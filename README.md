# LUCY_ADV 🦇

**Advanced Phishing Framework for Red Teamers & Security Pros**

LUCY_ADV is a modular, configurable phishing toolkit designed to emulate real-world phishing campaigns. It captures credentials, collects device metadata, and supports email spoofing and tunneling—ideal for authorized penetration tests and security awareness exercises.

---

## ✨ Features

- **Prebuilt Phishing Templates**  
  Clone popular login pages (e.g. Office 365, Google, Facebook) with easy customization.

- **Real‑Time Credential Capture**  
  Fetches usernames, passwords, session cookies, IP addresses, user agents, and geolocation info.

- **Device Fingerprinting**  
  Gathers OS, browser version, screen resolution, and other environment data.

- **Email Delivery Support**  
  Includes SMTP-based mailer; supports standard headers and templated interactions.

- **HTTPS & Tunneling**  
  Works with ngrok, localtunnel, or custom HTTPS setups.

- **Logging & Export**  
  Timestamped logs with optional CSV/JSON exports for easy reporting.

- **Basic Evasion**  
  Simple anti-bot/user-agent filters to reduce detection by scanners.

---

## ✅ Requirements

- Linux (or WSL on Windows)
- Bash shell
- `curl` or `wget`
- `ngrok` or equivalent tunneling method (optional)
- Basic SMTP credentials (optional—for email delivery)

---

## 🚀 Installation

Clone and launch in seconds:

```bash
git clone --depth=1 https://github.com/lucifer14333/LUCY_ADV.git
cd LUCY_ADV
bash lucy.sh
