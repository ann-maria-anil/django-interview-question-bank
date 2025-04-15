# Django Interview Question Bank

A Django-based web application that dynamically generates interview questions categorized by job role, difficulty level, and question type. It provides personalized role-based questions, evaluates responses, and allows users to bookmark questions for future reference.


## 🔍 Features

- 🎯 Role-specific interview questions  
- 📊 Categorization by difficulty level and question type  
- 💬 AI-generated questions using OpenAI’s GPT model  
- ✅ Real-time response evaluation  
- 📌 Bookmarking for future practice  
- 👥 Clean UI with a structured question flow


## 📚 Additional Resources

This repository includes various additional resources to help you understand and customize the project:

- 📝 **Synopsis**: A brief overview of the project, how it works, and its purpose.

- 🗃️ **Database Design**: Detailed explanations about the database schema, models, and how the data is structured for interview questions and user interactions.

- 🎨 **UI Design Details**: A comprehensive breakdown of the front-end layout, including wireframes, styles used, and the design principles applied.

- 📋 **Project Plan**: A step-by-step outline of the project timeline, major milestones, and how the development progressed from concept to completion.

- 🎥 **Video Explanation with Voice-Over**: A full video walkthrough with voice-over explanation, showing how the front-end of the project works. This includes a demonstration of the user interface, interaction flow, and overall design with a detailed voice-over for better understanding.

These resources will help you understand the **architecture** and **functionality** of the application in-depth, allowing you to **customize, expand, or contribute** to the project more effectively.



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
