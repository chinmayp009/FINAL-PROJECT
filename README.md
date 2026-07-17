# FINAL-PROJECT

# 🌍 AI Travel Planner Chatbot

An AI-powered travel assistant that helps users plan trips by answering travel-related questions, suggesting destinations, creating itineraries, providing travel tips, and recommending places to visit based on user preferences.

---

## 📌 Features

- 💬 Interactive AI chatbot interface
- 🗺️ Destination recommendations
- 📅 Personalized travel itinerary generation
- 💰 Budget-friendly travel suggestions
- 🌦️ Travel tips and essential information
- 🏨 Hotel and accommodation suggestions (optional)
- 🍽️ Restaurant recommendations (optional)
- ✈️ Transportation guidance
- 📱 Simple and user-friendly interface

---

## 🛠️ Technologies Used

- Python
- Streamlit
- Google Gemini API
- HTML/CSS (for UI customization)
- dotenv (Environment Variables)

---

## 📂 Project Structure

```
AI-Travel-Planner/
│
├── app.py                 # Main application
├── requirements.txt       # Project dependencies
├── .env                   # API key (Not uploaded to GitHub)
├── README.md
├── chatbot
    ├── __init__.py
    ├── ai.py
    ├── prompts.py
├── static
    ├── script.js
    ├── style.css
├── templates
    ├── index.html
└── venv
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Travel-Planner.git
```

### 2. Navigate to the project

```bash
cd AI-Travel-Planner
```

### 3. Create a virtual environment (Optional)

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / Mac

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

Create a `.env` file in the project folder.

Add:

```env
GOOGLE_API_KEY=YOUR_GEMINI_API_KEY
```

Replace `YOUR_GEMINI_API_KEY` with your actual API key.

---

## ▶️ Running the Project

Run the following command:

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 💡 Example Questions

- Plan a 5-day trip to Goa.
- Best places to visit in Japan.
- Suggest a budget trip under ₹25,000.
- What should I pack for Ladakh?
- Create a honeymoon itinerary for Bali.
- Best time to visit Switzerland.
- Family trip to Kerala for 4 days.

---

## 📸 Screenshots

Add screenshots of your chatbot here.

Example:

```
screenshots/
    home.png
    chat.png
```

---

## 🚀 Future Improvements

- User authentication
- Save travel history
- PDF itinerary download
- Flight search integration
- Hotel booking integration
- Google Maps integration
- Weather forecast support
- Voice interaction
- Multi-language support

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push to your branch
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Chinmay Patil**

Cybersecurity Student | AI & Python Enthusiast

GitHub: https://github.com/yourusername
