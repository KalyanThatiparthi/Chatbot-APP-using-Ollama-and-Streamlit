# Kalyan's Chatbot App

A simple, lightweight chatbot application powered by **Ollama** and **Streamlit**.

## Overview
This is a user-friendly web application that allows users to interact with AI models 
hosted locally via Ollama. Simply enter your query and get instant responses from 
your preferred language model.

## Features
- 🎨 Clean and intuitive Streamlit web interface
- 🔄 Real-time response generation
- 💬 Interactive chat with AI models
- ⚡ Powered by Ollama's local inference engine

## Tech Stack
- **Frontend**: Streamlit (Python)
- **Backend**: Ollama (Local AI Inference)
- **Model**: minimax-m2.7:cloud (customizable)

## Setup
1. Install dependencies:
   ```bash
   pip install streamlit ollama
2. Ensure Ollama is running locally (localhost:11434)
3. Pull the model:
   ollama pull minimax-m2.7:cloud
4. Run the app:
   streamlit run app.py
Usage
Enter your question or prompt in the text area
Click "Generate Response"
View the AI-generated response instantly
