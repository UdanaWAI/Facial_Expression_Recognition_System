# Facial Expression Recognition System

This project implements a **Facial Expression Recognition System** using deep learning. It includes model training, evaluation, and a real-time emotion prediction application.

---

## Dataset

I used the **Face Expression Recognition Dataset** from Kaggle:
[Face Expression Recognition Dataset](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset)

* The dataset contains grayscale images of faces (48x48 pixels) categorized into seven expressions:
  **Angry, Disgusted, Fear, Happy, Neutral, Sad, Surprise**

---

## Design & Models

### Model 1

* File: `Facial_Expressions_Recognition.ipynb`
* Trained model: `facial_expressions_model.h5`

### Model 2 (MobileNetV2)

* File: `Facial_Expressions_MobileNetV2.ipynb`
* Trained model: `facial_expressions_model_MobileNetV2.h5`

---

## Model Performance

* File: `Model_Performance.ipynb`
* Contains accuracy, precision, recall, F1-score, and other evaluation metrics for the models.

---

## Real-Time Application

* File: `Real-time_emotion_prediction.ipynb`
* Implements a live emotion detection system using the trained models.
* Features include displaying detected emotions and providing a brief analysis of the emotional state.

---

## Features

* Multi-model training and evaluation
* Real-time webcam emotion detection
* Performance metrics visualization
* Support for seven basic facial expressions

---

## Usage

1. Clone this repository:

   ```bash
   git clone <https://github.com/UdanaWAI/Facial_Expression_Recognition_System.git>
   ```
2. Install required dependencies (TensorFlow, OpenCV, NumPy, etc.).
3. Run the desired Jupyter Notebook for training, evaluation, or real-time emotion detection.

---

## References

* Face expression recognition dataset. (n.d.). [Kaggle](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset)
