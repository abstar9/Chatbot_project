# 🎬 T5 Movie Recommender Chatbot

This project fine-tunes a small transformer model (T5-small) to build an intelligent movie recommendation chatbot. Users can ask for movies by genre, mood, actor, or director, and get a relevant movie title in response.

## 🧠 What it does

- Understands natural language movie questions
- Suggests real movie titles
- Supports genres, actors, directors, and emotional cues (e.g., "I'm sad, recommend a happy movie")

## 📚 Technologies

- 🤗 HuggingFace Transformers (T5-small)
- 🐍 Python, Pandas, Datasets
- 💬 Gradio (for the web UI)

## 🛠 How it works

1. Load and clean a TMDB-based movie metadata dataset
2. Generate 1,500 to 50,000 Q&A training pairs
3. Fine-tune T5-small using HuggingFace Trainer
4. Save and reload the model
5. (Optional) Run chatbot via Gradio

## 🚀 Try it

```bash
pip install transformers datasets gradio

