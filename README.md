# Personalised_Chatbot
PDF Chatbot with AI - Upload PDFs and ask questions. Powered by LangChain, Together AI &amp; Streamlit.

# PDF Chatbot with Streamlit

A conversational AI chatbot that can answer questions about content in uploaded PDF documents.

![Chatbot Screenshot](screenshot.png) <!-- Add your screenshot here -->

## Features

- Upload and process PDF documents
- Natural language question answering
- Uses Mistral-8x7B-Instruct model via Together API
- Context-aware responses based on document content

## How It Works

1. The app extracts text from uploaded PDFs
2. Splits the text into manageable chunks
3. Creates vector embeddings for semantic search
4. Finds relevant document sections when you ask a question
5. Generates answers using a large language model
