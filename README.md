# 🎥 NeuroTube-Project
### An intelligent, multimodal assistant that extracts knowledge from YouTube videos using advanced AI tools. It transcribes, summarizes, answers questions, generates mind maps, and converts insights into speech — all in one streamlined app.

## ✨ Features

 Automatic Transcription using OpenAI Whisper

 Summarization with GPT-4 (via LangChain agents)

 Question Answering on video content

 Mind Map Generation with Graphviz

 Text-to-Speech conversion using gTTS

 Agentic AI using LangChain Tools & Functions

 Modular, Extensible Architecture

 Gradio Interface for interaction

##  Use Cases

Educational content exploration

Lecture or seminar summarization

Podcast or tutorial comprehension

Creating structured study materials from videos

## How It Works
**Upload or provide a YouTube video

The app:

Transcribes the audio using Whisper

Summarizes the content using GPT-4

Answers user questions with context-aware retrieval

Generates a mind map from the summary

Reads the output aloud using TTS

All components are orchestrated using LangChain Agents and Toolchains, with evaluation via LangSmith and vector storage (e.g., FAISS or ChromaDB).

## 🛠 Technologies Used:

Component	Tool                        Library
Transcription                    	OpenAI Whisper
Summarization                  	  GPT-4 via OpenAI API
QA System                        	LangChain Agents
TTS	                                    gTTS
Mind Map Generation	                  Graphviz
UI	                                   Gradio
Evaluation	                          LangSmith
Embeddings / Vector DB	        OpenAI Embeddings + FAISS

## How to Run:
1. Clone the repo:

2.Install dependencies:

3.Run the Gradio app:

4.Upload a YouTube video link or audio file and explore the features.



