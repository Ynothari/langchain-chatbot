# 🧠 LangChain-Powered AI Chatbot

A fully functional, customizable chatbot powered by **LangChain**, **OpenAI GPT-4**, and **Pinecone vector database**, deployed via **Streamlit**. This chatbot allows you to ask questions based on your own documents (PDFs or text).

---

## 🚀 Features

- ✅ Conversational AI with memory  
- 📄 Document ingestion and semantic search (via Pinecone)  
- 🤖 GPT-4 or GPT-3.5-turbo for natural language understanding  
- 🧠 LangChain integration with agents and chains  
- 🌐 Simple web UI with Streamlit  
- 🔐 API key-based secure access  

---

## 🛠️ Tech Stack

| Layer         | Tools/Frameworks                         |
|---------------|------------------------------------------|
| UI            | Streamlit                               |
| Backend       | Python, LangChain                        |
| LLM           | OpenAI GPT-3.5 / GPT-4                   |
| Vector Store  | Pinecone                                 |
| Data Handling | FAISS, PyPDF, TextSplitter               |
| Deployment    | GitHub + Streamlit Cloud (Optional)      |

---

## 📂 Project Structure

```
.
├── app.py              # Streamlit main app  
├── utils.py            # Helper functions  
├── requirements.txt    # Python dependencies  
├── .env                # API keys (OpenAI, Pinecone)  
└── README.md           # Project documentation  
```

---

## 📦 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Ynothari/langchain-chatbot.git  
cd langchain-chatbot
```

---

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

- **On Windows:**
  ```bash
  venv\Scripts\activate
  ```

- **On Mac/Linux:**
  ```bash
  source venv/bin/activate
  ```

---

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Add Your API Keys

Create a `.env` file in the root directory and add:

```env
OPENAI_API_KEY=your_openai_key  
PINECONE_API_KEY=your_pinecone_key  
PINECONE_ENV=your_pinecone_env
```

---

### 5. Run the App

```bash
streamlit run app.py
```

Visit `http://localhost:8501` in your browser to start chatting with your AI assistant.

---

## 🙌 Optional: Deploy to Streamlit Cloud

1. Push your repo to GitHub  
2. Go to [streamlit.io/cloud](https://streamlit.io/cloud)  
3. Connect your GitHub repo and deploy  
4. Add your `.env` secrets in Streamlit Cloud settings  

---

## 📬 Contact

For issues or suggestions, feel free to open an issue or contact [Ynothari](https://github.com/Ynothari).
