# 😸Emotion Detection using Deep Learning

This project uses a Convolutional Neural Network (CNN) to detect facial emotions from images using the FER-2013 dataset. 
The goal is to classify expressions and later map them to emojis.

## 📂Dataset

I have used the [FER-2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013) - which consists of grayscale facial images (48x48 pixels) categorized into 7 emotions:
- Angry 😠
- Disgust 🤢
- Fear 😨
- Happy 😄
- Sad 😢
- Surprise 😲
- Neutral 😐

## ❗Model Architecture
- Convolutional layers with ReLU activation
- Batch Normalization for stability
- MaxPooling to reduce dimensions
- Dense layers with Dropout to prevent overfitting
- Final output layer with softmax activation for 7-class classification

## 🧷Reports and Diagnostics:
![image](https://github.com/user-attachments/assets/16d584cb-f02a-47ca-a7d5-631f5b8126af)
![image](https://github.com/user-attachments/assets/e1232bec-1d9a-4add-b72f-24e503785568)

## 🛠️Requirements
Install dependencies:
```bash
pip install tensorflow keras numpy matplotlib

