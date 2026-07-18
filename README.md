from pathlib import Path
from textwrap import dedent

content = dedent("""
# Muqaddas Yamin

**Artificial Intelligence Student | AI & Machine Learning Enthusiast | Python Developer | AI Application Developer**

📍 Multan, Punjab, Pakistan

---

## 👩‍💻 About

I am Muqaddas Yamin, a Bachelor of Science in Artificial Intelligence student at **Bahauddin Zakariya University (BZU)**. I am passionate about designing intelligent systems that solve real-world problems through Artificial Intelligence and software development.

My interests include Machine Learning, Deep Learning, Natural Language Processing, Large Language Models (LLMs), AI-powered applications, Python development, and modern web technologies. I enjoy turning ideas into practical solutions by building AI chatbots, voice-enabled applications, intelligent assistants, and responsive web applications.

I believe in continuous learning, hands-on development, and creating projects that strengthen both my technical knowledge and problem-solving abilities. My goal is to become an AI Engineer who develops innovative AI solutions with real-world impact.

---

## 🎓 Education

### Bahauddin Zakariya University (2025–2029)
**Bachelor of Science in Artificial Intelligence**

### Muslim College (2023–2025)
**Intermediate (ICS – Computer Science)**

### Muslim Group of Schools & Colleges (2020–2023)
**FSc (Pre-Medical)**

---

## 🚀 Projects

- **CASPAM-Bot** — AI-powered university assistant with voice, image, and document understanding.
- **AI Voice Summarizer** — Speech-to-text and AI summarization application.
- **AI Study Assistant** — Intelligent assistant for academic support and document-based learning.
- **Neural Insight Portfolio** — AI-themed personal portfolio website.
- **Friends Traders Website** — Responsive business website.
- **Object-Oriented Racing Game** — C++ OOP game demonstrating core OOP concepts.
- **Electricity Bill Management System** — C++ billing application with file handling.
- **DreamHome Database System** — SQL database project with relationships and normalization.

---

## 💻 Technical Skills

### Artificial Intelligence
- Machine Learning
- Deep Learning
- Generative AI
- Large Language Models (LLMs)
- Natural Language Processing (NLP)
- AI Chatbots

### Programming
- Python
- C++
- JavaScript
- HTML5
- CSS3
- SQL

### Frameworks & APIs
- Flask
- Hugging Face
- OpenAI API
- Groq API
- Gemini API
- Claude API
- Mistral API

### Databases
- SQL
- MySQL
- Database Design
- Database Management Systems

### Tools
- Git
- GitHub
- VS Code
- PyCharm
- IntelliJ IDEA
- Render
- Replit
- Microsoft Excel
- Power BI

### Soft Skills
- Problem Solving
- Critical Thinking
- Communication
- Leadership
- Teamwork
- Time Management
- Continuous Learning

---

## 🌱 Currently Learning

- Advanced Artificial Intelligence
- Machine Learning
- Deep Learning
- Large Language Models
- Database Systems
- Flask Development
- Git & GitHub
- Power BI

---

## 🎯 Career Objective

I aspire to build intelligent AI systems that solve practical problems through machine learning, natural language processing, and software engineering. My objective is to continuously strengthen my technical expertise while contributing to innovative AI research and real-world applications.

---

## 📫 Connect

- LinkedIn
- GitHub
- Email
""")

path="/mnt/data/Updated_GitHub_README.md"
Path(path).write_text(content,encoding="utf-8")
print(path)
