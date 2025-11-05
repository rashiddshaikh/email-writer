# ✉️ AI Email Writer

Smart email drafting tool powered by Spring Boot, Google Gemini API, and a Material-UI React frontend.  
Generate professional emails based on tone, context, and purpose — instantly.

---

## 🚀 Features

- 🧠 AI-Generated Email Content (Google Gemini)
- 🎨 Modern UI built with Material-UI
- 🔄 Real-time editing response using MutationObserver
- 🌐 Axios-based API communication
- ⚡ Fast Spring Boot backend with clean REST endpoints
- 📦 Extendable templates and tone selection

---

## 🖥️ Tech Stack

| Layer | Technology |
|------|------------|
| Backend | Java, Spring Boot |
| AI Model | Google Gemini API |
| Frontend | React + Material-UI |
| HTTP Client | Axios |
| DOM Listener | MutationObserver |
| Build Tools | Maven / npm / yarn |

---

## 🧪 Setup & Development

### 1. Clone the repository
```bash
git clone https://github.com/rashiddshaikh/email-writer.git
cd email-writer
```
### 2. Backend Setup (Spring Boot in Eclipse)

1. Open Eclipse and import the backend folder as a Maven Project.
2. Go to:
```bash
Run → Run Configurations → Environment → Add
```
3. Add the required environment variables:

| Name        | Value                                                                 |
|------------|-----------------------------------------------------------------------|
| GEMINI_URL  | https://generativelanguage.googleapis.com/v1/models/gemini-pro:generateContent |
| GEMINI_KEY  | your_google_gemini_api_key                                            |
| SERVER_PORT | 8080                                                                   |

4. Click Apply ✅ and Run ▶️ the Spring Boot Application.
No need to hardcode keys in application.properties.

### 3. Frontend Setup (VS Code)
```bash
cd frontend
npm install
```
Run the frontend:
```bash
npm start
```

## 4. Chrome Extension Setup

### 1. Open the Extension Folder
The Chrome extension code is located in: email-writer-ext/
 
### 2. Load Extension in Chrome
1. Open Chrome and go to: chrome://extensions/
2. Enable **Developer Mode** (top-right toggle).
3. Click **Load unpacked**.
4. Select the folder: email-writer-ext/

### 3. Pin the Extension
Click the puzzle icon (🔧) → Pin **Email Writer Assistant** to the toolbar.

### 4. Make Sure Backend is Running
Launch **Spring Boot backend** in Eclipse:

### 5. Use the Extension
1. Open **Gmail**
2. Click **Compose** or **Reply**
3. A new **AI Reply** button will appear inside the compose toolbar
4. Click it → The email will be generated automatically 🎉
---
🎯 Usage Flow

- Enter email purpose / tone / context
- Frontend sends request → Backend
- Backend calls Google Gemini API
- Generated email returned to editor
- User edits, copies, or saves the final result

---
![GitHub Repo stars](https://img.shields.io/github/stars/rashiddshaikh/email-writer)
![GitHub forks](https://img.shields.io/github/forks/rashiddshaikh/email-writer)
![GitHub issues](https://img.shields.io/github/issues/rashiddshaikh/email-writer)
![GitHub last commit](https://img.shields.io/github/last-commit/rashiddshaikh/email-writer)

---
## 📄 License  
This project is licensed under the MIT License.

---

## ✍️ Author  
**Rashid Shaikh**  
🔗 GitHub: [@rashiddshaikh](https://github.com/rashiddshaikh)  
🔗 LinkedIn: [https://linkedin.com/in/rashidshaikh-dev](https://linkedin.com/in/rashidshaikh-dev)  
📧 Email: [rashidshaikh.dev@gmail.com](mailto:rashidshaikh.dev@gmail.com)

---
## 🌟 Contributing  
Pull requests are welcome!  
For major changes, please [open an issue first](https://github.com/rashiddshaikh/email-writer/issues).

---
## 🙏 Acknowledgments

- [Google Gemini API](https://ai.google.dev/) for powering intelligent email generation  
- [Material-UI](https://mui.com/) for clean and accessible UI components  
- The open-source community ❤️ for continuous inspiration and contributions




