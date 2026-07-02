# A.B.N.S Rishik

**B.Tech Artificial Intelligence · SRM Institute of Science and Technology, Ramapuram**
Chennai, India &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/abnsrishik) &nbsp;·&nbsp; rishikcr72401@gmail.com

---

## About

First-year AI student who builds and ships — not just learns.

I'm interested in the full stack of intelligence: how models learn from data, how language can be understood by machines, and how AI tools can solve real problems for real people. My approach is to build things early and improve them iteratively.

Open to internship opportunities in **Data Science and ML Engineering**.

---

## Projects

### 🔗 Assignment Evaluator &nbsp;·&nbsp; [Live App](https://assigneval.onrender.com)
AI-powered assignment grading system with a multi-model pipeline. Teachers create assignments and attach a rubric (written or AI-generated). Students submit PDFs or photos of handwritten work.

**How it works:**
1. **Handwritten OCR** — Llama 4 Scout (vision LLM) extracts text from handwritten pages
2. **Rubric-grounded scoring** — Llama 3.3 70B receives the student's answer + rubric verbatim, at `temperature=0` for consistency
3. **Structured output** — returns JSON: marks per question, correct content, missing content, feedback paragraph
4. **Teacher review loop** — teacher approves or overrides any score before finalised

No keyword matching. Awards marks based only on what is actually written, supporting partial credit.

`Python` `Llama 3.3 70B` `Llama 4 Scout` `Vision OCR` `Multi-model Pipeline` `Render`

---

### ⚡ FinPilot &nbsp;·&nbsp; [Live App](https://tryfinpilot.streamlit.app) &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/finpilot)
AI content pipeline for Indian finance creators. Cuts content production from 5–8 hours to ~1 minute.

**How it works:**
1. **Voice Analysis** — extracts your writing style: opening patterns, paragraph rhythm, transitions
2. **Research** — 3 targeted web searches via Tavily API, deduplicated
3. **Angle Selection** — LLM picks the best content angle from research + your voice profile
4. **Multi-format Output** — newsletter, LinkedIn post, Twitter thread, and email copy in one run

Cost: $0.02/run on Groq's free tier.

`Python` `Streamlit` `Groq API` `Llama 3.3 70B` `Tavily API` `Streamlit Cloud`

---

### 🤖 ShadowFox Internship — ML Projects &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/shadowfox)
Three end-to-end ML projects built during a structured AI/ML internship:

| Project | What it does | Stack |
|---|---|---|
| Image Classifier | CNN trained on CIFAR-10 to classify 10 image categories | TensorFlow, Keras |
| Car Price Predictor | Predicts used-car selling price from structured features | Scikit-learn, Random Forest |
| Trigram Language Model | Interpolated n-gram LM built from scratch | Python, NLP |

---

### 💪 Workout Tracker &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/workout-tracker-python)
Natural language workout logger. Type your exercise in plain English — Nutritionix NLP API calculates calories burned and duration based on your personal stats, then logs everything automatically to Google Sheets via Sheety API with date and time.

`Python` `Nutritionix API` `Sheety` `Google Sheets` `REST APIs` `NLP`

---

### 📈 Stock News Alert &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/stock-news-alert-python)
Monitors daily stock price movement and sends top 3 related news articles via WhatsApp when a stock moves more than 5%. Chains Alpha Vantage (stock data) and NewsAPI (news) together. Automated via GitHub Actions on weekdays only.

`Python` `Alpha Vantage` `NewsAPI` `Twilio` `WhatsApp` `GitHub Actions`

---

### 🌧️ Rain Alert &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/rain-alert-python)
Checks the OpenWeatherMap 5-period forecast for your location and sends a WhatsApp message if rain is expected. Runs daily at 5:00 AM IST via GitHub Actions.

`Python` `OpenWeatherMap API` `Twilio` `WhatsApp` `GitHub Actions`

---

### 🎂 Birthday Emailer &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/birthday-emailer-python)
Automated birthday emailer — reads a CSV of birthdays, checks today's date, picks a random personalised letter template, and sends an email. Runs daily via GitHub Actions cron schedule. No server needed.

`Python` `smtplib` `Pandas` `GitHub Actions` `Automation`

---

### 🔑 Password Manager &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/password-manager-python)
Desktop password manager with a built-in password generator. Saves credentials per website to JSON, supports instant search, and auto-copies generated passwords to clipboard.

`Python` `Tkinter` `JSON` `OOP` `pyperclip`

---

### ❓ Quizzler — Quiz App &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/quizzler-app-python)
True/False quiz app that fetches live questions from the Open Trivia Database API. Instant colour feedback, live score tracking, buttons disable between questions to prevent double-press.

`Python` `Tkinter` `REST API` `OOP` `html.unescape`

---

### 🃏 Flashcard Learning App &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/flashcard-app-python)
General-purpose flashcard app — load any two-column CSV and turn it into an interactive deck. Auto-flips after 3 seconds, tracks progress, resumes from remaining cards on relaunch. Works for any subject.

`Python` `Tkinter` `Pandas` `CSV` `File I/O`

---

### 🍅 Pomodoro Timer &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/pomodoro-timer-python)
Desktop Pomodoro productivity timer. Follows the 25/5/20 cycle — automatically switches between work, short break, and long break. Tracks completed sessions with ✔️ marks.

`Python` `Tkinter` `Math` `Event-driven`

---

### 🐍 Snake Game &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/snake-game-python)
Classic Snake with persistent high score across sessions. Collision resets the snake instead of ending the game — high score written to `data.txt` on every reset.

`Python` `OOP` `Turtle` `File I/O`

---

### 🐢 Turtle Crossing Game &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/turtle-crossing-game)
Frogger-inspired arcade game. Guide the turtle across a road of oncoming cars — each successful crossing increases the level and car speed.

`Python` `OOP` `Turtle` `Collision Detection`

---

### 🏓 Pong Game &nbsp;·&nbsp; [Repo](https://github.com/abnsrishik/pong-game-python)
Two-player Pong with an accelerating ball. Ball speeds up 10% on every paddle hit. Single `Paddle` class reused for both players. Live score display for both sides.

`Python` `OOP` `Turtle` `Two-player`

---

## Certifications

| Certificate | Issuer | Grade / Note | Year |
|---|---|---|---|
| Python for Data Science — **Elite** | NPTEL · IIT Madras (Govt. of India) | 75% · 23.25/25 assignments | Jan–Feb 2026 |
| AI/ML Virtual Internship — **Exceptional Performance** | ShadowFox (MSME · ISO 9001) | Completion · C.ID: SF04VIP353 | Apr 2026 |
| Getting Started with Artificial Intelligence | IBM | Completion | Feb 2026 |
| Supercharge Full-Stack Dev using AI | ShadowFox | Participation | Apr 2026 |

> NPTEL Elite certification issued by IIT Madras under the Ministry of Education, Govt. of India.

---

## Skills

| Area | Details |
|---|---|
| Languages | Python |
| ML / Deep Learning | TensorFlow, Keras, Scikit-learn |
| GUI Development | Tkinter |
| Data | Pandas, JSON, CSV, File I/O |
| APIs | REST APIs, Groq API, Tavily API, Twilio, OpenWeatherMap, Nutritionix, Alpha Vantage, NewsAPI |
| Automation | GitHub Actions, smtplib, cron scheduling |
| Core Concepts | CNNs, Regression, N-gram LMs, OOP, Event-driven programming |
| Tools | Git, GitHub, Jupyter Notebook, Render, Streamlit, pyperclip |
| Interests | Machine Learning · NLP / LLMs · Computer Vision · Data Science |

---

## Currently

- Completing 100 Days of Code — Python (Angela Yu, Udemy) · Day 35+/100
- Learning SQL for data science roles
- Shipped FinPilot — deployed AI content pipeline for finance creators
- **Actively seeking internships** in Data Science and ML Engineering

---

## Connect

📧 rishikcr72401@gmail.com &nbsp;·&nbsp; 🔗 [linkedin.com/in/abnsrishik](https://www.linkedin.com/in/abnsrishik) &nbsp;·&nbsp; 📍 Chennai, India

---

*First year. NPTEL certified. 14 projects shipped — from OOP games to deployed AI pipelines and API automations.*
