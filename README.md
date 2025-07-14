# README for AI Hiring Assistant

## 📌 Project Overview
An AI-powered hiring assistant chatbot built using **Gemini Pro API** and **Streamlit**. It collects candidate details, generates tailored technical questions based on the provided tech stack, and maintains an interactive conversation flow.

---

## 🚀 Features
- Candidate information collection
- Tech-stack-specific technical question generation
- State-managed conversation handling
- Exit detection and graceful conversation termination
- Fallback for unstructured inputs

---

## 🛠️ Installation Instructions
```bash
# Clone the repository
git clone <repo-link>
cd <project-folder>

# Install dependencies
pip install streamlit google-generativeai

# Run the app
streamlit run app.py
```

---

## 🧩 Usage Guide
1. Start the chatbot.
2. Provide your personal details and tech stack.
3. Receive tailored technical questions.
4. Type `exit`, `quit`, or `bye` to end.

---

## 🔍 Technical Details
- **Language:** Python
- **Frontend:** Streamlit
- **LLM:** Gemini 1.5 Pro API
- **State Management:** Streamlit session state

---

## 🧵 Prompt Design
- **Candidate Info Prompt:** Extracts structured JSON data.
- **Question Generation Prompt:** Creates 3-5 questions per tech.

---

## ⚙️ Deployment Guide
### Cloud (GCP Example)
1. Set up a **Google Cloud VM instance**.
2. Install Python and dependencies.
3. Clone the repo.
4. Run using `nohup streamlit run app.py &` for persistent background execution.
5. Open firewall port (default 8501) to allow public access.

Alternatively, deploy via **Streamlit Community Cloud** for quick demos.

---

## 🌐 Multilingual Support (Enhancement)
Integrate **Google Translate API** to translate:
1. User input to English.
2. AI responses back to the user's language.

This allows dynamic support for any language.

---

## 📌 Optional Enhancements
- Sentiment analysis via Huggingface APIs.
- Data storage using SQLite, Firebase, or AWS DynamoDB.
- Admin dashboard using Streamlit or a Flask-based web app.

---

## 🏁 Conclusion
This project is scalable for real-world recruitment applications, offering customization and cloud deployment for professional use.

---

For queries or contributions, contact: **sourabhsinghal22122002@gmail.com**
