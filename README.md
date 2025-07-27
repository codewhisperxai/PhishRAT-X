**PhishRAT-X**

> 💻 Real-time Phishing + Remote Access Tool (Educational & Ethical Use Only)
> ⚙️ Platform: Termux, Kali Linux, Parrot OS
> 🧰 Built with: Bash + PHP + Ngrok + Python + msfvenom

---

## 📦 Features Overview

| Feature                       | Description                             |
| ----------------------------- | --------------------------------------- |
| 🎯 **Phishing Templates**     | Facebook, Gmail, Instagram, WhatsApp    |
| 🔐 **Credential Logging**     | Real-time logs saved to file            |
| 📡 **Ngrok Integration**      | One-click tunnel setup                  |
| 💥 **RAT Payload Generator**  | Android reverse TCP payloads            |
| 📥 **Auto Send Payload**      | Send APK after user submits credentials |
| 🔁 **Session Listener (MSF)** | Metasploit auto-listener launcher       |
| 📲 **Mobile Friendly**        | Fully works in Termux                   |
| 🔒 **Offline Mode**           | Use on LAN without internet             |
| 🛡️ **Failsafe Exit**         | Auto-kills PHP/Ngrok on exit            |

---

## 🧾

````markdown
# PhishRAT-X 🔥
> 🎣 Advanced Phishing + RAT Payload Generator for Ethical Use Only  
> 📱 Works on Android (Termux), Kali, and Parrot OS  
> ⚠️ Educational Purposes Only!

---

## 📌 Description

PhishRAT-X is a hybrid toolkit designed for **ethical hacking demonstrations**, **phishing simulations**, and **remote access testing** using Android devices or Linux terminals. This tool combines **credential phishing** with **automatic payload generation**, simulating **real-world red team scenarios** in a controlled, permissioned environment.

---

## 🚀 Features

- 🎯 Facebook, Gmail, Instagram phishing pages
- 📡 Ngrok or localhost server tunnel
- 📥 Auto-generate malicious APK via `msfvenom`
- 🔐 Credentials saved in `/logs/creds.txt`
- 💣 One-click listener using Metasploit
- 🧠 Realistic simulation for awareness training

---

## 📱 Requirements

- Termux / Kali Linux / Parrot OS
- PHP, Python, wget, curl
- Ngrok (optional, for external tunnel)
- Metasploit Framework

---

## 🛠️ Installation

```bash
git clone https://github.com/yourname/PhishRAT-X
cd PhishRAT-X
bash setup.sh
````

---

## 🎣 Usage

```bash
bash phishratx.sh
```

> Choose template → Ngrok auto starts → Fake page loads
> When user submits credentials, APK is auto-sent + listener runs

---

## 🔎 Sample Output

```bash
[+] Starting Facebook Phishing Server...
[+] Ngrok Public URL: https://fb-login.ngrok.io
[+] Waiting for victim to submit data...

[+] [Captured] Email: hackeduser@example.com
[+] [Captured] Pass: 12345678

[+] Generating RAT APK...
[+] File saved as payload.apk

[+] Launching Metasploit Listener...
```

---

## 🧠 Educational Use Only

⚠️ This tool is meant for training and legal testing environments only. Never use it against targets without proper consent. Misuse can result in criminal charges. You are responsible for your actions.

---

## 🧩 Coming Soon

* ☁️ Telegram Bot Alert Integration
* 🎛️ Web dashboard to manage logs & sessions
* 🔐 AES Encryption for logs

---

```

---

