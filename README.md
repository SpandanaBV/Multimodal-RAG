Multimodal-RAG

An AI-powered chat application that supports text, audio, images, and PDFs for context-aware responses. It integrates language models with vector databases to enhance retrieval-augmented generation (RAG), making it a versatile tool for intelligent conversations.

🚀 Features

Text-to-Speech: Convert text responses to audio using gTTS

Speech-to-Text: Transcribe audio files using speech_recognition and Wav2Vec2

Visual Question Answering (VQA): Answer questions based on uploaded images using BLIP

PDF Knowledge Base: Upload PDFs to enhance knowledge and improve response accuracy

Context-Aware Responses: Use conversation history to provide more relevant answers

🛠 Tech Stack

Python

Streamlit (UI)

LangChain (LLM orchestration & RAG)

Pinecone (vector database)

gTTS (text-to-speech)

📂 Project Structure

app.py – Main Streamlit application

audio_processor.py – Handles speech-to-text and text-to-speech

llama_cpp_chains.py – LLaMA-based model chains

ollama_chain.py – Ollama-based model chains & RAG chains

pdf_handler.py – PDF loading and splitting

vqa.py – Visual question answering and audio transcription

vectorstore.py – Vector database setup and indexing

utils.py – Utility functions, configuration loader

Wav2Vec2 (speech-to-text)

BLIP (image-based Q&A)
