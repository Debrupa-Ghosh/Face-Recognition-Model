# 🧠 Face Recognition using Deep Learning Models

## 📌 Project Overview

This project implements and compares three popular deep learning models for face recognition: **VGGFace, FaceNet, and ArcFace**.
The goal is to evaluate their performance based on inference time and efficiency using a custom facial image dataset.

---

## 🚀 Features

* 🔍 Face detection and alignment using **RetinaFace**
* 🤖 Face recognition using **DeepFace (TensorFlow/Keras backend)**
* ⚡ Performance comparison of multiple models
* 📊 Real-time face matching using OpenCV
* 📈 Experimental analysis based on inference time

---

## 🧩 Models Used

* **VGGFace** – CNN-based baseline model
* **FaceNet** – Uses triplet loss for embedding learning
* **ArcFace** – Advanced model with angular margin loss for high accuracy

---

## 📊 Results

| Model   | Average Inference Time (sec) |
| ------- | ---------------------------- |
| FaceNet | 11.87 sec                    |
| ArcFace | 12.10 sec                    |
| VGGFace | 12.60 sec                    |

### 🔎 Observations

* ⚡ **FaceNet** is the fastest model → suitable for real-time applications
* 🎯 **ArcFace** provides the most accurate and robust results
* ⚖️ **VGGFace** offers balanced performance but is relatively slower

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* PIL
* DeepFace
* RetinaFace

---

## 📁 Dataset

* Custom facial image dataset
* Test case used for matching (e.g., celebrity images)

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook
```

4. Execute the notebook to test face recognition models

---

## 🔮 Future Improvements

* Improve inference speed using model optimization
* Deploy as a web app using Streamlit or Flask
* Use larger and more diverse datasets
* Optimize for real-time edge devices

---

## 🙌 Acknowledgements

* DeepFace Library
* OpenCV Community
* TensorFlow/Keras

---

## 👨‍💻 Author

**Debrupa Ghosh**
B.Tech CSE (Data Science)
Feel free to connect and collaborate!
