# TTS & STT Demonstration

## 🎤 Overview
This project demonstrates **Text-to-Speech (TTS) and Speech-to-Text (STT)** capabilities using **Google TTS, Whisper, and Gradio**. It includes real-time speech transcription, waveform visualization, and language translation.

## 🚀 Features
- **Text-to-Speech (TTS)**: Converts text into spoken audio using **Google TTS**.
- **Speech-to-Text (STT)**: Recognizes and transcribes speech using **Whisper**.
- **Multi-Language Support**: Demonstrates TTS in **English, Spanish, French, and German**.
- **Waveform & Spectrogram Visualization**: Displays the audio signal for better analysis.
- **Real-Time Transcription UI**: Uses **Gradio** for interactive speech recognition.
- **API Integration**: Connects with **Google Speech-to-Text and Whisper API**.

## 📦 Installation
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/kalopez0621/TTS_and_STT.git
cd TTS_and_STT
```

### **2️⃣ Set Up Virtual Environment**
```bash
python -m venv .venv
source .venv/bin/activate  # Mac/Linux
.\.venv\Scripts\activate  # Windows
```

### **3️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

## 🎯 Usage
### **Run the Demonstration**
To start the **TTS & STT demonstration**, run:
```bash
jupyter notebook TTS-STT.ipynb
```
or use:
```bash
python main.py
```
This will launch an **interactive demo** using Gradio.

## 🛠️ Technologies Used
- **[Whisper](https://github.com/openai/whisper)** - Speech-to-Text
- **[gTTS](https://pypi.org/project/gTTS/)** - Google Text-to-Speech
- **[Gradio](https://gradio.app/)** - Web Interface
- **[Librosa](https://librosa.org/)** - Audio Analysis
- **[Pydub](https://pydub.com/)** - Audio Processing
- **[Matplotlib](https://matplotlib.org/)** - Visualization

## 📌 Future Improvements
- 🔹 Improve **speech recognition accuracy** with fine-tuned models.
- 🔹 Add **custom voices** for more natural TTS output.
- 🔹 Enhance **real-time responsiveness** for faster transcription.

## 👥 Contributors
- **[Karla Lopez](https://github.com/kalopez0621)** - Project Creator

## 📜 License
This project is open-source and licensed under the **MIT License**.

---
🎤 **Try it out and explore the power of AI-driven speech technology!** 🚀

