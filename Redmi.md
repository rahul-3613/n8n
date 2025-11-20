
# 🚀 n8n WhatsApp Automation Workflows (Redmi Edition)

<div align="center">

![n8n Workflows](https://img.shields.io/badge/n8n-Workflows-orange?style=for-the-badge\&logo=n8n)
![WhatsApp Automation](https://img.shields.io/badge/WhatsApp-Automation-green?style=for-the-badge)
![Integrations](https://img.shields.io/badge/Integrations-50+-blue?style=for-the-badge)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge\&logo=buy-me-a-coffee\&logoColor=black)]

</div>

---

## 🌟 Overview

This repository contains a collection of **WhatsApp automation workflows** built using **n8n**, optimized for Redmi users or WhatsApp business automation setups.
Key features include:

* Auto reply to messages using **templates** or **AI**
* Dynamic **user database tracking**
* Command-based responses (like `/help`, `/menu`)
* Logging and analytics
* Fully compatible with **n8n Webhook & WhatsApp Cloud API**

---

## 🚀 Workflow Architecture

```mermaid
graph TD

    A[WhatsApp User] -->|Sends Message| B[WhatsApp Cloud API Webhook]

    B --> C[n8n Webhook Trigger]

    C --> D[Router Node]
    D -->|New User| E[Create User in Database]
    D -->|Existing User| F[Fetch User Profile]

    D -->|Command Based| G[Command Handler]
    D -->|Normal Text| H[AI Reply Generator]

    G --> I[Generate Template Reply]
    H --> I

    I --> J[Send WhatsApp Message via API]

    J --> K[Log Message to DB/Sheet]
    K --> L[Analytics Dashboard]
```

---

## 💻 How It Works

1. **User Sends Message:** Any WhatsApp user sends a message to your number.
2. **Webhook Trigger:** WhatsApp Cloud API forwards the message to n8n.
3. **Routing:** The workflow checks if the user exists, then decides which branch to follow.
4. **Reply Generation:**

   * **Template Reply:** Predefined responses for commands like `/help`, `/menu`
   * **AI Reply:** Smart AI-generated responses for normal messages
5. **Send Response:** Reply is sent back via WhatsApp Cloud API.
6. **Logging & Analytics:** All messages are logged in DB/Sheet for insights.

---

## 🏗️ Tech Stack

* **Automation Platform:** n8n
* **Messaging API:** WhatsApp Cloud API
* **Database:** SQLite / Google Sheets / Airtable
* **AI Engine:** OpenAI (optional for smart replies)
* **Deployment:** Docker / Local Server

---

## 📂 Repo Structure

```
n8n-whatsapp-automation/
├── workflows/          # n8n workflow JSONs
│   ├── whatsapp-webhook.json
│   ├── ai-reply.json
│   └── template-reply.json
├── db/                 # User data and logs
├── scripts/            # Optional helper scripts
└── README.md
```

---

## 🤝 Contributing

* 🐛 Report bugs via **Issues**
* 💡 Suggest features via **Discussions**
* 📝 Add new workflow JSONs for WhatsApp automation
* ⭐ Star the repo to support development

---

## 🔒 Security

* ✅ Input validation & sanitization
* ✅ Webhook authentication
* ✅ Rate limiting & logging
* ✅ Non-root Docker container deployment

---

## 💖 Support

<div align="center">

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge\&logo=buy-me-a-coffee\&logoColor=black)](https://www.buymeacoffee.com/zie619)

</div>

# 🚀 n8n WhatsApp Automation Workflows (Redmi Edition)

<div align="center">

![n8n Workflows](https://img.shields.io/badge/n8n-Workflows-orange?style=for-the-badge\&logo=n8n)
![WhatsApp Automation](https://img.shields.io/badge/WhatsApp-Automation-green?style=for-the-badge)
![Integrations](https://img.shields.io/badge/Integrations-50+-blue?style=for-the-badge)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge\&logo=buy-me-a-coffee\&logoColor=black)](https://www.buymeacoffee.com/zie619)

</div>

---

## 🌟 Overview

This repository contains a collection of **WhatsApp automation workflows** built using **n8n**, optimized for Redmi users or WhatsApp business automation setups.
Key features include:

* Auto reply to messages using **templates** or **AI**
* Dynamic **user database tracking**
* Command-based responses (like `/help`, `/menu`)
* Logging and analytics
* Fully compatible with **n8n Webhook & WhatsApp Cloud API**

---

## 🚀 Workflow Architecture

```mermaid
graph TD

    A[WhatsApp User] -->|Sends Message| B[WhatsApp Cloud API Webhook]

    B --> C[n8n Webhook Trigger]

    C --> D[Router Node]
    D -->|New User| E[Create User in Database]
    D -->|Existing User| F[Fetch User Profile]

    D -->|Command Based| G[Command Handler]
    D -->|Normal Text| H[AI Reply Generator]

    G --> I[Generate Template Reply]
    H --> I

    I --> J[Send WhatsApp Message via API]

    J --> K[Log Message to DB/Sheet]
    K --> L[Analytics Dashboard]
```

---

## 💻 How It Works

1. **User Sends Message:** Any WhatsApp user sends a message to your number.
2. **Webhook Trigger:** WhatsApp Cloud API forwards the message to n8n.
3. **Routing:** The workflow checks if the user exists, then decides which branch to follow.
4. **Reply Generation:**

   * **Template Reply:** Predefined responses for commands like `/help`, `/menu`
   * **AI Reply:** Smart AI-generated responses for normal messages
5. **Send Response:** Reply is sent back via WhatsApp Cloud API.
6. **Logging & Analytics:** All messages are logged in DB/Sheet for insights.

---

## 🏗️ Tech Stack

* **Automation Platform:** n8n
* **Messaging API:** WhatsApp Cloud API
* **Database:** SQLite / Google Sheets / Airtable
* **AI Engine:** OpenAI (optional for smart replies)
* **Deployment:** Docker / Local Server

---

## 📂 Repo Structure

```
n8n-whatsapp-automation/
├── workflows/          # n8n workflow JSONs
│   ├── whatsapp-webhook.json
│   ├── ai-reply.json
│   └── template-reply.json
├── db/                 # User data and logs
├── scripts/            # Optional helper scripts
└── README.md
```

---

## 🤝 Contributing

* 🐛 Report bugs via **Issues**
* 💡 Suggest features via **Discussions**
* 📝 Add new workflow JSONs for WhatsApp automation
* ⭐ Star the repo to support development

---

## 🔒 Security

* ✅ Input validation & sanitization
* ✅ Webhook authentication
* ✅ Rate limiting & logging
* ✅ Non-root Docker container deployment

---

## 💖 Support

<div align="center">

[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-FFDD00?style=for-the-badge\&logo=buy-me-a-coffee\&logoColor=black)](https://www.buymeacoffee.com/zie619)

</div>
 <h3 align="center">Passionate Competitive Programmer</h3>
<div align="center">

  <h3>Passionate Competitive Programmer</h3>

  <img alt="Coding" width="400" src="https://cdn.dribbble.com/users/416610/screenshots/4801105/coding_desk_flat_vector_ui_ux_design_illustration_motion_animation_gif2.gif" style="float:right; margin-left:20px;"/>

</div>

