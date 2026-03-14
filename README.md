# 🌟 Sentiment Analysis Web Application

[![Contributors](https://img.shields.io/github/contributors/Gotam-Dulhani/Sentiment-Analysis)](https://github.com/Gotam-Dulhani/Sentiment-Analysis/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/Gotam-Dulhani/Sentiment-Analysis)](https://github.com/Gotam-Dulhani/Sentiment-Analysis/network/members)
[![Stars](https://img.shields.io/github/stars/Gotam-Dulhani/Sentiment-Analysis)](https://github.com/Gotam-Dulhani/Sentiment-Analysis/stargazers)
[![Issues](https://img.shields.io/github/issues/Gotam-Dulhani/Sentiment-Analysis)](https://github.com/Gotam-Dulhani/Sentiment-Analysis/issues)
[![License](https://img.shields.io/github/license/Gotam-Dulhani/Sentiment-Analysis)](https://github.com/Gotam-Dulhani/Sentiment-Analysis/blob/main/LICENSE)

> A **full-stack Sentiment Analysis Web Application** with an interactive dashboard that classifies text as **Positive**, **Negative**, or **Neutral** in real-time.

🌐 **Explore the docs »**
🚀 **[View Demo](#)** · 🐛 **Report Bug** · 🌟 **Request Feature**

---

## 📌 Table of Contents

* [About The Project](#about-the-project)
* [Key Features](#key-features)
* [Built With](#built-with)
* [Getting Started](#getting-started)
* [Installation](#installation)
* [Usage](#usage)
* [System Architecture](#system-architecture)
* [Contributing](#contributing)
* [Contributors](#contributors)
* [License](#license)
* [Contact](#contact)
* [Acknowledgments](#acknowledgments)

---

## 💡 About The Project

The **Sentiment Analysis Web Application** allows users to analyze the emotional tone of any text using **Natural Language Processing (NLP)**.

Users can paste **reviews, feedback, or social media posts** and instantly get:

* Sentiment category
* Compound polarity score
* Visual distribution via interactive charts

**Technologies showcased in this project:**

* NLP and Machine Learning
* REST API backend with FastAPI
* Interactive frontend dashboards with React & Recharts
* Real-time sentiment scoring

---

## ✨ Key Features

* **Real-Time Analysis** – Instantly classify text sentiment.
* **Interactive Charts** – Pie/Donut visualizations of Positive, Neutral, Negative distributions.
* **Modern UI** – Glassmorphism design, responsive layout, smooth animations.
* **Fast Backend** – Powered by **FastAPI** and asynchronous Python processing.
* **Error Handling** – Handles empty inputs or API failures gracefully.
* **Scalable Architecture** – Modular, easy to expand with advanced ML models.

---

## 🛠 Built With

### Backend

* Python 3.8+
* FastAPI
* NLTK (VADER Sentiment Analyzer)
* Uvicorn
* Pydantic

### Frontend

* React
* Vite
* Axios
* Recharts
* Framer Motion
* Lucide React Icons
* Custom CSS

---

## 🚀 Getting Started

### Prerequisites

* Python 3.8+
* Node.js & npm
* Git

---

## 💾 Installation

### Clone the Repository

```bash
git clone https://github.com/Gotam-Dulhani/Sentiment-Analysis.git
cd Sentiment-Analysis
```

### Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

Backend runs at: `http://127.0.0.1:8000`

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at: `http://localhost:5173`

---

## 📝 Usage

1. Open the frontend application in your browser.
2. Enter or paste text into the input box.
3. Click **Analyze**.
4. View the sentiment results & interactive charts.

**Example Input:**

```text
This product is amazing! I love the quality and the design.
```

**Example Output:**

```text
Sentiment: Positive
Compound Score: 0.82
Positive: 0.78
Neutral: 0.22
Negative: 0.00
```

---

## 🏗 System Architecture

```
User Input (React UI)
        │
        ▼
Axios HTTP Request
        │
        ▼
FastAPI Backend
        │
        ▼
NLTK VADER Sentiment Analyzer
        │
        ▼
JSON Response
        │
        ▼
React Dashboard + Charts
```

### Sentiment Classification Logic

| Compound Score | Sentiment |
| -------------- | --------- |
| ≥ 0.05         | Positive  |
| ≤ -0.05        | Negative  |
| -0.05 to 0.05  | Neutral   |

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a feature branch:

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes:

```bash
git commit -m "Add AmazingFeature"
```

4. Push to the branch:

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

---

## 👤 Contributors

**Gotam Dulhani** – Project Development & Implementation

---

## 📝 License

Distributed under the **MIT License**. See `LICENSE` for details.

---

## 📫 Contact

Gotam Dulhani
GitHub: [https://github.com/Gotam-Dulhani/Sentiment-Analysis](https://github.com/Gotam-Dulhani/Sentiment-Analysis)

---

## 🙏 Acknowledgments

* NLTK Natural Language Toolkit
* FastAPI Documentation
* React Documentation
* Recharts Visualization Library
* Open Source Community
