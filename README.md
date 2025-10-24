# ContractAnalyzer
AI tool that summarizes and highlights key points from contracts in seconds.
# ContractAnalyzer

**AI-powered Legal Document Summarizer (Prototype)**

ContractAnalyzer is a prototype web application that helps **summarize lengthy legal contracts** in seconds. It extracts key clauses, obligations, liabilities, termination clauses, and potential risks from PDF contracts using AI or simple extractive summarization.  

---

## Features

- Upload a **PDF contract** and get a concise summary.
- Uses **OpenAI GPT model** (if API key provided) for smart AI-based summaries.
- **Fallback extractive summary** if OpenAI API is not set.
- Clean **Streamlit frontend** and **FastAPI backend** architecture.
- Easy to run locally or deploy on cloud platforms.

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, FastAPI |
| Frontend | Streamlit |
| AI | OpenAI GPT API (optional) |
| PDF Handling | PyPDF2 |
| Others | Requests, Python standard libraries |

---

## Demo (Local Setup)

1. **Clone repository & create environment**
```bash
git clone <your-repo-link>
cd ContractAnalyzer
python -m venv venv
# Activate venv
source venv/bin/activate       # macOS/Linux
venv\Scripts\activate.bat      # Windows
