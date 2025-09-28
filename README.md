# 📐 Maths GPT

Maths GPT is a **Streamlit** web app powered by the **ChatGroq Gemma2-9b-It** model.  
It solves math problems in natural language using a **WikipediaAPIWrapper** tool for quick fact-lookups and explanations.

---

## 🚀 Features
- 🧮 **Natural Language Math Solver** – Ask any math question in plain English.
- 🔍 **Wikipedia Integration** – Fetches supporting facts or definitions on demand.
- ⚡ **Gemma2-9b-It via ChatGroq** – Fast, high-quality reasoning for accurate answers.
- 🌐 **Simple Web UI** – Built entirely with [Streamlit](https://streamlit.io) for instant deployment.

---

## 📦 Tech Stack
| Component        | Description                                      |
|------------------|--------------------------------------------------|
| **Backend**      | [ChatGroq](https://groq.com) with `Gemma2-9b-It` |
| **Tool**         | `WikipediaAPIWrapper` from LangChain             |
| **Frontend**     | Streamlit                                        |
| **Language**     | Python 3.9+                                      |

---

## 🖥️ Demo
1. **Run locally**
   ```bash
   git clone https://github.com/<your-username>/maths-gpt.git
   cd maths-gpt
   pip install -r requirements.txt
   streamlit run app.py


⚙️ Project Structure
maths-gpt/
├─ app.py              # Main Streamlit app
├─ requirements.txt    # Python dependencies
├─ README.md           # This file
└─ ...