# 🤟 Sign Language Detection System

## 📌 Overview

This project is a **Sign Language Detection System** built using **Python, OpenCV, MediaPipe, and Scikit-learn**.
It detects hand gestures in real-time using a webcam and classifies them into predefined sign language gestures.

The goal of this project is to help bridge communication gaps between **hearing-impaired individuals and others** by translating hand gestures into meaningful outputs.

---

## 🚀 Features

* 🎥 Real-time hand tracking using webcam
* ✋ Hand landmark detection with MediaPipe
* 🧠 Machine Learning model for gesture classification
* ⚡ Fast and efficient prediction using Scikit-learn
* 📊 Custom dataset training support
* 🖥️ Easy-to-use interface

---

## 🛠️ Tech Stack

* **Python**
* **OpenCV**
* **MediaPipe**
* **Scikit-learn**
* **NumPy / Pandas**

---

## 📂 Project Structure

```
Sign-Language-Detection/
│── data/                 # Dataset (if used)
│── model/                # Trained ML model
│── src/                  # Source code files
│── main.py               # Main execution file
│── train_model.py        # Model training script
│── utils.py              # Helper functions
│── requirements.txt      # Dependencies
│── README.md             # Project documentation
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/sign-language-detection.git
cd sign-language-detection
```

### 2. Create virtual environment (optional but recommended)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Run the application

```bash
python main.py
```

* Your webcam will open
* Show hand gestures in front of the camera
* The system will detect and display the predicted sign

---

## 🧠 How It Works

1. **Hand Detection**
   MediaPipe detects hand landmarks (21 key points).

2. **Feature Extraction**
   Landmark coordinates are extracted and normalized.

3. **Model Training**
   A machine learning model (Scikit-learn) is trained on gesture data.

4. **Prediction**
   The trained model predicts gestures in real-time.

---

## 📊 Dataset

* Custom dataset created using hand landmark coordinates
* Each gesture is labeled and used for training the model

---

## 📈 Future Improvements

* Add more gesture classes
* Improve model accuracy using deep learning
* Add GUI interface
* Convert to mobile/web application
* Support full sentence recognition

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

## 🙌 Acknowledgements

* MediaPipe for hand tracking
* OpenCV for image processing
* Scikit-learn for machine learning

---

⭐ If you like this project, consider giving it a star!
