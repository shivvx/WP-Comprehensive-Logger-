<h1 align="center">🧠 Auxra Comprehensive Logger</h1>
<h3 align="center">A powerful WordPress plugin for advanced logging to Telegram, Discord, Email, WooCommerce & CPanel — built by <a href="https://auxra.in">Auxra.in</a></h3>

<p align="center">
  <img src="https://img.shields.io/badge/Version-1.0.0-ff4d4d?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-GPL--2.0%2B-ff4d4d?style=for-the-badge" />
  <img src="https://img.shields.io/badge/WordPress-5.0+-ff4d4d?style=for-the-badge&logo=wordpress&logoColor=white" />
  <img src="https://img.shields.io/badge/Made%20by-Auxra.in-111?style=for-the-badge&logo=redhat&logoColor=ff4d4d" />
</p>

---

## ✨ Overview
**Auxra Comprehensive Logger** is an all-in-one WordPress logging and monitoring plugin that connects your website to **Telegram, Discord, Email, WooCommerce, and CPanel**, with a **modern, responsive admin panel** for full control.

Built for agencies, developers, and power users who want *complete visibility* and *real-time notifications* across their systems — in style.

---

## 🚀 Key Features

### 🔔 Telegram Logging
- Real-time Telegram alerts via your bot  
- HTML-formatted messages with emojis  
- Site name, URL, and critical info included

### 🎮 Discord Logging
- Webhook integration with **rich embeds**  
- Thread-based message organization per site  
- Customizable color-coded embed designs

### 📧 Email Logging
- Track all outgoing and incoming emails  
- HTML-formatted reports and summaries  
- Real-time or scheduled delivery

### 🛒 WooCommerce Logging
- Full **order lifecycle** monitoring  
- Track **products, customers, and inventory**  
- Alert on low stock, coupon usage, or reviews  
- Subscription support (if plugin active)

### 🖥️ CPanel Monitoring
- Watch for WordPress core/plugin/theme updates  
- Disk usage, bandwidth, and backup alerts  
- Detect outdated or vulnerable components  
- File and DB change tracking

### ⚙️ Core Features
- Category-based log organization  
- AJAX-powered tests for connections  
- Export settings/logs instantly  
- Real-time system dashboard  
- Fully responsive, modern admin UI

---

## 🧩 Installation

1. Download `auxra-comprehensive-logger.zip`
2. Upload to `/wp-content/plugins/`
3. Activate via **Plugins → Auxra Logger**
4. Configure in **Settings → Auxra Logger**

---

## ⚙️ Configuration Quick-Start

### **Telegram**
1. Create a bot via [@BotFather](https://t.me/botfather)  
2. Get your **Bot Token** and **Chat ID**  
3. Enter both under **Telegram Tab** in settings  

### **Discord**
1. Go to Server Settings → Integrations → Webhooks  
2. Create webhook, copy the URL  
3. Paste it in the **Discord Tab**

### **Email**
1. Enable Email logging  
2. Set the recipient and frequency (instant / hourly / daily)

### **WooCommerce**
1. Active automatically if WooCommerce detected  
2. Configure which events to track under **WooCommerce Tab**

### **CPanel**
1. Enable in **CPanel Tab**  
2. Add host, username, password, and port  
3. Set thresholds for alerts (disk, bandwidth, etc.)

---

## 🧠 Admin Interface

| Feature | Description |
|----------|-------------|
| 🧭 **Tabbed Navigation** | Organized sections for General, Telegram, Discord, Email, WooCommerce, CPanel, Logs |
| ⚡ **AJAX Testing** | Instant integration tests for Telegram/Discord |
| 📊 **System Dashboard** | Shows PHP, WP, WC versions and system info |
| 🧾 **Log Viewer** | Filter, search, and export logs easily |
| 📱 **Responsive Design** | Works on desktop, tablet, and mobile |

---

## 🧱 Usage

### 👥 **User Activity**
- Logins, logouts, registrations, profile edits, password changes  
- Role changes and deletions  

### 📰 **Content Management**
- Post/page create/update/delete  
- Comments, media, categories, and tags  

### ⚙️ **System Events**
- Plugin/theme activations  
- WordPress core updates  
- PHP warnings and DB optimizations  

### 🛍️ **WooCommerce**
- Orders, payments, stock, and coupon usage  
- Customer registrations and updates  

### 🔐 **Server Monitoring**
- Disk usage, bandwidth, and backups  
- Security checks and file system updates  

---

## 🧰 Requirements
- **WordPress:** 5.0+  
- **PHP:** 7.4+  
- **WooCommerce:** Optional  
- **cURL:** Required  

---

## 📁 File Structure

```bash
📂 auxra-comprehensive-logger/
├── 📄 auxra-comprehensive-logger.php        # Main plugin bootstrap
├── 📂 includes/
│   ├── 📄 class-auxra-logger.php            # Core logging engine
│   ├── 📄 class-telegram-logger.php         # Telegram integration
│   ├── 📄 class-discord-logger.php          # Discord integration
│   ├── 📄 class-email-logger.php            # Email logging module
│   ├── 📄 class-woocommerce-logger.php      # WooCommerce event logging
│   ├── 📄 class-cpanel-logger.php           # CPanel monitoring integration
│   └── 📄 class-admin-settings.php          # Admin panel + settings management
├── 📂 assets/
│   ├── 📂 css/
│   │   └── 📄 admin.css                     # Admin interface styles
│   └── 📂 js/
│       └── 📄 admin.js                      # Admin-side JavaScript
└── 📄 TODO.md                               # Development notes
```
---

## 🔒 Security
- Nonce verification for all AJAX actions  
- Strict capability checks for admin areas  
- Input sanitization and escaping  
- Secure API key storage  
- Error masking and safe fallbacks  

---

## ⚡ Performance
- Optimized queries and async logging  
- Background AJAX tasks for heavy ops  
- Smart caching of settings  
- Lightweight UI and fast response time  

---

## 🧩 Troubleshooting

| Issue | Possible Fix |
|--------|---------------|
| Telegram not sending | Check Bot Token & Chat ID |
| Discord not working | Verify Webhook URL & permissions |
| Email logs missing | Check spam folder or WP mail setup |
| CPanel errors | Confirm credentials & API access |

Enable **Debug Mode** in General Tab for detailed logs.

---

## 🤝 Contributing
1. Fork this repo  
2. Create a feature branch  
3. Commit & test changes  
4. Submit a PR  

---

## 📅 Changelog
### **v1.0.0**
- Initial release  
- Modern admin UI  
- Full Telegram, Discord, Email, WooCommerce & CPanel integration  
- AJAX log testing and export tools  
- Responsive dashboard  

---

## 🧾 License
GPL v2 or later

Copyright (C) 2025
Shivam Kumar / Auxra.in

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software Foundation,
either version 2 of the License, or (at your option) any later version.


---

<p align="center">
  <b>Developed with ❤️ by <a href="https://auxra.in">Shivam Kumar · Auxra.in</a></b><br/>
  <sub>Empowering WordPress developers with precision, design, and automation.</sub>
</p>


