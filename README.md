# 📚 Information Retrieval using LlamaIndex + Google Gemini

An intelligent **Retrieval-Augmented Generation (RAG)** system that allows users to query documents and retrieve accurate answers using **Google Gemini LLM** combined with **LlamaIndex document indexing**.

The system processes PDF documents, builds a searchable knowledge index, retrieves relevant context, and generates answers through an **interactive Streamlit interface**.

---

# 🚀 Features

- 📄 PDF document ingestion and indexing
- 🔎 Semantic search using LlamaIndex
- 🤖 Question answering powered by Google Gemini
- 🧠 Retrieval-Augmented Generation (RAG) pipeline
- 🖥️ Interactive Streamlit user interface
- 📝 Logging and custom exception handling
- 📦 Modular Python project architecture

---

# 🧠 How the System Works

The application follows a **Retrieval-Augmented Generation pipeline**:

```
User Query
    │
    ▼
Streamlit Interface
    │
    ▼
LlamaIndex Retrieval Engine
    │
    ▼
Relevant Document Chunks
    │
    ▼
Google Gemini LLM
    │
    ▼
Generated Answer
```

---

# 📂 Project Structure

```
Information-Retrieval-using-LlamaIndex-Google-Gemini
│
├── Experiments/                # Experimental notebooks
├── QAWith/                     # Core QA system
├── QAWithPDF/                  # PDF-based retrieval system
├── notebook/                   # Jupyter notebook experiments
├── data/                       # Document dataset
├── logs/                       # Application logs
│
├── StreamlitApp.py             # Streamlit UI application
├── logger.py                   # Logging utility
├── exception.py                # Custom exception handling
├── requirements.txt            # Project dependencies
│
└── README.md
```

---

# 🛠️ Technologies Used

| Component | Technology |
|----------|-----------|
| LLM | Google Gemini |
| Retrieval Framework | LlamaIndex |
| Interface | Streamlit |
| Programming Language | Python |
| Document Source | PDF |

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Information-Retrieval-using-LlamaIndex-Google-Gemini.git
cd Information-Retrieval-using-LlamaIndex-Google-Gemini
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Setup Environment Variables

Create a `.env` file in the root directory and add your **Google Gemini API key**:

```
GOOGLE_API_KEY=your_api_key_here
```

---

# ▶️ Running the Application

Start the Streamlit app:

```bash
streamlit run StreamlitApp.py
```

After running the command, the application will open automatically in your browser.

---

# 💬 Example Queries

Example questions users can ask:

- "Summarize the document"
- "What are the key concepts discussed in the PDF?"
- "Explain the methodology described in the document"

The system retrieves relevant document sections and generates answers using **Gemini LLM**.

---

# 🧪 Experiments

The following folders contain development experiments:

- **Experiments/** → Retrieval and indexing experiments
- **notebook/** → Prototype notebooks for testing RAG workflows

---

# 📈 Future Improvements

- Vector database integration (FAISS / Pinecone)
- Multi-document knowledge base
- Conversation memory
- API-based query endpoint
- Cloud deployment

---

# 👩‍💻 Author

**Pallavi Mishra**

---

# ⭐ Support

If you found this project useful, consider giving the repository a **star ⭐**.
