# 🌐 AI Translator: English to Hindi & Telugu Using Streamlit, n8n & Gemini AI

## 📌 Project Overview
AI Translator is a **multilingual translation application** that translates English text into **Hindi** and **Telugu** using **Google Gemini AI**, integrated with **Streamlit** for a user-friendly interface and **n8n** for workflow automation.  
This project is designed for users seeking **real-time, AI-powered translations** with **easy deployment** and **interactive features**.

---

## 🎯 Objectives
- Translate English text to Hindi and Telugu accurately  
- Provide a **real-time, interactive interface** using Streamlit  
- Automate workflow and API calls using n8n  
- Leverage Google Gemini AI for advanced natural language understanding  

---

## 🛠 Technologies Used
- **Programming Language:** Python  
- **Libraries & Tools:** Streamlit, Requests / HTTP client, n8n Automation Platform  
- **AI Engine:** Google Gemini AI  
- **Development Environment:** VS Code / Jupyter Notebook  

---

## 🔍 Project Workflow
1. **User Input:** English text entered in the Streamlit interface  
2. **Workflow Trigger:** n8n captures the input and sends it to the AI model  
3. **AI Translation:** Google Gemini AI generates translated text in Hindi or Telugu  
4. **Display Output:** Streamlit displays the translated text  
5. **Optional Logging:** Save translations for review or analysis  

---

## 🚀 Features
- Real-time translation from English → Hindi / Telugu  
- Interactive web interface with Streamlit  
- Fully automated workflow using n8n  
- Powered by **Google Gemini AI** for accurate translation  
- User-friendly and suitable for multilingual communication  

---

## 🔧 Setup Instructions

### 1️⃣ Install Dependencies
```bash
pip install streamlit requests
````

### 2️⃣ Run n8n

```bash
n8n
```

* Import workflow JSON file for automation

### 3️⃣ Run Streamlit App

```bash
streamlit run app.py
```

### 4️⃣ Enter Text

* Open the browser interface
* Enter English text and select target language (Hindi / Telugu)
* Click Translate → Output appears instantly

---

## 🧩 How It Works Internally

1. Streamlit captures user input
2. n8n workflow sends request to Google Gemini AI
3. AI model translates text to selected language
4. Translated text returned to Streamlit interface
5. Optional: Store translation in logs or CSV

---

## 🎯 Use Cases

* Multilingual education platforms
* Real-time translation assistants
* Support for businesses interacting with Hindi/Telugu speaking clients
* AI-powered personal translators

```
