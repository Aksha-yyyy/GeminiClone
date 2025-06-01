# Gemini AI Chatbot 🌐🤖

A Gemini Pro AI chatbot clone built using **HTML**, **CSS**, and **JavaScript**, powered by **Google's Gemini Pro API**. Supports Markdown, theme switching (dark/light mode), typing animation, code highlighting, and local chat history storage.

---

## 🚀 Features

- ✅ Gemini Pro API Integration (`gemini-pro`)
- 🌓 Light / Dark Theme Toggle
- 💬 Chat history stored in `localStorage`
- 🧠 Typing effect for chatbot responses
- 📄 Markdown + syntax highlighting (via `marked.js` and `highlight.js`)
- 📋 One-click copy for answers and code
- 💡 Suggested prompts
- 🗑️ Clear chat history button

---

## 🧰 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **API**: [Google Gemini Pro via Generative Language API](https://makersuite.google.com/app/apikey)
- **Markdown Parsing**: [marked.js](https://github.com/markedjs/marked)
- **Code Highlighting**: [highlight.js](https://highlightjs.org/)

---

## 🔑 Get Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/gemini-ai-chatbot.git
cd gemini-ai-chatbot
2. Set Your API Key
Get a free API key from Google AI Studio (MakerSuite).

⚠️ This API only supports gemini-pro. If your key doesn't work, it may be expired or unsupported.

In script.js, replace this line:

js
Copy
Edit
const GOOGLE_API_KEY = "YOUR_API_KEY_HERE";
const GOOGLE_API_KEY = "AIzaSy...yourKey...";
3. Open index.html in Your Browser
bash
Copy
Edit
# Just open manually or use a live server

🧪 API Error Handling
If you see any of these messages:

"API key expired" – Get a new key from MakerSuite

"models/gemini-pro is not found" – Ensure you are using the correct endpoint:

js
Copy
Edit
https://generativelanguage.googleapis.com/v1/models/gemini-pro:generateContent?key=YOUR_API_KEY
💡 Google Cloud Console API keys only work with gemini-pro-vision and embedding-gecko unless you're on Vertex AI.

📄 License
This project is open source and available under the MIT License.

🤝 Contributing
PRs and suggestions are welcome! Open an issue or submit a pull request to improve the project.
