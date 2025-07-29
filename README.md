# 🎤 Voice Emotion Recognition using ML (RAVDESS Dataset)

Welcome to the Voice Emotion Recognition AI project!  
This project detects emotions from speech audio using machine learning techniques.  

## 📌 Features

- Predicts emotions like **neutral**, **happy**, **angry**, **sad**, etc.
- Uses **MFCC** features from audio.
- Built with **Random Forest** and **K-Nearest Neighbors (KNN)**.
- Includes a simple **Gradio UI**.
- Trained on the **RAVDESS** dataset.

## 📁 Dataset

- 📦 Dataset: [RAVDESS - Ryerson Audio-Visual Database of Emotional Speech and Song](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)
- 🎙️ Audio samples of 24 actors expressing 8 emotions.

## 🛠️ Requirements

Install dependencies:

```bash
pip install librosa soundfile scikit-learn numpy pandas gradio

🚀 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/YourUsername/Voice-Emotion-Recognition.git
cd Voice-Emotion-Recognition
Launch the Gradio app:

bash
Copy
Edit
python app.py
You’ll see a Gradio web interface open in your browser to upload .wav files and get emotion predictions.

📁 File Structure
bash
Copy
Edit
.
├── app.py                   # Main Gradio UI and prediction logic
├── emotion_model.pkl        # Trained Random Forest classifier
├── scaler.pkl               # Standard scaler used in training
├── label_encoder.pkl        # Label encoder for emotion labels
├── dataset_preprocessing.ipynb   # Full dataset processing & training notebook
├── README.md                # Project documentation
📊 Model Evaluation
Accuracy: 85–90% (on test data)

Confusion Matrix, Precision, Recall & F1-score included in notebook

📂 Dataset
RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
Download from Kaggle: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio

👥 Contributing
Pull requests are welcome! For major changes, open an issue first to discuss what you’d like to improve.

📌 Submission
Part of TechnikNest AI/ML Mini Project Series 2025
