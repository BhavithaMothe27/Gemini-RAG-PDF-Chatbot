📄 AI RAG PDF Chatbot

An AI-powered Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF documents and ask questions about their content. The chatbot uses semantic search with vector embeddings and Google's Gemini model to generate accurate answers based only on the uploaded document.

🚀 Features

- 📂 Upload PDF documents
- 📖 Extract text automatically
- ✂️ Smart text chunking
- 🔍 Semantic search using ChromaDB
- 🧠 Sentence Transformer embeddings
- 🤖 Google Gemini 2.5 Flash for answer generation
- 💬 Interactive Gradio web interface
- ⚡ Fast and accurate document question answering

🛠️ Technologies Used

- Python
- Gradio
- ChromaDB
- Google Gemini API
- Sentence Transformers
- PyPDF
- UUID

📁 Project Structure

```
RAG-PDF-Chatbot/
│
├── app.py
├── requirements.txt
├── README.md
└── sample.pdf
```

📦 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/RAG-PDF-Chatbot.git
cd RAG-PDF-Chatbot
```

Install dependencies

```bash
pip install -r requirements.txt
```

▶️ Run the Application

```bash
python app.py
```

or

```bash
python main.py
```

The Gradio interface will open in your browser.

Configure Gemini API

Replace

```python
genai.configure(api_key="YOUR_GEMINI_API_KEY")
```

with your own Google Gemini API key.

📸 Workflow

1. Upload a PDF document.
2. The PDF text is extracted.
3. Text is divided into chunks.
4. Embeddings are generated using Sentence Transformers.
5. ChromaDB stores the vector embeddings.
6. User asks a question.
7. Semantic search retrieves relevant chunks.
8. Gemini generates an answer using the retrieved context.

📚 Future Improvements

- Multi-PDF support
- Chat history
- Citation of source pages
- OCR for scanned PDFs
- Persistent vector database
- User authentication
- Streamed responses

Author

Bhavitha Mothe
