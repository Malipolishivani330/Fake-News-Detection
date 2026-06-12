# 📰 Fake News Detection using Deep Learning (LSTM)

## 📌 Project Overview

Fake News Detection is a machine learning and deep learning application developed to classify news articles as **Fake** or **Real**. The system uses Natural Language Processing (NLP) techniques to preprocess news content and an LSTM (Long Short-Term Memory) neural network to learn patterns from textual data and predict the authenticity of unseen news articles.

The application also provides a simple desktop interface built with Tkinter, allowing users to upload datasets, train the model, visualize performance, and test custom news articles in real time.

---

# 🚀 Problem Statement

With the rapid growth of online media, false information spreads quickly across social platforms and news websites. Manually verifying every article is difficult and time-consuming.

This project aims to automatically identify fake news using deep learning and NLP techniques to improve information reliability.

---

# 🎯 Objectives

* Detect whether a news article is Fake or Real.
* Clean and preprocess raw textual data.
* Convert text into numerical vectors using TF-IDF.
* Train an LSTM-based deep learning model.
* Provide real-time prediction through a user-friendly GUI.
* Save trained models for future predictions without retraining.

---

# 🏗️ System Architecture

User Input
↓
Dataset Upload
↓
Text Preprocessing
↓
Tokenization & Cleaning
↓
Stopword Removal
↓
Lemmatization
↓
TF-IDF Vectorization
↓
Train-Test Split
↓
LSTM Model Training
↓
Model Evaluation
↓
Save Model
↓
Real-Time Prediction

---

# 🛠 Technologies Used

### Programming Language

* Python

### Machine Learning & Deep Learning

* TensorFlow
* Keras
* Scikit-learn

### Natural Language Processing

* NLTK
* TF-IDF Vectorizer
* N-Grams
* WordNet Lemmatizer

### Data Processing

* Pandas
* NumPy

### Visualization

* Matplotlib

### GUI

* Tkinter

### Model Storage

* Pickle
* JSON
* H5 Weights

### Development Tools

* VS Code
* Git
* GitHub

---

# 📂 Project Structure

```
Fake-News-Detection/
│
├── Main.py
├── model/
│   ├── model.json
│   ├── model_weights.h5
│   ├── history.pckl
│   └── model.txt
│
├── TwitterNewsData/
│   ├── news.csv
│   └── testNews.txt
│
├── run.bat
├── requirements.txt
└── README.md
```

---

# 🔄 Workflow

## Step 1: Dataset Loading

The user uploads the news dataset through the Tkinter interface.

## Step 2: Data Preprocessing

The system performs:

* Lowercase conversion
* Punctuation removal
* Tokenization
* Stopword removal
* Lemmatization
* Cleaning invalid words

## Step 3: Feature Extraction

TF-IDF Vectorizer converts cleaned text into numerical feature vectors.

## Step 4: Dataset Splitting

The dataset is divided into training and testing sets.

## Step 5: Model Training

An LSTM neural network is trained on the processed data.

Model architecture:

* LSTM Layer
* Dropout Layer
* LSTM Layer
* Dropout Layer
* Dense Layer
* Output Layer (Softmax)

## Step 6: Model Saving

The trained model is stored using:

* model.json
* model_weights.h5
* history.pckl

This avoids retraining every time.

## Step 7: Prediction

The user uploads new news content.

The system preprocesses it, converts it into TF-IDF vectors, loads the trained model, and predicts whether the news is Fake or Real.

---

# 📊 Features

* Upload custom datasets
* Automatic text preprocessing
* TF-IDF feature extraction
* Deep Learning using LSTM
* Accuracy and Loss visualization
* Model persistence
* Real-time news prediction
* Simple Tkinter graphical interface

---

# 📈 Model Performance

* Dataset preprocessing with NLP pipeline
* TF-IDF vectorization with N-Grams
* LSTM-based sequence learning
* Achieved approximately **70% prediction accuracy** on the available dataset

---

# ▶️ How to Run

## Clone Repository

```bash
git clone https://github.com/Malipolishivani330/Fake-News-Detection.git
cd Fake-News-Detection
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Application

```bash
python Main.py
```

or

Double-click:

```
run.bat
```

---

# 📋 User Guide

1. Launch the application.
2. Click **Upload Fake News Dataset**.
3. Select `news.csv`.
4. Click **Preprocess Dataset**.
5. Click **Run LSTM Algorithm**.
6. View model accuracy.
7. Open **Accuracy & Loss Graph**.
8. Upload test news.
9. View prediction as **Fake** or **Real**.

---

# 💡 Key Learnings

Through this project I gained practical experience in:

* Natural Language Processing
* Text preprocessing techniques
* TF-IDF feature engineering
* Deep Learning with LSTM
* Model serialization and reuse
* GUI development using Tkinter
* Data visualization
* Machine learning workflow implementation
* Git and GitHub project management

---

# 🔮 Future Enhancements

* Deploy as a web application using Flask or Django
* Add BERT or Transformer-based models
* Integrate live news API support
* Improve accuracy with larger datasets
* Enable multilingual fake news detection
* Containerize using Docker
* Deploy on cloud platforms

---

# 👩‍💻 Author

**Shivani Mali**

Python | Machine Learning | Deep Learning | NLP | Data Science

---

## ⭐ If you found this project useful, please give it a star on GitHub.
