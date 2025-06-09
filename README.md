# 🎙️ Voice Command AI

An intelligent voice-controlled assistant app built with Streamlit that can:

- 🎧 Start reading aloud uploaded notes (PDF/Image)
- 🌐 Translate the content into multiple languages
- 📝 Summarize your notes
- ❓ Answer contextual questions
- 🧠 Quiz you based on uploaded content
- ⏩ Change playback speed (Slow / Medium / Fast)

## 🚀 Features
- Voice command recognition using Google Speech API
- OCR support for handwritten or printed notes using Tesseract
- PDF text extraction
- Language translation with DeepL API
- Text-to-speech with pyttsx3
- GPT-3.5 based contextual question answering and summarization
- Interactive Streamlit UI

## 🛠️ Setup Instructions
1. Clone the repo
```bash
git clone https://github.com/yourusername/voice-command-ai.git
cd voice-command-ai
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Add your OpenAI and DeepL API keys in `app.py`

4. Run the app
```bash
streamlit run app.py
```
