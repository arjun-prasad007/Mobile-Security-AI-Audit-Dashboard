# 🛡️ Mobile Security AI Audit Dashboard

An automated mobile security auditing tool that performs hardware health checks and software vulnerability analysis using Python, ADB, and VirusTotal API.

## 🚀 Overview
This project is designed for security enthusiasts and system administrators to perform a quick security audit on Android devices. It extracts installed applications, checks their reputation against global threat intelligence databases, and monitors system health metrics like battery and storage.

## ✨ Features
- Automated App Extraction: Fetches all 3rd party apps via ADB.
- Threat Intel Integration: Uses VirusTotal API to classify apps as CLEAN or MALICIOUS.
- Hardware Monitoring: Real-time tracking of device model and battery percentage.
- Interactive Dashboard: Built with Streamlit for a professional data visualization experience.

## 🛠️ Tech Stack
- Language: Python 3.x
- Tools: Android Debug Bridge (ADB)
- Frontend: Streamlit
- Data: Pandas & CSV
- 
## 🚦 How to Run
1. Connect your Android device with USB Debugging enabled.

   ![](/assets/MODEL.png)
   
2. Run the scanner:
  
   python advanced_scan.py

   ![](/assets/CMD.png)

3.Launch the dashboard:

streamlit run dashboard.py

![](/assets/DASHBOARD-1.png)
![](/assets/DASHBOARD-2.png)

📝 Project Structure
advanced_scan.py: Backend script for ADB extraction and API calls.
dashboard.py: Frontend script for visualization.
Advanced_Security_Report.csv: Generated audit report.
