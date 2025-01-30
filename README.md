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
<p>This tool require PHP for webserver, wget & unzip for download and extract cloudflare. First run following command on your terminal</p>
'''
apt-get -y install php unzip git wget
'''

## **🚀 Installation**
Clone the Repository: Clone the repository using the following command:

'''
git clone https://github.com/techchipnet/hound
cd hound
'''

Install Dependencies: Make sure PHP and Wget are installed on your system. You can install them using:

'''
sudo apt-get install php wget
'''

Make Script Executable: Grant execute permissions to the script:

'''
chmod +x hound.sh
'''

Run Hound: Execute the tool:

'''
./hound.sh
'''

##**⚙️ Usage**
Running the Tool  
Once executed, the tool will display a banner and prompt you to choose whether to use Cloudflare tunneling or run it locally.

If you select Cloudflare tunneling, Hound will generate a public URL that can be shared with the target.

If you select the local server option, it will run the tool on localhost:8080.

Hound will wait for the target to open the link, and once they do, it will capture the IP address and any other relevant data, such as GPS coordinates (if applicable).

The captured information is saved in the data.txt file and can be reviewed for further analysis.

##**📂 Files Generated**
data.txt: Captures data from the target (including IP).  
saved.ip.txt: Stores the IP addresses of targets.  
targetreport.txt: A log of all the collected data for reporting purposes.

##**🛠️ Troubleshooting**
Common Issues  
PHP Not Installed:  
If PHP is not installed, use:  
'''
sudo apt-get install php
'''

Cloudflared Issues:  
If Cloudflared is not installed, make sure to download the correct version based on your system's architecture. The script handles this automatically.

Permission Issues:  
If you encounter permission issues when executing the script, ensure you’ve granted execute permissions:

chmod +x hound.sh

Firewall/Network Restrictions:  
If the tool is not functioning as expected, ensure that your firewall or network settings allow outbound traffic and DNS resolution for Cloudflare.

##**💡 Contributions**
Contributions are always welcome! If you have any suggestions, bug fixes, or improvements, feel free to open an issue or submit a pull request.

##**📜 License**
This project is licensed under the MIT License. See the LICENSE file for more details.

##**👨‍💻 Credits**
Brave Boy Codes for developing this tool.  
TechChip for the inspiration behind the concept.
