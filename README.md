# 🤖 Automated Gmail AI Reply Draft Generator (n8n + Google Gemini)

An automated AI workflow built on **n8n** that monitors unread emails in Gmail, generates context-aware draft replies using **Google Gemini AI**, and includes an active **Error Handling & Notification System**.

---

## 🌟 Key Features

* **Automatic Email Polling:** Periodically checks Gmail for new unread incoming messages.
* **Smart AI Drafting:** Leverages Google Gemini to analyze email context and write professional draft responses automatically.
* **Safe Human-in-the-Loop:** Saves replies strictly as **Drafts** in Gmail, ensuring total control before sending.
* **Robust Error Handling:** Separate automated error workflow that instantly sends alert notifications if any step fails.
* **Email Parsing & Sanitization:** Dynamically extracts clean email addresses using `.extractEmail()` logic to prevent delivery failures.

---

## 🛠️ Tech Stack & Tools

* **Automation Engine:** n8n Cloud
* **AI Model:** Google Gemini API
* **Integration:** Gmail OAuth2 API
* **Data Format:** JSON, REST APIs, Webhooks

---

## 🚀 How to Import and Use

1. Clone or download this repository.
2. Open your **n8n** workspace.
3. Create a new workflow, click the top-right menu, and select **Import from File**.
4. Choose the `gmail ai reply.json` or `error handler.json` file.
5. Connect your own **Gmail OAuth2** and **Google Gemini API** credentials.
6. Activate/Publish the workflow.
