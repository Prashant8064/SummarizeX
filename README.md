# SummarizeX 🧠📄

**SummarizeX** is an AI-powered document summarization tool built with cutting-edge NLP models and an intuitive Gradio interface. It intelligently summarizes PDF, DOCX, and TXT files using both **abstractive** and **extractive** methods.

---

## 🚀 Features

- 🧠 **Abstractive Summarization** using:
  - `facebook/bart-large-cnn`
  - `google/pegasus-xsum`
  - `t5-small`
- 📝 **Extractive Summarization** with LSA (Latent Semantic Analysis)
- 📊 **ROUGE-1 / ROUGE-L** evaluation for comparison
- ☁️ **WordCloud** generation from summaries
- 📄 Upload and summarize `.pdf`, `.docx`, or `.txt` documents
- ⚡ Fast, interactive **Gradio web UI**

---


## 🔧 Tech Stack

- Python
- HuggingFace Transformers
- Sumy (for LSA extractive summary)
- Gradio (UI)
- WordCloud, Matplotlib
- ROUGE Score
- docx2txt, PyPDF2

---

## 📦 Installation

```bash
pip install -r requirements.txt
or

bash
Copy
Edit
pip install gradio transformers sumy wordcloud textstat python-docx PyPDF2 rouge-score docx2txt
▶️ Run the App
bash
Copy
Edit
streamlit run SummarizeX.ipynb
# or convert to .py and run: python app.py
🧪 Example Usage
Input:
Upload a research_paper.pdf with 3–5 pages of technical text

Output:
Abstractive Summary (via BART):
"This paper explores transformer-based models in NLP and compares performance across several datasets."

ROUGE-1: 0.621 | ROUGE-L: 0.598
WordCloud: (auto-generated from key summary terms)

📁 Project Files
SummarizeX.ipynb: Main notebook with full summarization logic

Advanced-Text-Summarization.pptx: Project presentation

requirements.txt: All dependencies

assets/demo_screenshot.png: Optional demo image

📄 License
Licensed under the MIT License — free to use, fork, and improve.

🙋‍♂️ About Me
Made with ❤️ by @Prashant8064
🚀 Open to AI, NLP, and LLM-related full-time or remote roles.

🔗 Connect
  prashantgupta8064@gmail.com ✉️ Email
