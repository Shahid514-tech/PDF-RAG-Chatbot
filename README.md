# 🤖 RAG Chatbot with Google Gemini API

This project is a **Retrieval-Augmented Generation (RAG) chatbot** built with **Streamlit** and powered by **Google Gemini API**.
It allows users to query documents or datasets and receive AI-powered responses with context-aware retrieval.

---

## 📌 Features

* 🔍 Document / Dataset retrieval with RAG
* 🤖 AI-powered responses using Google Gemini API
* 🎨 Interactive UI with **Streamlit**
* ☁️ Deployable on Hugging Face Spaces or locally

---

## ⚡ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup API Key

Export your **Google Gemini API Key**:

### On Linux / macOS

```bash
export GEMINI_API_KEY=your_api_key_here
```

### On Windows (CMD)

```bash
set GEMINI_API_KEY=your_api_key_here
```

### On Windows (PowerShell)

```bash
$env:GEMINI_API_KEY="your_api_key_here"
```

---

## 🚀 Run the App

```bash
streamlit run app.py
```

By default, the app runs at:
👉 [http://localhost:8501](http://localhost:8501)

On **Hugging Face Spaces**, it will run at:
👉 [https://your-space-url.hf.space](https://huggingface.co/spaces/EDITH02/PDF-RAG-Chatbot)

---

## 📂 Project Structure

```
├── app.py                # Main Streamlit app
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## 🛠️ Requirements

* Python 3.9+
* Streamlit
* Google Gemini API access
* FAISS

---

## ✨ Example Usage

Upload your documents, type a query, and let the chatbot fetch context and generate responses using Gemini.

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify.
