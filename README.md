# 🤖 Gemini ChatBot | Streamlit + Google Gemini API

<img width="1900" height="891" alt="image" src="https://github.com/user-attachments/assets/dab8d909-8630-487c-96a1-264ef19c04ac" />


A conversational chatbot built using **Google's Gemini 1.5 Flash** model and deployed using **Streamlit**. This chatbot retains chat history during a session and can be used for general Q&A or AI-powered assistance.

----

## 🚀 Features

- Chat with Google's Gemini (1.5 Flash) via API
- Streamlit-based interactive interface
- Maintains conversation memory
- Button to clear chat history
- Environment variable handling via `.env` file

---

## 🖥️ Tech Stack

- [Streamlit](https://streamlit.io/) – For frontend UI
- [Google Generative AI SDK](https://ai.google.dev/) – To connect with Gemini
- [Python Dotenv](https://pypi.org/project/python-dotenv/) – For secure API key handling

---

## 🔧 Setup Instructions

### 1. Clone the Repository

### 2. Create Virtual Environment (optional but recommended)
python -m venv .venv
source .venv/bin/activate       # On Linux/Mac
.venv\Scripts\activate          # On Windows

### 3. Install Dependencies
pip install -r requirements.txt

### 4. Add Your Gemini API Key
GOOGLE-API-KEY=your_actual_api_key_here

### 5. Run The App
streamlit run app.py

## File Structure
gemini-chatbot/
│
├── app.py                # Main Streamlit application
├── .env                  # Stores API key (excluded from Git)
├── requirements.txt      # Required Python packages
└── README.md             # Project documentation

