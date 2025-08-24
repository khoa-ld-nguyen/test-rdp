# 🖥️ Free RDP with GitHub Actions + Ngrok

This repository gives you a **6-hour free Windows VPS** using GitHub Actions + Ngrok.

## ✨ Features
- Windows 2022 server via GitHub Actions
- RDP access via Ngrok (auto-reconnect)
- Preinstalled: Git, Node.js, Python, Chrome, VS Code
- Logs show the **latest Ngrok RDP URL** every 20 seconds

## 🚀 How to Use
1. Fork this repo.
2. Go to **Settings > Secrets and variables > Actions**.
3. Add a new secret:
   - Name: `NGROK_AUTH_TOKEN`
   - Value: your Ngrok token from https://dashboard.ngrok.com/get-started/your-authtoken
4. Go to **Actions > Free RDP Windows (VN Dev AutoReconnect)**.
5. Click **Run workflow**.
6. Wait ~1 minute, then check logs for RDP IP:PORT, username, and password.

## 🔑 Login Credentials
- **User:** `knguyen`
- **Password:** `P@ssw0rd123`

Enjoy your free VPS 🚀
