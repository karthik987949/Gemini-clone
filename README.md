# 🤖 Gemini Clone Chatbot 

A simple **Gemini Clone chatbot** built with **Streamlit** and the **Google Generative Language API (Gemini 1.5 Flash)**.  
This web app allows users to have interactive conversations with an AI model directly in the browser.

---

## 🚀 Features
- **Interactive Chat UI** built with Streamlit's `chat_message` and `chat_input`.
- **Session Memory**: Stores previous conversation context using `st.session_state`.
- **Google Gemini API Integration** for generating AI responses.
- **Error Handling**: Displays API and network errors clearly for debugging.

---

## 🛠️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/gemini-clone-chatbot.git
cd gemini-clone-chatbot
```

### 2. Install Dependencies
Make sure you have Python 3.8+ installed.
```bash
pip install streamlit requests
```

### 3. Set Your API Key
In the `chatbot.py` file, replace:
```python
api_key = "YOUR_API_KEY"
```
with your actual **Google Gemini API key**.  
You can get your API key from [Google AI Studio](https://makersuite.google.com/).

> **Security Tip:** Use environment variables or a `.env` file instead of hardcoding your API key for production.

### 4. Run the App
```bash
streamlit run chatbot.py
```

Then open your browser and go to:
```
http://localhost:8501
```

---

## 📂 Project Structure
```
├── chatbot.py    # Main application file
├── README.md     # Project documentation
```

---

## 🖼️ Screenshot
(Add a screenshot of your app here)


---

## ⚠️ Notes & Improvements
- Use **environment variables** to securely store your API key.
- Deploy on **Streamlit Cloud**, **Heroku**, or **Render** for easy hosting.
- Add **voice input/output** and **multi-turn conversation support** for enhancements.

---


## 👨‍💻 Author
Developed by **[Sai Karthik](https://github.com/your-username](https://github.com/karthik987949))**  
Contributions, issues, and feature requests are welcome!
