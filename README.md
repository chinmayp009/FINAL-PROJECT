# 🤖 AI Customer Support Bot

An AI-powered customer support chatbot built using **Python**, **Streamlit**, and the **Google Gemini API**. The chatbot provides instant responses to customer queries, helping businesses automate customer support and improve user experience.

---

## 📌 Features

- 💬 AI-powered conversational chatbot
- ⚡ Instant customer support responses
- 🧠 Natural language understanding using Google Gemini
- 📄 Answers based on company documents or FAQs (if provided)
- 🎨 Clean and user-friendly Streamlit interface
- 🔒 Secure API key management using `.env`
- 📱 Responsive web application

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini API
- python-dotenv
- HTML/CSS (optional UI customization)

---

## 📂 Project Structure

```
AI-Customer-Support-Bot/
│
├── app.py                 # Main Streamlit application
├── requirements.txt       # Project dependencies
├── .env                   # Stores API key (not uploaded to GitHub)
├── README.md
├── data/                  # Company FAQs or documents (optional)
└── assets/                # Images and icons (optional)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Customer-Support-Bot.git
```

### 2. Navigate to the project folder

```bash
cd AI-Customer-Support-Bot
```

### 3. Create a virtual environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 API Key Setup

Create a `.env` file in the project directory.

```env
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

Replace `YOUR_GEMINI_API_KEY` with your own Gemini API key.

---

## ▶️ Running the Project

Start the application with:

```bash
streamlit run app.py
```

Then open the local URL displayed in your terminal (usually `http://localhost:8501`).

---

## 💬 Example Questions

- What are your business hours?
- How can I track my order?
- What is your refund policy?
- How do I reset my password?
- Do you offer international shipping?
- How can I contact customer support?
- What payment methods do you accept?

---


## 🚀 Future Improvements

- User authentication
- Conversation history
- Multi-language support
- Voice-based interaction
- Sentiment analysis
- Live chat handoff to human agents
- Database integration
- FAQ management dashboard
- Email support integration
- Analytics and reporting

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes.
4. Push the branch.
5. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Chinmay Patil**

- GitHub: https://github.com/chinmayp009/FINAL-PROJECT
