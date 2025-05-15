# 🎥 YouTube Video Summarizer using Gemini API

This project is a YouTube video summarizer that:
- Extracts transcripts from any public YouTube video using `youtube-transcript-api`
- Sends the transcript to **Google's Gemini (LLM)** to generate a concise summary
- Can be run entirely in **Google Colab** or locally
- (Optional) Provides a Gradio-powered UI for interactive summarization

---

## 🚀 Features

- ✅ Automatically fetches YouTube subtitles (even auto-generated)
- ✅ Summarizes long videos using Gemini 1.5 Flash or Pro model
- ✅ Runs directly in Google Colab (no need for local setup)
- ✅ A `youtube_summary.txt` file generated
- 🔐 Uses your private Google API Key (secured)


---

## ✅ Technical Skills Used
### 🧠 Machine Learning & AI
- Prompt engineering for summarization using Gemini
- LLM API integration (Google Gemini 1.5)

### 🌐 Web APIs & Data Processing
- Extracting YouTube video transcripts using youtube-transcript-api
- Parsing and preprocessing raw transcript text

### 🐍 Python Programming
- Function-based scripting and modular design
- Exception handling for API and network errors

### 📡 API Integration
- Using Google Generative AI SDK (google-generativeai)
- Secure API key handling (getpass, genai.configure)

### 🧪 Notebook Environment
- Interactive development in Google Colab
- Installing and managing Python packages with pip

---

## ✅ Next Steps
- web UI/UX interface design with Gradio (Optional)
- You can build lightweight web apps from Python functions
---

## 📦 Requirements

Install the dependencies using pip:

```bash
pip install google-generativeai
pip install youtube-transcript-api
pip install pytube
