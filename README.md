# IoT-Predictive-Maintenance
An IoT-Based Predictive Maintenance System that leverages AWS Cloud and Python analytics to forecast equipment failures before they occur. The system collects real-time sensor data through AWS IoT Core, processes it on AWS EC2, and uses machine learning models (Pandas, Scikit-learn) for predictive analytics.
# ⚙️ IoT-Based Predictive Maintenance System  

**Tech Stack:** Python | AWS IoT | EC2 | Pandas | Scikit-learn | Boto3  

An **IoT-enabled predictive maintenance system** designed to monitor industrial equipment, analyze sensor data in real time, and predict potential failures before they occur. The system uses **AWS Cloud** for data collection, processing, and alert automation, helping industries minimize downtime and optimize maintenance schedules.  

---

## 🧠 Project Overview
Industrial machines often fail unexpectedly, leading to costly downtime. This project demonstrates how IoT sensors and cloud-based analytics can detect anomalies and alert maintenance teams early.  
Data from IoT devices is streamed to **AWS IoT Core**, stored and processed on **AWS EC2**, and analyzed with **Python and Pandas** to forecast failures.  

---

## 🏗️ System Architecture
![Architecture](aws/architecture_diagram.png)

### Components
- **IoT Sensors:** Simulated temperature, vibration, and voltage data  
- **AWS IoT Core:** Collects and routes live data streams  
- **AWS EC2 Instance:** Runs predictive models and analytics scripts  
- **AWS SNS:** Sends automated alerts (email/SMS) when thresholds are breached  
- **Dashboard:** Python-based data visualization for equipment health  

---

## 🌟 Key Features
✅ Real-time data collection and preprocessing  
✅ Predictive analytics using ML models (Random Forest / Logistic Regression)  
✅ Automated failure alerts and notifications  
✅ Visualization dashboard for monitoring sensor trends  
✅ Scalable and cloud-deployed on AWS  

---

## 📂 Project Structure
