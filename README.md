# 🌞 Daylit — Your Personal Daily Dashboard

**Daylit** is a minimalist personal dashboard built with Flask.  
Stay emotionally aware, focused, and organized — all in one place.

Track your **mood**, manage **to-dos**, check the **weather**, and get inspired with a **daily quote** — in a calm, clean interface.

---

## ✨ Features

- 🌤️ Real-time weather updates  
- ✅ Daily to-do list  
- 🧠 Mood tracker with emoji + reflection  
- 🧘 Daily inspirational quote  
- 💾 SQLite database for local data  
- 🎨 Responsive UI with Bootstrap or Tailwind

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/Le0wang06/daylit.git
cd daylit
```

### 2. (Optional) Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the App
```bash
flask run
```

Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 📁 Project Structure

```
daylit/
├── static/             # CSS, JS, images
├── templates/          # HTML templates
│   ├── layout.html
│   ├── index.html
│   └── dashboard.html
├── app.py              # Main Flask app
├── config.py           # API keys & config
├── utils.py            # Helper functions
├── requirements.txt
└── README.md
```

---

## 🔮 Future Ideas

- 📈 Mood history & analytics  
- 🌓 Dark mode toggle  
- 🔔 Daily reminders (PWA notifications)  
- 📥 Export moods or tasks as PDF  
- 🤖 AI-assisted journaling (GPT)

---

## 🛠️ Tech Stack

- Python + Flask  
- SQLite  
- HTML/CSS (Bootstrap or Tailwind)  
- OpenWeather API  
- Quotes API

---

## 📄 License

MIT License • Feel free to fork and build on it.

---

## 👤 Author

Built with ☕ and clarity by [@yourusername](https://github.com/yourusername)
