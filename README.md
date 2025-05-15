# YouTubeVideoSummerization-AI

# 🎥 YouTube Video Summarizer using Gemini API

This project is a YouTube video summarizer that:
- Extracts transcripts from any public YouTube video using `youtube-transcript-api`
- Sends the transcript to **Google's Gemini (LLM)** to generate a concise summary
- Can be run entirely in **Google Colab** or locally
- (Optional) Provides a Gradio-powered UI for interactive summarization

---

## ✨ Demo

![demo](https://github.com/yourusername/yourrepo/assets/demo.gif) <!-- Add your own Colab/Gradio demo GIF here -->

---

## 🚀 Features

- ✅ Automatically fetches YouTube subtitles (even auto-generated)
- ✅ Summarizes long videos using Gemini 1.5 Flash or Pro model
- ✅ Runs directly in Google Colab (no need for local setup)
- ✅ Optional web UI with Gradio
- 🔐 Uses your private Google API Key (secured)

---

## 📦 Requirements

Install the dependencies using pip:

```bash
pip install google-generativeai
pip install youtube-transcript-api
pip install pytube
