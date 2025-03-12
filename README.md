## 🎯 Project Overview  

This project analyzes **video and audio** to assess emotions and speech characteristics. It consists of two main components:  

### 🖼️ Video Analysis  
- Extracts video frames using OpenCV.  
- Applies a **CNN-based model** for **emotion detection** (happy, sad, angry, etc.).  
- Counts frames for each detected emotion.  

### 🔊 Audio Analysis  
#### 🎵 Tone Analysis  
- Extracts **pitch, loudness, speech rate, pauses, and silence ratio**.  
- Uses 20+ parameters with logic-based scoring.  

#### 📝 Text Analysis  
- Converts speech to text using **Whisper**.  
- Analyzes transcribed text with **Gemini Pro**.  

### 📌 Technologies Used  
- **Librosa** – Audio processing & feature extraction  
- **NumPy** – Statistical computations  
- **Pydub** – Audio conversion & silence detection  
- **Wave & Audioop** – Handling & analyzing raw audio data  

🚀 **Ready to dive in? Let's analyze emotions like never before!**
