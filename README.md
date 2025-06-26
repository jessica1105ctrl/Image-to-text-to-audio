# Image-to-text-to-audio# 🖼️🔤🔊 Image to Text to Audio

This project converts an **image** into **text** using Optical Character Recognition (OCR), and then transforms that text into **speech audio** using Text-to-Speech (TTS) technology. It’s useful for visually impaired users, educational tools, and accessibility-focused applications.

---

## 📌 Features

- 📷 Upload an image containing text
- 🔍 Extract text from the image using OCR (Tesseract)
- 🔊 Convert the extracted text into speech audio (Google Text-to-Speech / pyttsx3)
- 💾 Save the audio file (MP3/WAV) locally
- 🎛️ Simple and interactive user interface (optional GUI or CLI)

---

## 🛠️ Technologies Used

- Python 🐍
- Tesseract OCR 📖
- pytesseract (Python wrapper)
- gTTS (Google Text-to-Speech) or pyttsx3 (offline TTS)
- OpenCV / Pillow (image preprocessing)
- Tkinter / Streamlit (optional GUI)

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.7+
- Tesseract installed and added to PATH
  - [Tesseract Installation Guide](https://github.com/tesseract-ocr/tesseract)
  
### 📦 Installation

```bash
git clone https://github.com/your-username/image-to-text-to-audio.git
cd image-to-text-to-audio
pip install -r requirements.txt
