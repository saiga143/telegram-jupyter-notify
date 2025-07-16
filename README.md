# 🔔 Telegram Notifications for Jupyter Notebooks

This repository shows you how to receive **Telegram messages** when your Jupyter Notebook finishes running a cell or task.

No more constantly checking your screen — get notified instantly, whether you're training a model, processing geospatial data, or running a long Earth Engine export.

---

## 🚀 What You’ll Learn

- How to create a Telegram bot using `@BotFather`
- How to find your Telegram chat ID
- How to write a Python function that sends messages via your bot
- How to use this in a real Jupyter Notebook workflow

---

## 📂 Files in This Repo

| File | Description |
|------|-------------|
| `telegram_notify_example.ipynb` | A step-by-step notebook with all the code and setup instructions |
| `requirements.txt` | Python dependencies (just `requests`) |

---

## 📲 Getting Started

### 1. Install Requirements
```bash
pip install requests
```

### 2. Create a Telegram Bot

- Open Telegram and start a chat with `@BotFather`
- Type `/newbot` and follow instructions to create your bot
- Copy the API token that `@BotFather` gives you
  


### 3. Get your Chat ID

- Search for your bot in Telegram and click 'Start'. Send a 'Hi' message.
- Open the following URL in a browser (replace with your token):
  
  `https://api.telegram.org/bot<YOUR_TOKEN>/getUpdates`
- You'll see a response containing `"chat": { "id": 123456789 }` - this is your chat ID.



### 4. Open the notebook

- Open `telegram_notify_example.ipynb`
- Replace `PASTE_YOUR_BOT_TOKEN_HERE` and `PASTE_YOUR_CHAT_ID_HERE` with your values
- Run the cells and see the magic ✨

---

## 💡 Use Cases

- Model training that takes hours
- Huge reprojections or export tasks
- Heavy geospatial joins/data downloads
- Notebooks running on remote servers
- Any task where you don't want to keep checking progress manually

---

## 🔐 Security Notes

- This bot can only send messages to you, no access to files or data
- Do not share your token publicly
- If needed, you can regenerate the token anytime using `@BotFather`

---
## 🙏 Acknowledgements

Developed by Sai Ganesh Veeravalli, part of the DEPRIMAP Project at Karlstad University (https://sola.kau.se/deprimap/)

<img width="373" height="110" alt="466517323-a180a6e3-1b60-429d-b0b8-c14a45e4e190" src="https://github.com/user-attachments/assets/b5c8f717-2325-418b-b9ac-a46251a657fb" />

 

