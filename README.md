# 🎨 Prompt2Pixel – Telegram Image Generation Bot (n8n)

Prompt2Pixel is an **AI-powered Telegram bot** built using **n8n** that converts natural language prompts into **AI-generated images**.
Users simply send a text message to the bot, and it returns a generated image URL using the **Gemini 3 Pro Image Preview** model.

---

## ▶️ Demo

To see the app in action, try the live Telegram bot here:
👉 [https://t.me/promptPixelBot](https://t.me/promptPixelBot)

---

## ✨ Features

* 🤖 Telegram-based AI image generation bot
* 🎨 Converts text prompts into images
* 🧠 Uses **Gemini 3 Pro Image Preview** model
* 🔁 Fully automated **n8n workflow**
* 🧾 Clean, well-documented, open-source friendly

---

## 🧩 Workflow Overview

**Flow:**

```
Telegram Message
   ↓
Check /start Command
   ├─ /start → Send Welcome Message
   └─ prompt → Generate Image → Send Image URL
```

---
<img width="1182" height="667" alt="image" src="https://github.com/user-attachments/assets/622f8fc8-fcf5-4c49-9a7e-cd6e3d9f8b85" />
---


### Node Responsibilities

* **Telegram Bot Trigger** – Listens for incoming Telegram messages
* **Check /start Command** – Handles onboarding vs prompt input
* **Send Welcome Message** – Explains usage with an example
* **Generate Image from Prompt** – Calls the image generation API
* **Send Image URL** – Sends the generated image back to the user

---

## 📂 Repository Contents

* 📄 `Prompt2Pixel.json` – Exported n8n workflow
* 📘 `README.md` – Project documentation

---

Here’s a **clean, professional rephrased version** that fits perfectly in a GitHub README 👇

---

## 🔐 Credentials & Security

> ⚠️ **This repository does not include any credentials**

After importing the workflow, you need to configure the following:

* ✅ **Telegram Bot API credentials**

To create a Telegram bot and obtain the required bot token, follow the guide below and complete **up to Step 5 (Get the Bot Token)**:
👉 [https://nicegram.app/blog/how-to-create-a-telegram-bot-complete-beginners-guide](https://nicegram.app/blog/how-to-create-a-telegram-bot-complete-beginners-guide)

---

## 🚀 How to Use

### 1️⃣ Import Workflow

* Open n8n
* Click **Import workflow**
* Upload `Prompt2Pixel.json`

### 2️⃣ Configure Credentials

* Add Telegram Bot credentials
* Add HTTP Bearer Auth credentials

### 3️⃣ Activate Workflow

* Enable the workflow
* Start chatting with your Telegram bot 🎉
---

## 💬 Example Usage

```
User: A futuristic cyberpunk city at night, neon lights, ultra-detailed
Bot: https://generated-image-url.com/image.png
```

---



