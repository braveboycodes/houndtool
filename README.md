# 🐾 **Hound v0.2**  
*By Brave Boy Codes, inspired by [TechChipNet](https://youtube.com/techchipnet)*  

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

# What is Hound?
<p>Hound is a tool that can remotely capture the exact GPS coordinates of a target device using a PHP server, and can also grab basic information about the system and ISP. This tool can be very helpful in information gathering. you can get following information of the target device</p>
<ul>
  <li>Longitude</li>
  <li>Latitude</li>
  <li>Device Model</li>
  <li>Operating System</li>
  <li>Number of CPU Cores</li>
  <li>Screen Resolution</li>
  <li>User agent</li>
  <li>Public IP Address</li>
  <li>Browser Name</li>
  <li>ISP Information</li>
</ul>

## Features
  <p>The tool offers a wide range of features and functionality, including:</p>
    <ul>
  <li>Capture Exact GPS Location</li>
  <li>Automated Data Collection</li>
   <li>User-friendly Interface</li>
</ul>

## This Tool Works On :
<ul>
  <li>Kali Linux</li>
  <li>Windows(WSL)</li>
  <li>Termux</li>
  <li>MacOS</li>
  <li>Ubuntu</li>
  <li>Parrot Sec OS</li>
</ul>

## Installing and requirements
<p>This tool require PHP for webserver, wget & unzip for download and extract cloudflare. First run following command on your terminal</p>

```
apt-get -y install php unzip git wget
```

## Installing (Kali Linux/Termux):

```
git clone https://github.com/techchipnet/hound
cd hound
bash hound.sh
```
## Change log:
Version: 0.2: Remove Ngrok and update cloudflared tunnel

### Video Demo
[![Hound Demo](https://img.youtube.com/vi/IiJRyVmITgI/0.jpg)](https://www.youtube.com/watch?v=IiJRyVmITgI)

### For More Video subcribe <a href="http://youtube.com/braveboycodes">Brave Bpy Codes YouTube Channel</a>
<p>Hound is created to help in penetration testing and it's not responsible for any misuse or illegal purposes.</p>
<p>credit - Chatbot template : Masud Rana</p>
The Main Credit : TechChipNet
