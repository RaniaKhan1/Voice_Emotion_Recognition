# Voice Emotion Recognition AI

A machine learning web app that detects **human emotions** from voice using the **RAVDESS dataset**. Built with Python, audio processing, and Gradio for an interactive user interface.

---

## Features

- Detects emotions like: **happy**, **sad**, **angry**, **neutral**, etc.
- Uses **MFCC** (Mel-Frequency Cepstral Coefficients) for feature extraction
- Trained with **Random Forest** and **KNN** classifiers
- Simple and interactive **Gradio UI**
- Model trained on the **RAVDESS** dataset (Kaggle)

---

## Requirements

Install required Python packages:

```bash
pip install librosa soundfile numpy pandas scikit-learn gradio
## **How to Run**

Clone the repository:
```bash
git clone https://github.com/Raniakhan1/Voice-Emotion-Recognition.git
cd Voice-Emotion-Recognition
Launch the voice-emotion-recognation.py:

```bash
voice-emotion-recognation.py
You’ll see a Gradio web interface open in your browser to upload .wav files and get emotion predictions.

File Structure
bash
├── voice-emotion-recognation.py                
├── emotion_model.pkl        
├── scaler.pkl
├── label_encoder.pkl
├── voice-emotion-recognation.ipynb   
├── README.md
             
Model Evaluation
Accuracy: 85–90% (on test data)

Confusion Matrix, Precision, Recall & F1-score included in notebook

Dataset
RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)
Download from Kaggle: https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio


Submission
Part of TechnikNest AI/ML Mini Project Series 2025
