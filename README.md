# 🎵 Mood-Based Music Recommender System

This project is an intelligent music recommendation system that suggests songs based on the user's current mood. It leverages facial emotion recognition and audio emotion analysis to tailor a personalized music experience.

---

## 🚀 Features

- 🎭 Detects user's mood using facial expressions
- 🎧 Recommends songs that match the detected emotion
- 🧠 Uses machine learning and deep learning models
- 🌐 User-friendly interface for uploading images or audio
- 🎵 Categorized music recommendations (happy, sad, calm, energetic, etc.)

---

## 🛠️ Technologies Used

| Layer        | Tech Stack                                   |
|--------------|-----------------------------------------------|
| 👨‍💻 Frontend   | HTML, CSS, JavaScript                       |
| 🧠 Backend    | Python, Flask                                |
| 📊 ML Models  | OpenCV, TensorFlow/Keras, Scikit-learn       |
| 🔍 Emotion Detection | Haar Cascades, CNNs (for emotion classification) |
| 📦 Music DB   | Custom curated music dataset or Spotify API (optional) |
| 🔧 Tools      | Git, GitHub, VS Code                         |

---

## 💡 How It Works

1. The user uploads an image or audio file.
2. The system processes the input to detect emotion using trained models.
3. Based on the detected mood (e.g., happy, sad, angry, neutral), the system recommends songs aligned with that emotional state.
4. Songs are played or recommended through a simple web interface.

---

## 📁 Project Structure

```bash
.
├── app.py                  # Main Flask app
├── model/                  # Trained ML models
├── static/
│   └── css/, js/, images/  # Frontend assets
├── templates/
│   └── index.html          # Web UI
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
