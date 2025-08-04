# SalesServe: Intelligent Sales Forecasting & Conversational Support Bot

**SalesServe** is a dual-function AI platform that delivers both **sales forecasting** and **intelligent voice-based customer support**. This system enables smart business insights and real-time interaction through speech and text

---

## ⚡ Key Highlights

* 📊 **Sales Prediction**
  Harnesses machine learning to forecast future sales based on historical trends and input features.

* 🗣️ **Voice-Driven Customer Assistant**
  A conversational bot that understands and responds to customer voice inputs using advanced NLP pipelines.

---

## 🧰 Technology Stack

* [LangChain](https://www.langchain.com/) – framework for chaining LLMs with tools
* [Groq API](https://groq.com/) – ultra-fast LLM inference
* [Cohere](https://cohere.ai/) – embeddings and generation
* [Whisper](https://openai.com/research/whisper) – speech-to-text by OpenAI
* [SentenceTransformers](https://www.sbert.net/) – for vector-based semantic search
* [scikit-learn](https://scikit-learn.org/) – traditional ML for sales forecasting
* [NetworkX](https://networkx.org/) – graph-based logic (if applicable)
* [Plotly](https://plotly.com/) – interactive visualizations

---

## 📁 Folder Structure

```bash
SalesServe/
├── Chatbot_code.ipynb        # Customer support assistant logic
├── README.md                 # This documentation
```

---

## 🧪 Getting Started

### 🔧 Setup Instructions

#### Clone the Project

```bash
git clone https://github.com/Rohanshu121/SalesServe.git
cd SalesServe
```

### 💻 Running the Notebooks

#### Option A: Locally with Jupyter

1. Install Jupyter if not already:

   ```bash
   pip install notebook
   ```

2. Start the notebook server:

   ```bash
   jupyter notebook
   ```

3. Open:

   * `Chatbot_code.ipynb` to try out the voice-enabled chatbot

#### Option B: On Google Colab

* Upload the notebooks to [Google Colab](https://colab.research.google.com/)
* Link your Google Drive for dataset access if needed
* Run cells interactively in the browser

---

## 📊 Data Inputs

* **Sales Data**: Time-series sales data (e.g., daily/weekly revenue, product info, region, etc.) in `.csv` format.
* **Knowledge Base**: Documents such as FAQs, user manuals, or transcripts to power the retrieval-augmented chatbot.

---

## 🙌 Contribution Guidelines

We welcome community involvement! You can:

* Fork the repo and submit a pull request
* Report bugs or suggest features via [issues](https://github.com/Rohanshu121/SalesServe/issues)
* Help with improvements in code, UI/UX, or documentation

---

## 🔮 Roadmap

* Interactive dashboard for real-time sales tracking
* Streaming voice interface for live customer support
* Seamless integration with CRMs and e-commerce platforms

---

## 📄 License

This project is distributed under the [MIT License](LICENSE). You’re free to use, modify, and share it with proper attribution.
