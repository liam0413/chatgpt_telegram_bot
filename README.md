# 🚀 **ChatGPT Telegram Bot: Fast. No Limits. Special Chat Modes**

We all love [chat.openai.com](https://chat.openai.com), but… it’s **laggy**, has **daily limits**, and is only available via an **outdated web interface**.

💡 **Solution?** A **lightning-fast** Telegram bot that brings ChatGPT directly to you!

👉 Deploy your own bot or use mine: [@Solomon](https://t.me/Solomon)

---

## 🌟 **Why This Bot?**
✅ **Super Fast** – Replies in **3-5 seconds**  
✅ **Unlimited Access** – No request limits  
✅ **Message Streaming** – Real-time responses  
✅ **GPT-4 & GPT-4 Turbo** – Advanced AI at your fingertips  
✅ **GPT-4 Vision** – Image recognition capabilities  
✅ **Voice Messages** – AI listens & responds  
✅ **Group Chat Support** – Just type `/help_group_chat`  
✅ **DALLE 2** – AI-generated images in 🎨 **Artist mode**  
✅ **15+ Special Chat Modes** – Talk to **Elon Musk**, a **Psychologist**, an **English Tutor**, and more!  
✅ **Customizable** – Edit `config/chat_modes.yml` to create your own chat modes  
✅ **Full API Support** – Integrate via the [ChatGPT API](https://platform.openai.com/docs/guides/chat/introduction)  
✅ **Balance Tracking** – Monitor API usage  

---

## 🆕 **Latest Updates**
📅 **April 2, 2024** – **GPT-4 Vision** support added! 👀  
📅 **November 15, 2023** – **GPT-4 Turbo** support! ⚡  
📅 **August 1, 2023** – Added OpenAI API Base config for **LocalAI**  

---

## 🔥 **Bot Commands**
- `/retry` – Regenerate last bot answer
- `/new` – Start new dialog
- `/mode` – Select chat mode
- `/balance` – Show balance
- `/settings` – Show settings
- `/help` – Show help

---

## ⚙️ **Setup Guide**
1. **Get API Keys**  
   - [OpenAI API Key](https://openai.com/api/)
   - Telegram Bot Token from [@BotFather](https://t.me/BotFather)

2. **Edit Configuration Files**  
   ```bash
   mv config/config.example.yml config/config.yml
   mv config/config.example.env config/config.env
   ```

3. **Run the Bot**  
   ```bash
   docker-compose --env-file config/config.env up --build
   ```

---

## 👥 **Contributors**
- **Main Contributor:** [@Solomon](https://t.me/Solomon)

---

## 🔗 **References**
- [*Build ChatGPT from GPT-3*](https://learnprompting.org/docs/applied_prompting/build_chatgpt)
