# Distracted Driver Detection

## 🚗 Project Overview

This project uses a Convolutional Neural Network (CNN) to detect
distracted driving behaviors from images. The system classifies driver
actions such as safe driving, texting, talking on the phone, adjusting
the radio, and more.

## 🎯 Objective

The goal is to develop a deep-learning model capable of identifying
unsafe driver behaviors to improve road safety and assist in ADAS
(Advanced Driver Assistance Systems).

## 🛠 Technologies Used

-   Python\
-   TensorFlow / Keras\
-   CNN (Convolutional Neural Network)\
-   OpenCV\
-   Scikit-Learn\
-   NumPy, Pandas\
-   Matplotlib

## 📂 Project Structure

    ├── dataset/                 # Images for training/testing
    ├── models/                  # Saved model files
    ├── scripts/                 # Training & preprocessing scripts
    ├── results/                 # Accuracy, loss graphs
    ├── main.py                  # Main training file
    └── README.md                # Project documentation

## 📊 Model Workflow

1.  **Image Preprocessing** using OpenCV\
2.  **Data Augmentation** to improve generalization\
3.  **CNN Model Training** using TensorFlow\
4.  **Evaluation** using accuracy, loss, precision, recall\
5.  **Prediction** on new driver images

## 📈 Results

-   Achieved high accuracy in classifying distracted vs. non-distracted
    drivers\
-   Model performance improved using augmentation & hyperparameter
    tuning

## ▶️ How to Run the Project

    pip install -r requirements.txt
    python main.py

## 🔮 Future Improvements

-   Real-time detection using webcam feed\
-   Integration with vehicle monitoring systems\
-   Deployment using Flask / FastAPI

## 📄 License

MIT License -- Free to use and modify.
