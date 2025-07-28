# RAG Chatbot using Flowise + Google Gemini

This project is a **Retrieval-Augmented Generation (RAG)** chatbot that answers questions based on the book *Ikigai: The Japanese Secret to a Long and Happy Life*. Built with [FlowiseAI](https://github.com/FlowiseAI/Flowise) using the Google Gemini model and a vector store retriever.

## 🔧 Features

- Google Gemini-powered question answering
- Vector store document retrieval
- Chat history context (ConversationalRetrievalQAChain)
- Book-based RAG over *Ikigai* content

## 📁 Files

- `RAG Chatbot Chatflow.json` – Flowise chatflow configuration
- `README.md` – Project overview
- `requirements.txt` – Python dependencies (if needed)

## 🚀 Getting Started

1. Install Flowise:
   ```bash
   npm install -g flowise
   flowise start
Import the chatflow:

Go to Flowise UI → Import RAG Chatbot Chatflow.json

Add your Google Gemini credentials

Upload your documents to the vector store

Start chatting!

📊 Evaluation Metrics
To evaluate performance:

Accuracy: Compare answers with ground-truth content from the book

Relevance: Use cosine similarity between retrieved documents and user queries

Latency: Measure response time for each query

🧠 Model Details
LLM: Google Gemini (gemini-2.5-flash-preview)

Retriever: Flowise DocumentStore Vector Store

Chain: ConversationalRetrievalQAChain

📚 Dataset
Based on the book:

Ikigai: The Japanese Secret to a Long and Happy Life by Héctor García and Francesc Miralles

🙌 Acknowledgements
FlowiseAI

Google AI

📌 License
MIT License

yaml
Copy
Edit

---

## 🔗 Post Your GitHub Link on LinkedIn

Once deployed, share it on LinkedIn with a caption like:

> 🚀 Just deployed my **RAG Chatbot using Google Gemini & Flowise**!  
> This bot answers questions from *Ikigai: The Japanese Secret to a Long and Happy Life* using conversational context and a vector retriever.  
> Explore the repo: [https://github.com/your_username/rag-chatbot-flowise](https://github.com/your_username/rag-chatbot-flowise)  
>  
> #AI #GenAI #RAG #Flowise #LLM #Chatbot #OpenSource

---

Let me know if you want me to:
- Create the `README.md` file for download
- Generate a `requirements.txt`
- Help publish the chatbot on Hugging Face or Render
