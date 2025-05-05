# 🎥 NeuroTube-Project
### An intelligent, multimodal assistant that extracts knowledge from YouTube videos using advanced AI tools. It transcribes, summarizes, answers questions, generates mind maps, and converts insights into speech — all in one streamlined app.




## 🚀 Features


🔗 YouTube Downloader: Downloads high-quality video/audio using yt_dlp.

🧠 Transcription: Converts video audio to text using OpenAI’s Whisper model.

📋 Chunking & Vector Embedding: Splits transcripts into chunks and embeds them using OpenAI embeddings with FAISS vector storage.

💬 Question Answering: Uses GPT-4 and LangChain’s RetrievalQA to answer questions based on the video transcript.

📝 Summarization: Summarizes transcripts into bullet points using GPT-4.

🗣️ Text-to-Speech & Speech-to-Text: Converts between text and speech using gTTS and speech_recognition.

🧭 Mind Map Generation: Visualizes summarized content as a mind map using Graphviz.

🤖 LangChain Agent: An intelligent agent that decides whether to summarize or answer questions.




##  Use Cases

1.Educational content exploration

2.Lecture or seminar summarization

3.Podcast or tutorial comprehension

4.Creating structured study materials from videos



## How It will look:

**Upload or provide a YouTube video

The app:

Transcribes the audio using Whisper

Summarizes the content using GPT-4

Answers user questions with context-aware retrieval

Generates a mind map from the summary

Reads the output aloud using TTS

All components are orchestrated using LangChain Agents and Toolchains, with evaluation via LangSmith and vector storage (e.g., FAISS or ChromaDB).




## 📦 Libraries and Their Purpose

| Library | Description |
|--------|-------------|
| `os`, `re`, `time`, `random`, `tempfile`, `json`, `concurrent.futures` | Standard Python libraries used for system operations, regex, timing, randomness, temp files, JSON handling, and parallel processing. |
| `yt_dlp` | Downloads videos and extracts audio from YouTube. |
| `whisper` | OpenAI’s speech recognition model for transcribing audio. |
| `speech_recognition` | Library for performing speech recognition with various engines. |
| `pydub` | Used for audio processing and format conversion. |
| `moviepy.editor` | For extracting and manipulating audio/video content. |
| `gtts` | Google Text-to-Speech – converts text into spoken audio. |
| `graphviz` | Creates visualizations like diagrams and mind maps. |
| `gradio` | For building simple web UIs (planned for future UI integration). |
| `langchain` | Framework for developing applications powered by LLMs. |
| `langchain_openai` | Integrates LangChain with OpenAI models like GPT-4. |
| `FAISS` | Vector database for efficient similarity search and retrieval. |




## How to Run:
1. Clone the repo:
   
```bash
# Your bash commands go here
python3 main.py
pip install -r requirements.txt
```


2.Install dependencies:

```bash
pip install -r requirements.txt
```

3.Set your environment variables:
You can store these in a .env file or directly in your environment:

```bash
export OPENAI_API_KEY=your_openai_key
export LANGCHAIN_API_KEY=your_langchain_key
export LANGCHAIN_PROJECT=youtube-rag-bot

```

## 📁 File Project Structure

```
neurotube_project/
├── neurotube_project.py       # Main Python script for the project
├── README.md
├── requirements.txt           # List of required Python packages
└── deploy_app.ipynb          # Jupyter notebook for deployment process
└── .env (optional)         # For environment variables
```

## ❗ Security Note
Do not commit your API keys in code. Use environment variables or secret management tools.



نسخ
تحرير



