
# 🎥 Violence Detection Using Deep Learning

An AI-powered video analysis system designed to classify video activities into **Violence** and **Non-Violence** categories using Python and Computer Vision.

## 📌 Project Overview

Violence Detection is a deep learning-based project that analyses video streams and identifies activities classified as violent or non-violent.

The system uses computer vision and deep learning techniques to process video frames and generate predictions. It aims to demonstrate how AI can support video monitoring and automated activity analysis.

## 🎯 Objectives

- Detect violent and non-violent activities from video input.
- Apply deep learning techniques for video classification.
- Analyse video frames using computer vision.
- Develop an AI-based video monitoring application.
- Explore real-world applications of intelligent video analysis.

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming |
| OpenCV | Video processing |
| TensorFlow / Keras | Deep learning |
| CNN | Spatial feature extraction (if implemented) |
| LSTM | Temporal sequence analysis (if implemented) |
| Streamlit | Web application (if implemented) |

## 🧠 System Workflow

1. Upload or provide video input.
2. Extract video frames.
3. Preprocess frames for model input.
4. Analyse the video using the trained model.
5. Classify the activity as Violence or Non-Violence.
6. Display the prediction.

## 📂 Project Structure

```text
Violece-Detection/
│
├── streamlit_violence_detection_advanced.py
├── README.md
├── requirements.txt
└── screenshots/
```

*Update the structure according to the actual files in your repository.*

## 🚀 Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/Praveena2097/Violece-Detection.git
```

### 2. Navigate to the project

```bash
cd Violece-Detection
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Download the trained model

The trained Keras model is hosted separately on Hugging Face because of its large file size.

🔗 **Hugging Face Model:**

https://huggingface.co/YOUR_USERNAME/YOUR_MODEL_NAME

Download the model and place it in the path expected by the application.

### 5. Run the application

```bash
streamlit run streamlit_violence_detection_advanced.py
```

## 🤖 Trained Model

- Model Format: `.keras`
- Model Hosting: Hugging Face
- Model Download: [Access Trained Model](https://huggingface.co/YOUR_USERNAME/YOUR_MODEL_NAME)

## 📊 Output Classes

- **Violence:** Activity classified by the model as violence.
- **Non-Violence:** Activity classified by the model as non-violence.

## 🔮 Future Enhancements

- Improve classification performance.
- Expand testing with diverse video samples.
- Improve real-time video processing.
- Enhance prediction reporting.
- Add a human-review workflow for flagged results.

## 👩‍💻 Developed By

**Praveena R**

B.Tech – Artificial Intelligence and Data Science

GitHub: https://github.com/Praveena2097

Project Repository:
https://github.com/Praveena2097/Violece-Detection

## ⚠️ Disclaimer

This project is developed for academic and educational purposes. Model predictions may be incorrect and should not be treated as definitive evidence of an incident. Human review and appropriate privacy safeguards are essential.
