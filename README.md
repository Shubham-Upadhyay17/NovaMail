# ✉️ NovaMail – AI-Powered Email Assistant

NovaMail is an AI-powered email assistant that helps users draft professional emails quickly using short prompts. The project is built with **Spring Boot** (backend) and designed to integrate with a **modern frontend (React/Vite)**. It supports prompt-based email generation and is easy to extend with OpenAI or any other large language model (LLM).

---

## ✨ Features

- 📨 Accepts natural language prompts to generate full emails  
- ⚡ Fast RESTful API built with Spring Boot  
- 🧠 AI-ready: Easily integratable with Gemini API or custom models  
- 🔗 Designed to connect with any frontend (e.g., React, Vite)  
- 📦 Clean, modular structure

---

## 🛠️ Tech Stack

- Java 17  
- Spring Boot  
- Maven  
- Gemini API (optional for email generation)  
- React/Vite (frontend – separate module in same repo)

---

## 📡 API Endpoints

### `POST /api/email/generate`

#### Request Body
```json
{
  "prompt": "Follow-up email after an interview"
}
```
#### Response Body
```json{
  "generatedEmail": "Dear [Recipient], I hope you're doing well. I wanted to follow up regarding our recent interview..."
}
```
---

## 💡 Use Cases
- Drafting internship/job application emails
- Writing follow-ups after meetings/interviews
- Automating standard email replies using prompts
- Creating formal business emails instantly

---
---

## 🧩 Chrome Extension

NovaMail includes a Chrome Extension that brings the power of AI-generated emails directly into your browser.

### 🔧 How it Works
- Highlight any text (e.g., a prompt like "send a thank you email").
- Click the NovaMail extension icon.
- A professional email will be generated instantly.

### 🛠️ Setup Instructions
1. Go to `NovaMail/extension/` folder (in this repo).
2. In Chrome, open `chrome://extensions/`.
3. Enable **Developer Mode**.
4. Click **Load Unpacked** and select the `extension` folder.
5. Pin the extension and start using it!

> Note: The extension connects to the running NovaMail backend. Make sure the Spring Boot server is up on `http://localhost:8080`.

---
---

## 📄 License
   This project is licensed under the MIT License.

---

🪐 “Nova” means a star that suddenly becomes brilliantly bright — just like NovaMail, which helps your communication shine.

