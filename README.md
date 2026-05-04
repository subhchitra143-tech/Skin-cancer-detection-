# 🧠 Skin Cancer Detection System (CNN + Flask)

## 📌 Overview

This project is a **deep learning-based Skin Cancer Detection System** that classifies skin lesion images using a **Convolutional Neural Network (CNN)**.
It is designed to assist in **early diagnosis** by providing automated predictions from dermoscopic images.

The system also includes a **Flask web application** where users can upload images and get predictions in real-time.

---

## 🚀 Features

* 🧬 Image-based skin cancer classification
* 🤖 CNN model trained on medical image dataset
* 🌐 Flask-based web interface
* 📊 Model visualization (architecture + performance)
* ⚡ Fast prediction with pre-trained model

---

## 🏗️ Tech Stack

* **Python 3.x**
* **TensorFlow / Keras**
* **Flask**
* **NumPy, OpenCV**
* **HTML, CSS (Frontend)**

---

## 📂 Project Structure

```
Skin-Cancer-Detection/
│── app.py                     # Flask app
│── skin_cancer_detection.py  # Model logic
│── best_model.h5             # Trained CNN model
│── requirements.txt          # Dependencies
│── templates/
│     ├── home.html
│     └── results.html
│── static/ (if any)
│── model.png
│── model_architecture.png
│── tester.jpg
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/Skin-cancer-detection.git
cd Skin-cancer-detection
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
python app.py
```

Open browser:

```
http://127.0.0.1:5000/
```

---

## 🧪 How It Works

1. User uploads a skin image
2. Image is preprocessed (resize, normalization)
3. CNN model predicts class
4. Result is displayed on web interface

---

## 📊 Model Details

* Architecture: Convolutional Neural Network (CNN)
* Input: Skin lesion images
* Output: Classification (Benign / Malignant)
* Framework: TensorFlow / Keras

---

## 📸 Screenshots

(Add screenshots here for better presentation)

---

## ⚠️ Disclaimer

This project is for **educational purposes only**.
It is **not a substitute for professional medical diagnosis**.

---

## 👨‍💻 Author

**Shubham Verma**

* GitHub: https://github.com/shubham-devx

---

## ⭐ Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

