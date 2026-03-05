# 🤖 Robotics Lab Monitoring Platform

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white" alt="Apache Spark" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white" alt="Databricks" />
</p>

## 📌 Project Overview
The **Robotics Lab Monitoring Platform** is a data-driven system designed to monitor the environment of the ** Robotics Lab** at Braude Academic College. The project leverages **Apache Spark** for distributed data processing and **Firebase** as a Realtime Database to manage and analyze sensor data (Temperature, Humidity, Motion, and Distance).

## 📢 Features

**✅ Real-Time IoT Data Integration**
* Synchronizes live sensor data from a Raspberry Pi to a **Firebase Realtime Database**.
* Implemented a **Gemini AI ChatBot** interface for natural language querying of current lab metrics.

**✅ Big Data Analytics with Apache Spark**
* Utilizes **PySpark** to process large-scale sensor logs and user comments.
* Implemented **MapReduce** algorithms to identify key patterns and frequently reported issues in the lab.

**✅ Anomaly Detection & Visualization**
* Automated detection of environmental anomalies (e.g., temperature spikes or high humidity).
* Interactive dashboards created in **Databricks** for historical trend analysis.

**✅ Advanced Management Dashboard**
* Role-based user management (Manager/Engineer) to control system access and lab oversight.

## 🛠 Tech Stack

**⚙️ Data Engineering & Cloud**
* **Apache Spark (PySpark):** Core framework for distributed processing and text analysis.
* **Firebase:** Real-time NoSQL database for hardware-software synchronization.
* **Databricks:** Unified analytics platform for collaborative data engineering.

**🖥 Hardware & Communication**
* **Python:** Scripting for sensor data collection and MQTT/Firebase integration.
* **MQTT:** Protocol used for lightweight sensor messaging between devices.

## 📐 System Flow



## 📂 Repository Structure
* `scripts/`: Python scripts for sensor integration and data uploading.
* `pyspark_notebooks/`: Spark-based notebooks for MapReduce analysis and anomaly detection.
* `docs/`: Technical reports and project documentation.

## 💻 How to Run Locally

1. **Firebase Configuration:**
   Place your `serviceAccountKey.json` in the project root and update your `databaseURL` in the config file.

2. **Clone the repository:**
   ```bash
   git clone [https://github.com/rober-saliba/Robotics-Lab-Monitoring-Platform.git](https://github.com/rober-saliba/Robotics-Lab-Monitoring-Platform.git)
    ```
3.Install Dependencies:
    ```bash
   pip install pyspark firebase-admin paho-mqtt
    ```

    
4.Execute on Databricks:
Import the notebooks to your Databricks Workspace to run the distributed Spark jobs.
