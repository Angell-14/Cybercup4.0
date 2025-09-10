# AI-Driven Anomaly Detection in Cloud Infrastructure

## Project Overview
This project develops an AI-powered system for **real-time anomaly detection** in cloud infrastructure, focusing specifically on **Express.js server logs**. Leveraging a **Retrieval Augmented Generation (RAG)** deep learning model, the system continuously monitors incoming server logs to detect unusual patterns or potential security threats such as **DDoS attacks**, **brute force attempts**, and other anomalies.

By automating log analysis, the system enables immediate threat detection and automated alert generation, reducing the need for manual log inspection and improving overall cloud security.

---

## 🚨 Problem Statement

- **Cloud Security Vulnerabilities**  
  Cloud systems face increasing numbers of cyberattacks, demanding more robust and automated security solutions.

- **Real-Time Detection Gaps**  
  Traditional security tools often struggle with real-time detection of evolving threats.

- **Manual Monitoring Inefficiency**  
  Manual log inspection is time-consuming, error-prone, and not scalable for large datasets typical of cloud environments.

---

## ✅ AI-Powered Solution

### Data Source  
- Continuously collect logs from an **Nginx server hosting an Express.js application on AWS EC2**.

### AI Model  
- Uses a **Retrieval Augmented Generation (RAG)** deep learning model trained on historical log data for anomaly detection.

### Alerts  
- Automated alerts are triggered upon detection of suspicious activity for immediate response.

---

## ⚙️ Workflow

1. **Data Collection & Training**  
   - Collected ~1000 rows of attack-related log data for model training.

2. **Log Collection**  
   - Real-time logs are streamed from the Express application.

3. **Model Inference**  
   - Logs are analyzed in real-time by the RAG model to detect anomalies.

4. **Data Visualization**  
   - Results are displayed on a web interface for easy interpretation.

5. **Alerts**  
   - Automated alerts notify the security team when threats are detected.

---

## 🧱 AI Model Architecture

- **Model Type**: Retrieval Augmented Generation (RAG) Deep Learning Model  
- **Training Dataset**: Curated historical attack logs  
- **Key Features**:
    - Detects various types of attacks  
    - Provides severity assessment across three levels  
- **Performance Metrics**:
    - Accuracy  
    - Precision  
    - Recall  
    - Predictions

---

## 🚀 Real-Time Log Monitoring

- Continuous log stream from the Express app
- Real-time processing by the AI model
- Immediate anomaly detection and flagging
- Automated alerts generated for any detected threats

---

## 🌟 Future Enhancements

- Support for additional cloud services and server types  
- Advanced detection of zero-day vulnerabilities and insider threats  
- Integration with security tools like Firewalls and Intrusion Detection Systems (IDS)

---

## ✅ Conclusion

This AI-based anomaly detection system provides a reliable and efficient solution for real-time threat detection in cloud environments. Automating log analysis significantly reduces response times to cyber threats, safeguarding cloud infrastructure while reducing the workload for security teams.

---

## 📁 Repository Contents

- `data/` – Training and testing log datasets  
- `models/` – Pre-trained RAG model files  
- `src/` – Source code for data collection, model inference, and alert generation  
- `web/` – Frontend for data visualization  
- `README.md` – Project documentation  

---

## 📧 Contact

For any questions or contributions, feel free to reach out.

## 🔗 LinkedIn Project Showcase

Check out the detailed project overview and media viewer on LinkedIn :

[View Project on LinkedIn](https://www.linkedin.com/in/saksham-malhotra-27tech/details/projects/1746025144555/single-media-viewer/?profileId=ACoAAD3kOucBw186Q423qDnAo1IIE5D-Y_9hLmo) 
