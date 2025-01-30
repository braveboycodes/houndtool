# 🐾 **Hound v0.2**  
*By Brave Boy Codes, inspired by [TechChip](https://youtube.com/techchipnet)*

![Hound Banner](https://example.com/banner_image.jpg)  
*Tool for information gathering and GPS coordinates capture.*

---

## **🔍 Overview**

**Hound v0.2** is a simple and lightweight tool designed for **information gathering** and **GPS coordinates capture**. It runs either via **Cloudflare tunneling (cloudflared)** or locally using a **PHP server**, allowing users to expose targets and capture crucial data like **IP addresses** for penetration testing.

Inspired by TechChip, this tool provides an easy-to-use and efficient way to collect data and interact with target systems.

---

## **✨ Features**

- **💡 Information Gathering**: Automatically captures the **IP addresses** of users who visit the malicious link.
- **🌐 Cloudflare Tunneling**: Expose your server publicly with Cloudflare's tunneling for an accessible URL.
- **🏠 Local Server**: Run Hound on **localhost:8080** if Cloudflare is unavailable.
- **⚙️ Payload Integration**: Seamlessly integrate a payload to capture more user information.
- **📂 Data Logging**: Logs all gathered information in a structured format for easy review.

---

## **📦 Dependencies**

To run Hound, ensure you have the following installed:

- **PHP** (for the local server)
- **Cloudflared** (for tunneling)
- **Wget** (for downloading cloudflared)
- **Linux** or compatible Unix-based systems

Install the missing dependencies:
```bash
sudo apt-get install php wget
