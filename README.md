# 🤖 AI-Powered Web Scraper with FAISS & Streamlit

This project is an **AI-powered web scraper** that extracts text from
websites, stores it in a **FAISS vector database**, and enables
**question-answering (Q&A)** using **Ollama LLM** with **Hugging Face
embeddings**.

------------------------------------------------------------------------

## 🚀 Features

-   🌍 Scrape website text content (from `<p>` tags).
-   🔎 Store text chunks in a **FAISS vector database** for similarity
    search.
-   🧠 Use **Hugging Face MiniLM embeddings** for text vectorization.
-   🤖 Answer user questions with context from scraped websites using
    **Mistral LLM** via Ollama.
-   🎨 Interactive **Streamlit Web UI**.

------------------------------------------------------------------------

## 🛠️ Installation

1.  **Clone this repository**

``` bash
git clone https://github.com/MaddyRizvi/Web-Scrapper-AI-Agent.git
cd web-scraper-agent
```

2.  **Create & activate virtual environment (recommended)**

``` bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate    # On Windows
```

3.  **Install dependencies**

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

## 📦 Requirements

Make sure the following Python packages are installed:

-   `requests`
-   `streamlit`
-   `faiss-cpu`
-   `numpy`
-   `beautifulsoup4`
-   `langchain`
-   `langchain-community`
-   `langchain-ollama`
-   `sentence-transformers`

Create a `requirements.txt` file with:

``` txt
requests
streamlit
faiss-cpu
numpy
beautifulsoup4
langchain
langchain-community
langchain-ollama
sentence-transformers
```

------------------------------------------------------------------------

## ▶️ Usage

Run the Streamlit app:

``` bash
streamlit run scraper_app.py
```

Then open the URL provided by Streamlit (default:
`http://localhost:8501`) in your browser.

------------------------------------------------------------------------

## 💡 How It Works

1.  User enters a **website URL**.
2.  Website text (`<p>` tags) is **scraped** and stored in FAISS.
3.  Text is **split into chunks** and embedded using Hugging Face MiniLM
    embeddings.
4.  User enters a **question** → FAISS retrieves relevant context.
5.  **Mistral LLM** (via Ollama) generates an **AI-powered answer**.

------------------------------------------------------------------------

## 📝 Example

-   Input: `https://example.com`
-   Question: `"What is this website about?"`
-   Output: 🤖 AI generates an answer based on the scraped content.

------------------------------------------------------------------------

## ⚡ Notes

-   FAISS stores chunks in-memory only (not persistent).
-   Text is limited to **5000 characters** per site to avoid overload.
-   Ensure **Ollama** is installed and running with the `mistral` model.

------------------------------------------------------------------------

## 📜 License

This project is licensed under the **MIT License**.

------------------------------------------------------------------------

👨‍💻 Developed with ❤️ using **Python, FAISS, HuggingFace & Streamlit**.
