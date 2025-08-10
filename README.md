<h1 align="center">🤖 Generative AI Chatbot with LangChain & OpenAI</h1>

<p align="center">
  <i>A hybrid AI chatbot built with Python (LangChain + OpenAI) for intelligent conversations and a responsive HTML/Tailwind CSS/JavaScript frontend.</i>
</p>

<p align="center">
  <a href="https://shreeraksha.ccbp.tech/" target="_blank">🌐 Live Demo</a> |
 
</p>

---

## 📚 About the Project

This chatbot was developed during the **Generative AI Workshop** and combines:
- **Python + LangChain + OpenAI GPT models** for backend intelligence
- **HTML + Tailwind CSS + JavaScript** for a smooth user interface
- Optional **Hugging Face Spaces** deployment for public hosting

It is capable of:
- Maintaining conversation history
- Providing contextual and relevant answers
- Integrating both rule-based and generative AI

---

## 🧠 Skills Learned

| Skill / Tool | Purpose |
|--------------|---------|
| ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) **Python** | Backend logic and AI integration |
| ![LangChain](https://img.shields.io/badge/LangChain-black?logo=chainlink&logoColor=white) **LangChain** | LLM orchestration & memory |
| ![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white) **OpenAI API** | GPT-based conversation generation |
| ![Gradio](https://img.shields.io/badge/Gradio-orange?logo=python&logoColor=white) **Gradio** | Quick prototyping of chat UI |
| ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) **HTML** | Frontend structure |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white) **Tailwind CSS** | Styling and layout |
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) **JavaScript** | UI interactions |
| ![Hugging Face](https://img.shields.io/badge/HuggingFace-yellow?logo=huggingface&logoColor=black) **Hugging Face** | Deployment platform |

---

## ✨ Features

- 💬 **Multi-turn Conversations** with memory
- 🤖 **LangChain-powered LLM** integration
- 🌐 **Responsive Web UI** with Tailwind CSS
- 📜 **OpenAI GPT-3.5-turbo** model usage
- 🚀 **Deployable on Hugging Face Spaces**
- 🔌 **Easy API key setup**

---

## 🚀 Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/yourusername/genai-chatbot.git
cd genai-chatbot
```
### 2️⃣ Install Dependencies
```bash
pip install langchain langchain-community openai gradio huggingface_hub
```
### 3️⃣ Get Your OpenAI API Key
- Go to OpenAI API Keys
- Create a New Secret Key
- Copy it and set it in your environment:

```bash
import os
os.environ["OPENAI_API_KEY"] = "your_api_key_here"
```
### 4️⃣ Run Locally
```bash
python app.py

```
Open http://127.0.0.1:5000/ or the Gradio link.

### 🌍 Deployment on Hugging Face
1. Login to Hugging Face
```bash
from huggingface_hub import notebook_login
```
2. Upload Files
```bash
from huggingface_hub import HfApi
api = HfApi()
api.upload_file(path_or_fileobj="./requirements.txt", path_in_repo="requirements.txt", repo_id="YourRepo", repo_type="space")
api.upload_file(path_or_fileobj="./app.py", path_in_repo="app.py", repo_id="YourRepo", repo_type="space")
```
3. Add Secrets in your Hugging Face Space Settings
- Go to Variables and secrets
- Add OPENAI_API_KEY

### 🔮 Future Enhancements
- 🎤 Voice-enabled conversations
- 🌍 Multi-language support
- 🗄 Persistent conversation storage
- 📊 Usage analytics

<p align="center"> Built with ❤️ using Python, LangChain, and OpenAI API </p> 









