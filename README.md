# Black-dragon.1.0.1
👨‍💻Hacking📍 Facebook, Instagram, hacking a camera, making malicious links, phishing IP, creating a fake Facebook phishing page, extracting information from IP ☠️

Black-Dragon Tool | 2025 | Unlimited Power

⚡ A Multi-Tasking Ethical Hacking Tool ⚡

🔹 Account Cracking (Brute-Force) Professionally
✔ Supports login and brute-force attacks for Instagram and Facebook accounts
✔ Advanced password management and high-speed testing

🔹 Camera Exploit
✔ Capture photos from the target device's camera via a malicious link after approval
✔ Send and receive photos securely

🔹 IP Grabber via Malicious Link
✔ Generate smart links to attract victims
✔ Obtain IP, geolocation, device type, and browser details

🔹 Extract and Analyze Information from Any IP
✔ Various techniques for retrieving data
✔ Comprehensive geographic and security analysis

🔹 Create a Fake Facebook Login Page
✔ Professionally designed to mimic the official page
✔ Log user credentials after approval

💀 Power, Speed, Intelligence – All in Black-Dragon 💀







تنسي واضح وجذاب.


---


# 🚀 tool Black-dragon Setup Guide  

🔥 **Complete guide to setting up your Kali Linux environment with essential updates, packages, and Python libraries.**  

---

## 📌 Table of Contents  
🔹 [Update DNS Settings](#-update-dns-settings)  
🔹 [Update & Upgrade System](#-update--upgrade-system)  
🔹 [Install Essential Packages](#-install-essential-packages)  
🔹 [Install Python Libraries](#-install-python-libraries)  
🔹 [Install Playwright Browsers](#-install-playwright-browsers)  
🔹 [Troubleshooting](#-troubleshooting)  
🔹 [Final Note](#-final-note)  

---

## 🌍 Update DNS Settings  

If you experience **slow internet** or **repository connection issues**, update your DNS settings to **Google Public DNS**.  

🔹 **Run this command:**  

```bash
echo "nameserver 8.8.8.8" | sudo tee /etc/resolv.conf > /dev/null
echo "nameserver 8.8.4.4" | sudo tee -a /etc/resolv.conf > /dev/null

✅ This will:

Set 8.8.8.8 as the primary DNS server.

Set 8.8.4.4 as the secondary DNS server.


📌 If the issue persists, try using Cloudflare’s DNS:

echo "nameserver 1.1.1.1" | sudo tee /etc/resolv.conf > /dev/null
echo "nameserver 1.0.0.1" | sudo tee -a /etc/resolv.conf > /dev/null


---

🔄 Update & Upgrade System

Ensure your system is fully updated to avoid compatibility issues.

🔹 Run this command:

sudo apt update -y && sudo apt upgrade -y

📌 What this does:

apt update → Updates package lists.

apt upgrade → Installs the latest versions of all packages.


⚠️ If you get an error about a locked package manager:

sudo rm /var/lib/dpkg/lock /var/lib/dpkg/lock-frontend
sudo dpkg --configure -a


---

📦 Install Essential Packages

Install important tools like Python’s package manager and Chromium browser.

🔹 Run these commands:

sudo apt install -y python3-pip
sudo apt install -y chromium

📌 Why?

python3-pip → Manages Python libraries.

chromium → A lightweight browser for web automation.



---

🐍 Install Python Libraries

Install required Python packages using pip.

🔹 Run these commands:

pip install selenium --break-system-packages
pip install playwright --break-system-packages
pip install requests --break-system-packages
pip install flask --break-system-packages
pip install flask-cors --break-system-packages
pip install werkzeug --break-system-packages
pip install colorama --break-system-packages
pip install art --break-system-packages

📌 What they do:

selenium → Browser automation

playwright → Web testing

requests → HTTP requests

flask → Web framework

flask-cors → CORS support

werkzeug → WSGI utilities

colorama → Terminal colors

art → ASCII art



---

🌐 Install Playwright Browsers

After installing Playwright, install required browsers.

🔹 Run this command:

playwright install

📌 This installs:
✅ Chromium
✅ Firefox
✅ WebKit


---

⚠️ Troubleshooting

1️⃣ DNS or Connection Issues?
Try resetting DNS using Cloudflare:

echo "nameserver 1.1.1.1" | sudo tee /etc/resolv.conf > /dev/null
echo "nameserver 1.0.0.1" | sudo tee -a /etc/resolv.conf > /dev/null

2️⃣ APT Lock Issues?

sudo rm /var/lib/dpkg/lock /var/lib/dpkg/lock-frontend
sudo dpkg --configure -a

3️⃣ Pip Installation Fails?

pip install --upgrade pip

4️⃣ Playwright Installation Fails?

python -m playwright install


---

🎯 Final Note

🚀 Follow the steps carefully to ensure a smooth setup.
✅ If you encounter any errors, check the troubleshooting section.

🔥 Now, your Kali Linux is fully configured!

---
