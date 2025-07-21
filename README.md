# 🎭 Emotion Detection from the Most Talkative Person in a Video

This project analyzes a video to identify the person who speaks the most and tracks their emotional state throughout the footage using facial expression analysis.

## 🔍 What it does

- Detects active speakers using a combination of:
  - Voice Activity Detection (VAD)
  - Lip movement scoring
  - Face recognition for identity tracking
- Identifies the most talkative individual across the video
- Applies [DeepFace](https://github.com/serengil/deepface) to detect facial emotions (e.g., happy, sad, neutral, angry)
- Outputs a timeline of emotions expressed by the dominant speaker

## 🧑‍💻 Project Context

This model was developed as part of a **team project focused on emotion detection from videos**, integrating audio-visual signals and AI-based facial emotion recognition.

🎥 **Presentation video (in Romanian):** [Watch here](https://www.youtube.com/watch?v=BNJF8pHVoaw)

## 🛠️ Technologies Used

- Python
- OpenCV
- MediaPipe
- DeepFace
- WebRTC VAD
- NumPy, scikit-learn

## 📦 Use Cases

- Video emotion analytics
- Social interaction analysis
- Media content analysis (e.g., debates, interviews)
