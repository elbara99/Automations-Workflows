# Automation Workflows by **Elbara Mouaffak** 🚀

[![n8n](https://img.shields.io/badge/Automations-n8n-orange)](#) [![Zapier](https://img.shields.io/badge/Automations-Zapier-red)](#) [![Make.com](https://img.shields.io/badge/Automations-Make.com-purple)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE) [![Languages](https://img.shields.io/badge/Docs-English-blue)](#)

---

## About Me

Hi, I’m **Elbara Mouaffak**, a no‑code workflow automation specialist focused on **n8n**. I help businesses save hours every week and scale faster with reliable, API‑driven automations — no code required.

> ✅ **First audit is FREE** — message me your idea and I’ll suggest a ready‑to‑use scenario.

---

## 🔧 Services

* n8n workflow design, debugging, and maintenance
* API/webhook integrations (REST, GraphQL)
* CRM, e‑commerce, and marketing automations
* Monitoring, logging, and error‑handling best practices

**Full services list →** [Open Notion page](https://www.notion.so/2424f7e5cb5b81f999f6da0dc91afd03?pvs=21)

---

## 🧩 Example Use Cases

* 🛒 **For Online Stores**: When an order is confirmed → auto‑send WhatsApp message + update Google Sheets + notify via Telegram.
* 📥 **For Freelancers/Agencies**: When a form is submitted → create a task in Trello + send confirmation email + save contact to Airtable.
* 📈 **For Business Owners**: Daily report from multiple sources sent to your phone **every morning**.

---

## 📁 Repository Structure

Organize workflows by platform:

```bash
automation-workflows/
├── n8n/
│   ├── customer-support.json
│   ├── lead-generation.json
├── make/
│   ├── ecommerce-automation.json
├── zapier/
│   ├── gmail-slack.zap.json
├── assets/
│   └── screenshots/   # Optional screenshots
└── README.md
```

> **Note**: Some tools don’t support direct JSON imports (like certain Zapier Zaps). Add a small README inside the folder explaining manual setup steps.

---

## ▶️ How to Use (Import)

### n8n

1. Open n8n → **Workflows** → **Import from File**.
2. Choose a `.json` file from the `n8n/` folder.
3. Update **Credentials** and **Environment variables** as needed.

### Make (Integromat)

1. Open Make → **Scenarios** → **Create new**.
2. Rebuild the modules as shown in the description (or import JSON if available).
3. Test with dummy data before going live.

### Zapier

* If no JSON import is available, create a new Zap manually following the instructions in each Zap’s README.

---

## ⭐ Why Work With Me?

* 🧠 Experienced with complex **n8n** workflows
* 🛠️ No‑code + API integration specialist
* 🇩🇿 Based in Algeria with global project experience
* 💬 Fast communication in **Arabic, French, English**
* ✅ **First audit is free**

---

## 📞 Contact

* **WhatsApp:** [wa.me/213778877361](https://wa.me/213778877361)
* **Instagram:** [@elbara.ai](https://instagram.com/elbara.ai)
* **Email:** [elbaraemoueffek@gmail.com](mailto:elbaraemoueffek@gmail.com)

---

## 🎁 Free Templates & Portfolio

* **Portfolio Items:** [Open Notion page](https://www.notion.so/2424f7e5cb5b819887c3c4d6ad3e114e?pvs=21)

---

## 🧱 Quality & Safety

* All files are educational/boilerplate. Always review third‑party costs and rate limits before production.
* Store API keys in **.env** (never commit them to GitHub).

```bash
# Example .env
N8N_WEBHOOK_URL=
TELEGRAM_BOT_TOKEN=
WHATSAPP_API_KEY=
AIRTABLE_API_KEY=
```

---

## 🤝 Contributing

PRs are welcome! Open an **Issue** to describe bugs or ideas, or submit a Pull Request with:

* Clear description of changes
* Screenshots (if relevant)
* Test steps

---

## 📜 License

This repository is licensed under the **MIT License**. See `LICENSE` for details.

---

### Quick Start

```bash
# 1) Clone
git clone https://github.com/<your-username>/automation-workflows.git
cd automation-workflows

# 2) Create folders
mkdir -p n8n zapier make assets/screenshots

# 3) Commit & push
git add .
git commit -m "chore: init repo structure"
git branch -M main
git remote add origin https://github.com/<your-username>/automation-workflows.git
git push -u origin main
```

---

> **Need a custom automation?** DM me on WhatsApp and I’ll sketch a ready‑to‑import n8n workflow for your use case.
