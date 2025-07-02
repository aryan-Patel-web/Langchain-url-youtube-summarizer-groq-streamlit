
# LangChain URL & YouTube Summarizer with Groq + Streamlit

A Streamlit web app to summarize the textual content of **any web page or YouTube video** using LangChain, Groq’s blazing-fast LLMs, and powerful document loaders.

---

## 🚀 Features

✅ Summarize YouTube videos  
✅ Summarize web articles and pages  
✅ Uses LangChain summarization chains  
✅ Groq LLMs for high-speed responses  
✅ Easy-to-use Streamlit frontend

---

## 🛠️ Requirements

- Python 3.10+
- Groq API Key

Install Python dependencies:

```bash
pip install -r requirements.txt


---

## ✅ requirements.txt

```txt
streamlit
langchain
langchain-community
langchain-core
langchain-groq
validators
python-dotenv


🔑 Environment Variables
Create a .env file:


GROQ_API_KEY=sk-xxxxxx

🚀 Running the App

streamlit run app.py


🌐 Usage
Enter any valid URL (YouTube or website) in the input field and click Summarize. The app extracts the text and produces a summary.

Example prompt:


URL: https://www.example.com/some-article

Or a YouTube video:

URL: https://www.youtube.com/watch?v=dQw4w9WgXcQ


🎯 Future Enhancements
Support longer video transcripts

Multilingual summarization

Save summaries as PDF or download

Add keyword extraction

👨‍💻 Author
Aryan Patel