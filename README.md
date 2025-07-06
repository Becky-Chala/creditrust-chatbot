# creditrust-chatbot

An AI-powered chatbot system that turns raw customer complaints into actionable insights for internal teams at CrediTrust Financial. This project uses Retrieval-Augmented Generation (RAG) with semantic search and large language models (LLMs) to help Product Managers, Support, and Compliance teams quickly understand customer pain points.

---

## 🚀 Project Overview
CrediTrust Financial serves over 500,000 users across East Africa. With thousands of customer complaints monthly, internal teams face challenges identifying trends and acting proactively.

### 🔥 Key Features
- Natural language query support ("Why are customers unhappy with BNPL?")
- Semantic search using vector databases (FAISS/ChromaDB)
- RAG pipeline for context-grounded answers
- Interactive web UI (Gradio or Streamlit)
- Source transparency: shows excerpts used in answers

---

## 📁 Project Structure
```
creditrust-complaint-analyzer/
│
├── data/
│   ├── raw/                     # Original CFPB dataset
│   └── filtered_complaints.csv  # Cleaned dataset
│
├── notebooks/
│   └── task_1_eda_preprocessing.ipynb  # EDA and preprocessing
│
├── src/
│   └── preprocessing.py         # Text cleaning functions
│
├── vector_store/                # Vector DB for embeddings
│
├── app.py                       # Web UI (Gradio/Streamlit)
├── README.md                    # Project documentation
└── .gitignore
```

---

## 📦 Installation
### Prerequisites
- Python >= 3.8
- pip / conda

### Clone the repo
```bash
git clone https://github.com/Becky-Chala/creditrust-complaint-analyzer.git
cd creditrust-complaint-analyzer
```

### Install dependencies
```bash
pip install -r requirements.txt
```

---

## 📝 Usage
### 1️⃣ EDA & Preprocessing
Run the notebook to explore and clean the data:
```bash
jupyter notebook notebooks/task_1_eda_preprocessing.ipynb
```
This will save a filtered dataset to `data/filtered_complaints.csv`.

---

## 🧠 Technical Stack
- **EDA & Cleaning**: Pandas, Matplotlib, Seaborn
- **Embeddings**: sentence-transformers/all-MiniLM-L6-v2
- **Vector DB**: FAISS / ChromaDB
- **LLM**: Hugging Face Transformers
- **Web UI**: Streamlit / Gradio

---

## 📅 Milestones
| Task                            | Status       |
|---------------------------------|--------------|
| Task 1: EDA & Preprocessing     | ✅ Completed |
| Task 2: Embedding & Indexing    | ⬜ In Progress|
| Task 3: RAG Core Logic          | ⬜ Pending    |
| Task 4: Interactive UI          | ⬜ Pending    |

---

## 👩‍💻 Authors
- Bereket Chala
- 10 Academy – KAIM 5 Week 6 Team

---
