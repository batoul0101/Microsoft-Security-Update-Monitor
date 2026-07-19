 Microsoft Security Update Monitor

An automated system to track and notify critical Microsoft security vulnerabilities in real-time.

📂 Project Overview
This project automates the process of checking the [Microsoft Security Update Guide API](https://api.msrc.microsoft.com/) to detect new security updates. It prevents manual tracking by sending instant alerts via Telegram.

 📷 Workflow Diagram
https://github.com/batoul0101/Microsoft-Security-Update-Monitor/blob/main/workflow11.png

 🚀 How to Implement
1. **Import:** Download the `security-monitor.json` file from the `/workflow` folder.
2. **Setup:** Import the JSON file into your n8n dashboard.
3. **Configure:** Update the Telegram credentials (Bot Token and Chat ID) in the Telegram node.
4. **Activate:** Toggle the "Active" switch to start the 24/7 monitoring.

 🛠 Tech Stack
- **Automation:** [n8n](https://n8n.io/)
- **API:** Microsoft MSRC API
- **Alerts:** Telegram Bot API

👥 Authors                                                                                                                                                                     
Batoul almahdi

Majd alsakkal
