# 🤖 AI Appointment Agent

An end-to-end AI-powered appointment booking automation — **zero manual effort** required.

## 🚀 What It Does

✅ Collects customer details through WhatsApp chat and saves them to **Google Sheets**                                                                                                                                

✅ Sends **email confirmations** to both the customer and provider

✅ Books the **appointment in Google Calendar**

✅ Automatically sends a **reminder 2 hours before** the appointment

Everything works seamlessly from form submission to calendar sync — all powered by AI and automation.

---

## 🛠️ How to Set It Up

1. **Import the JSON** workflow into [n8n](https://n8n.io/).
2. **Configure API credentials** for Google (Calendar, Sheets, and Gmail) and Gemini/OpenAI.
3. If you're using **OpenAI**, replace the `AI Agent1 (Gemini)` node with an `OpenAI Respond to Message` node.
4. In your **Google Sheet**, open the Apps Script editor and:

   * Paste the provided script.
   * Replace the Webhook URL in the script with your n8n Webhook URL.
5. That’s it — you're all set!

---

## 📦 Tech Stack

* **n8n** (Automation Platform)
* **Google Apps Script**
* **Google Calendar API**
* **Google Sheets API**
* **Gmail API**
* **Gemini / OpenAI (for AI responses)**

---

Feel free to fork, clone, and customize the flow for your own use cases.


