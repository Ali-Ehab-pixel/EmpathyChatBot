# EmpathyChatBot
This project is an AI-powered chatbot that can detect emotions in text and respond empathetically using Retrieval-Augmented Generation (RAG).
🚀Key Features:
Emotion Detection: Uses a pre-trained Hugging Face model to classify user input into positive, neutral, or negative.
Response Retrieval (RAG) → Searches a custom corpus (corpus.json) using FAISS embeddings for relevant response templates.
Natural Responses → Combines retrieved responses with few-shot prompting for human-like answers.
Interactive Demo → Deployable via Streamlit or Gradio, and easily shareable on Hugging Face Spaces or Streamlit Cloud.
