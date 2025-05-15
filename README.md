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

## ✅ Next Steps
- web UI with Gradio (Optional)
---

## 📦 Requirements

Install the dependencies using pip:

```bash
pip install google-generativeai
pip install youtube-transcript-api
pip install pytube
