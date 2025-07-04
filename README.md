# 🤖 Gemini Q&A NLP Demo

A simple yet powerful Natural Language Processing (NLP) application built using Google's Gemini Pro (`gemini-1.5-flash`) and Streamlit.  
This project allows users to ask natural language questions and get real-time AI-generated answers from Gemini.  
It was developed as part of a hands-on workshop on building intelligent web apps using large language models (LLMs).

---

## ⚙️ Tech Stack

- 🐍 Python 3.8+
- 📚 [Streamlit](https://streamlit.io/) – UI framework for Python
- 🤖 [Google Generative AI (Gemini)](https://makersuite.google.com/) – LLM for question-answering
- 🔐 [python-dotenv](https://pypi.org/project/python-dotenv/) – Secure handling of environment variables

---

## 🚀 Getting Started

### 🔑 Prerequisites

- Python installed locally (`python --3.8`)
- A Google Generative AI API key from [Google AI Studio](https://makersuite.google.com/)

### 📦 Setup Instructions

1. **Clone the repository**

   git clone https://github.com/AishwaryaM-10/Question_Answering_AI.git
   
   cd Question_Answering_AI

3. **Create and activate a virtual environment (optional but recommended)**
   python -m venv venv
   On Windows
   venv\Scripts\activate
   On macOS/Linux
   source venv/bin/activate

4. **Install dependencies**

   pip install -r requirements.txt

6. **Create a .env file and add your API key**

   GOOGLE_API_KEY=your_google_api_key_here

8. **Run the app**
   
   streamlit run app.py


