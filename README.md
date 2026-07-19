# Microsoft-Security-Update-Monitor
Automated n8n workflow to monitor Microsoft security updates and send Telegram alerts
Microsoft Security Update Monitor
An automated system designed to monitor the Microsoft Security Update Guide (MSRC) in real-time. This project uses n8n to fetch the latest security vulnerabilities, compare them with previous data to avoid duplicates, and send instant alerts via Telegram.

🚀 Features
Real-time Monitoring: Automated 24/7 tracking of Microsoft security releases.

API-Driven: Connects directly to the official Microsoft API for high accuracy.

Duplicate Prevention: Uses logical filtering to ensure you only get notified about new updates.

Instant Alerts: Delivers updates directly to your Telegram chat.

🛠️ How to use
Download the security-monitor-bot.json file from this repository.

Import the JSON file into your n8n instance.

Configure your Telegram bot credentials (Token and Chat ID) in the Telegram node.

Activate the workflow to start monitoring.

👥 Authors
Batoul almahdi

Majd alsakkal
