# 🎙️ Emotion Detection from Speech (MARS Project)

This project performs **real-time emotion classification** from speech using deep learning. Upload a `.wav` audio file and the model will predict the emotion expressed in the voice.

---

## 💡 Overview

The system uses audio processing (`librosa`) to extract MFCC features and classifies them using a trained Convolutional Neural Network (CNN).

**Emotions classified:**
- Angry
- Calm
- Disgust
- Fearful
- Happy
- Neutral
- Sad
- Surprised

---

## 📁 Folder Structure

MARS_Project_DL/
speech_emotion_app/ 
├── app.py 
├── emotion_final.h5 
├── label_encoder.pkl 
├── test_script.py 
├── requirements.txt 
├── README.m


---

## 🧠 Model Details

- Input: MFCC features (shape: 300x40)
- Model: 1D CNN + BI-LSTM with Dropout
- Accuracy: > 80% F1 on validation data
- Normalized features, class weights used

---

- You can use anaconda prompt to run this code in the folder where streamlit_app.py is there 
streamlit run streamlit_app.py




https://github.com/user-attachments/assets/b64345e9-38ff-4a91-8cc0-78534a9e88a3

