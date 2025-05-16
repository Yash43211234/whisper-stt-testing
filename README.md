# Whisper STT - Speech-to-Text Transcription

This project demonstrates how to use OpenAI's **Whisper** model for converting audio files (like `.mp3`, `.wav`, `.m4a`) into text using **Python**, **Hugging Face Transformers**, and **Jupyter Notebook**.

---

## 📌 Features

- 🎙️ Transcribes speech from MP3 audio files
- 🌐 Supports multiple languages
- ⚙️ Works offline with local models
- 🚀 Powered by OpenAI's Whisper and Hugging Face pipeline

---

## 📁 Project Structure

whisper-stt-testing/
├── whisper_transcribe.ipynb
├── README.md
└── sample_audio.mp3




## 📦 Requirements

Install dependencies using pip:


pip install transformers
pip install git+https://github.com/openai/whisper.git
pip install torchaudio

# 🧪 How It Works

from transformers import pipeline

pipe = pipeline("automatic-speech-recognition", model="openai/whisper-base")
result = pipe("sample_audio.mp3")
print(result['text'])


# 🛠️ Future Enhancements
Add a simple GUI

Auto language detection

Timestamped transcriptions

# 📄 License
This project is for educational purposes and follows OpenAI & Hugging Face licensing terms.

#🙋‍♂️ Author
Yash43211234


---

### ✅ To add this file:

Paste this in a new file called `README.md` in your Jupyter Notebook folder:

```python
with open("README.md", "w") as f:
    f.write("""# Whisper STT - Speech-to-Text Transcription

This project demonstrates how to use OpenAI's **Whisper** model for converting audio files (like `.mp3`, `.wav`, `.m4a`) into text using **Python**, **Hugging Face Transformers**, and **Jupyter Notebook**.



## 📌 Features

- 🎙️ Transcribes speech from MP3 audio files
- 🌐 Supports multiple languages
- ⚙️ Works offline with local models
- 🚀 Powered by OpenAI's Whisper and Hugging Face pipeline

---

## 📁 Project Structure

whisper-stt-testing/
├── whisper_transcribe.ipynb
├── README.md
└── sample_audio.mp3

## 📦 Requirements

Install dependencies using pip:

```bash
pip install transformers
pip install git+https://github.com/openai/whisper.git
pip install torchaudio

How It Works

from transformers import pipeline

pipe = pipeline("automatic-speech-recognition", model="openai/whisper-base")
result = pipe("sample_audio.mp3")
print(result['text'])

🛠️ Future Enhancements
Add a simple GUI

Auto language detection

Timestamped transcriptions

📄 License
This project is for educational purposes and follows OpenAI & Hugging Face licensing terms.

# 🙋‍♂️ Author
Yash43211234


Then commit and push it:

```python
!git add README.md
!git commit -m "Add README.md with project overview"
!git push





