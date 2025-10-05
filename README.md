# 📚 Custom ChatGPT App (Streamlit)

**🌐 Live Demo:** [https://mycustomgpt.streamlit.app/](https://mycustomgpt.streamlit.app/)

This repository contains a simple Streamlit-based ChatGPT-style app that integrates features like language detection and text-to-speech.

---

## 🧠 Features

- 💬 Chat interface powered by a GPT-like backend  
- 🌍 Automatic language detection using `langdetect`  
- 🔊 Text-to-speech support via `gtts`  
- 🧱 Simple and clean UI using Streamlit  
- ☁️ Easy deployment on Streamlit Cloud  

---

## 📁 Project Structure

.
├── chatgpt.py
├── requirements.txt
└── README.md
- `chatgpt.py` → main Streamlit app script  
- `requirements.txt` → contains required Python dependencies  
- `README.md` → project documentation  

---

## 🛠️ Setup & Installation

### 🔹 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Charishma-Guduru-123/chatgpt.git
   cd chatgpt
Create and activate a virtual environment

python3 -m venv venv
source venv/bin/activate        # (Linux / macOS)
# On Windows:
venv\Scripts\activate


Install dependencies

pip install --upgrade pip
pip install -r requirements.txt


Run the app

streamlit run chatgpt.py


Open your browser and visit http://localhost:8501 to use the app.

☁️ Deploying on Streamlit Cloud

Push your code to GitHub (make sure requirements.txt is included).

Go to Streamlit Cloud
 and create a new app.

Connect your GitHub repo (Charishma-Guduru-123/chatgpt).

Streamlit will automatically install dependencies and launch your app.

✅ Example requirements.txt
streamlit
groq
langdetect
gtts


(Add any additional packages you use, e.g. openai, requests, etc.)

🔍 How It Works (High-Level)

The user inputs text in the Streamlit interface.

The app uses langdetect to detect the language.

The text is processed by your backend or GPT-like API (e.g., Groq or OpenAI).

The output is displayed as text and optionally converted to audio using gTTS.

Streamlit renders both the text and audio response.

🧩 Troubleshooting

ModuleNotFoundError in Streamlit logs?
→ Add the missing package to requirements.txt and redeploy.

App not updating?
→ Click “Manage app” → “Rerun” or “Reboot app” on Streamlit Cloud.

Local testing
→ Always test using:

pip install -r requirements.txt
streamlit run chatgpt.py

📸 (Optional) Add Screenshots

You can include screenshots of your Streamlit UI here for better presentation:

![App Screenshot](assets/screenshot.png)

📝 License & Credits

(Add your preferred license here, e.g., MIT, Apache 2.0, etc.)

Developed by Charishma Guduru 💻
Powered by Streamlit, Groq, LangDetect, and gTTS

⭐ Don’t forget to star this repo if you found it helpful!


---

Would you like me to make a **version with badges and a screenshot section** (like GitHub-style polished README)?  
It’ll make your project page look more professional.
