
# 🎥 Violence Detection Using Deep Learning

An AI-powered video analysis system designed to identify and classify activities into **Violence** and **Non-Violence** categories using Python, Computer Vision, and Deep Learning.

## 📌 Project Overview

Violence Detection is an AI-based video analysis project that aims to identify violent activities from video streams.

The system processes video input, analyses visual patterns, and generates predictions using a trained deep learning model.

The project demonstrates the application of Artificial Intelligence and Computer Vision in automated video monitoring and activity classification.

## 🎯 Objectives

- Develop an AI-based system to identify violent activities in videos.
- Classify video content into Violence and Non-Violence categories.
- Apply computer vision techniques for video analysis.
- Use deep learning for automated activity classification.
- Explore practical applications of AI in intelligent video monitoring.

## ⚙️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| OpenCV | Video processing and frame extraction |
| TensorFlow / Keras | Deep learning model |
| CNN | Spatial feature extraction, if implemented |
| LSTM | Temporal pattern analysis, if implemented |
| Streamlit | Web application interface, if implemented |

## 🧠 System Workflow

1. **Video Input:** Provide a video for analysis.
2. **Frame Extraction:** Extract frames from the video.
3. **Preprocessing:** Prepare frames for model input.
4. **Feature Analysis:** Analyse visual and temporal patterns.
5. **Classification:** Predict Violence or Non-Violence.
6. **Result Display:** Display the prediction through the application interface.

## 🏗️ System Architecture

The high-level workflow consists of:

```text
       Video Input
            |
            v
     Frame Extraction
            |
            v
       Preprocessing
            |
            v
    Deep Learning Model
            |
            v
      Classification
            |
       +----+----+
       |         |
       v         v
   Violence  Non-Violence
       |         |
       +----+----+
            |
            v
      Display Result
```

## 📂 Project Structure

```text
Violece-Detection/
│
├── streamlit_violence_detection_advanced.py
├── README.md
├── requirements.txt
└── screenshots/
```

*Note: Update this structure to match the actual files in your repository.*

## 🚀 Installation and Execution

### 1. Clone the Repository

```bash
git clone https://github.com/Praveena2097/Violece-Detection.git
```

### 2. Navigate to the Project Directory

```bash
cd Violece-Detection
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

If you do not have a requirements.txt file, install the packages required by your application.

For example:

```bash
pip install opencv-python tensorflow streamlit
```

### 4. Download the Trained Model

The trained Keras model is hosted separately on Hugging Face because of its large file size.

**Hugging Face Model Repository:**

https://huggingface.co/Threatwatch38/Violecedetection-model

Download the model and place it in the location expected by the application.

### 5. Run the Application

If your project uses Streamlit:

```bash
streamlit run streamlit_violence_detection_advanced.py
```

## 🤖 Trained Deep Learning Model

The trained model is hosted on Hugging Face for easy access and download.

| Details | Information |
|---|---|
| Model Name | Violecedetection-model |
| Model Format | Keras (.keras) |
| Model Hosting | Hugging Face |
| Repository Owner | Threatwatch38 |

### 🔗 Access the Model

[Click Here to View and Download the Trained Model](https://huggingface.co/Threatwatch38/Violecedetection-model)

## 📊 Output Classes

The system is designed to classify video input into two categories:

- **Violence:** Video activity classified by the model as violent.
- **Non-Violence:** Video activity classified by the model as non-violent.

## 📸 Application Screenshots

Screenshots of the application interface and prediction results can be added here.

Example:

```markdown
![Application Interface](screenshots/app-interface.png)

![Prediction Output](screenshots/prediction-output.png)
```

## 🔮 Future Enhancements

- Improve model performance and classification accuracy.
- Evaluate the model using precision, recall, F1-score, and accuracy.
- Improve real-time video processing.
- Test with more diverse and appropriately labelled video samples.
- Enhance the user interface and prediction reporting.
- Introduce a human-review workflow for flagged results.

## 👩‍💻 Developed By

**Praveena R**

B.Tech – Artificial Intelligence and Data Science

GitHub Profile:
https://github.com/Praveena2097

### Project Links

- GitHub Repository: https://github.com/Praveena2097/Violece-Detection
- Hugging Face Model: https://huggingface.co/Threatwatch38/Violecedetection-model

## ⚠️ Disclaimer

This project is developed for academic and educational purposes.

The system is intended to support video analysis and human review. Model predictions may be incorrect and should not be treated as definitive evidence of an incident.

Appropriate privacy, consent, and responsible-use safeguards should always be followed.
