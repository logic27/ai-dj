# 🎧 AI DJ – Mood-Based Music Mixer

An experimental AI-powered DJ that dynamically changes songs based on the mood of the crowd. This project combines real-time emotion detection with intelligent playlist curation to create immersive, mood-aware music experiences.

---

## 🧠 What It Does

AI DJ captures crowd emotions using video feeds or sensor data, then analyzes that data in real time to adapt the music accordingly. Whether you're at a party, a lounge, or an event, the AI DJ adjusts the vibe to match the audience’s collective energy.

### Core Features

- 🎵 **Automatic Song Transitioning**  
  Smooth transitions between tracks based on detected mood shifts.

- 😄 **Mood Detection**  
  Uses computer vision and/or wearable data to analyze crowd emotions (e.g., happy, bored, hyped, calm).

- 🎚️ **Real-Time Adaptation**  
  Adjusts genre, tempo, and energy level to match the current mood.

- 🎶 **Smart Playlist Engine**  
  Builds and modifies playlists on-the-fly using Spotify, local files, or YouTube.

- 🧩 **Modular Architecture**  
  Easy to extend and customize. Use your own mood detection model or music source.

---

## 🔧 Technologies Used

- **Python / Node.js** – Core logic and orchestration  
- **OpenCV / MediaPipe** – Mood detection from faces and gestures  
- **TensorFlow / PyTorch** – Emotion recognition models  
- **Spotify API / YouTube API** – Music sourcing and control  
- **FFmpeg / VLC** – For song transitions and playback  
- **Socket.io / WebSockets** – Real-time communication layer  

---

## 🚀 Getting Started

### Prerequisites

- Python 3.10+  
- Node.js 18+  
- FFmpeg installed  
- Spotify Developer account (if using Spotify integration)  
- Webcam or video input for mood detection  

### Installation

```bash
git clone https://github.com/your-username/ai-dj
cd ai-dj

# Setup backend
cd backend
pip install -r requirements.txt

# Setup frontend / control panel
cd ../frontend
npm install
