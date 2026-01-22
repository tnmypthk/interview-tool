# 🎯 Interview Tool — AI-Assisted Interview Practice

An **AI-powered interview preparation tool** built with **Python and Streamlit** that helps users practice interview questions interactively and receive structured responses in real time.
The application is designed as a **lightweight applied AI system**, focusing on user interaction, prompt orchestration, and deployment.

---

## 🚀 Overview

This project provides an interactive interview-practice experience where users can:

* Simulate interview questions
* Practice structured responses
* Use an AI-powered backend to guide and evaluate answers
* Access the tool via a simple web interface built with Streamlit

The goal of this project is to demonstrate **applied AI engineering**, including:

* LLM orchestration
* Interactive UI development
* End-to-end deployment of an AI application

---

## ✨ Features

* 🧠 **AI-assisted interview questions**
* 💬 **Interactive Streamlit UI** for real-time practice
* ⚡ **Fast iteration & response handling**
* 🌐 **Deployed web application** (Streamlit-based)
* 🧩 Modular Python codebase for easy extension

---

## 🛠️ Tech Stack

* **Language:** Python
* **UI Framework:** Streamlit
* **AI / NLP:** LLM-based prompt orchestration
* **Environment:** Virtualenv / Dev Containers
* **Deployment:** Streamlit Cloud
* **Configuration:** `.streamlit`, `requirements.txt`

---

## 🏗️ Architecture (High-Level)

```
User
  ↓
Streamlit UI
  ↓
Prompt / Interview Logic
  ↓
LLM Response Generation
  ↓
Formatted Output to UI
```

This architecture keeps the UI, logic, and AI interaction **loosely coupled**, making it easy to:

* Add scoring or feedback
* Plug in vector search (RAG)
* Extend to agentic workflows

---

## 🧪 How to Run Locally

### 1️⃣ Clone the repository

```bash
git clone https://github.com/tnmypthk/interview-tool.git
cd interview-tool
```

### 2️⃣ Create and activate virtual environment

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Streamlit app

```bash
streamlit run app.py
```

The application will be available at:

```
http://localhost:8501
```

---

## 🌍 Deployment

The application is deployed using **Streamlit**, enabling fast iteration and easy access without complex infrastructure setup.

*(Add deployed app URL here if public)*

---

## 📌 Use Cases

* Interview preparation for technical and behavioral interviews
* AI-assisted self-evaluation and practice
* Demonstration of applied AI + UI integration
* Foundation for future agentic AI workflows

---

## 🔮 Future Enhancements

Planned improvements include:

* ✅ Answer evaluation and scoring
* ✅ Agentic interview flow using LangGraph
* ✅ Retrieval-Augmented Generation (RAG) for domain-specific interviews
* ✅ Interview session history and analytics
* ✅ API-based backend using FastAPI

---

## 📚 Learning Objectives

This project was built to strengthen skills in:

* Applied AI engineering
* LLM prompt orchestration
* Streamlit application development
* End-to-end AI system deployment

---

## 👤 Author

**Tanmay Pathak**
Senior Integration Engineer transitioning into **AI Engineering & Applied AI Systems**

* GitHub: [https://github.com/tnmypthk](https://github.com/tnmypthk)
* LinkedIn: [https://linkedin.com/in/tanmay-pathak-64579883](https://linkedin.com/in/tanmay-pathak-64579883)
