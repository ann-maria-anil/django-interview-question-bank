# Django Interview Question Bank

A Django-based web application that dynamically generates interview questions categorized by job role, difficulty level, and question type. It provides personalized role-based questions, evaluates responses, and allows users to bookmark questions for future reference.

## 🔍 Features

- 🎯 Role-specific interview questions  
- 📊 Categorization by difficulty level and question type  
- 💬 AI-generated questions using OpenAI’s GPT model  
- ✅ Real-time response evaluation  
- 📌 Bookmarking for future practice  
- 👥 Clean UI with a structured question flow

## 🧠 AI Integration

This project uses [OpenAI's GPT model](https://platform.openai.com/) via the OpenAI API to generate relevant interview questions dynamically. Based on the user's selected job role, difficulty, and question type, the backend sends prompts to the model, which responds with context-aware questions in real time.

> This makes the experience feel adaptive and personalized, mimicking real-life interview scenarios.

## 🛠️ Tech Stack

- **Backend**: Django  
- **Frontend**: HTML, CSS, Bootstrap  
- **AI**: OpenAI GPT (via API)  
- **Database**: SQLite/MySQL

## ⚙️ Setup Instructions

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/ann-maria-anil/django-interview-question-bank.git
   cd django-interview-question-bank
