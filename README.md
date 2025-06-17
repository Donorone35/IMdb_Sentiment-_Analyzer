# 🎬**IMDB Sentiment Analyzer: Classifying Movie Reviews**

This repository contains a **Bidirectional LSTM-based deep learning model** designed to classify **IMDB movie reviews** as **positive or negative**. It processes user reviews, trains on labeled data, and evaluates model performance through visualizations and metrics.

## **Key Features**
- **Data Preprocessing:** Tokenizes reviews, removes noise, and converts text into padded sequences.
- **Model Architecture:** Uses **Bidirectional LSTM** with dropout and L2 regularization for context-aware sentiment learning.
- **Performance Evaluation:** Tracks **accuracy, loss, confusion matrix, and classification report**.
- **Prediction Function:** Accepts custom user reviews and returns real-time sentiment prediction.
- **Visualization:** Includes **accuracy/loss graphs** and a **confusion matrix heatmap** for easy interpretation.

## **Technology Used**
### **Languages & Libraries**
- **Python**
- **TensorFlow / Keras** (Model building and training)
- **Pandas & NumPy** (Data Handling)
- **Matplotlib & Seaborn** (Data Visualization)
- **Scikit-learn** (Evaluation metrics)

### **APIs & Tools**
- **Kaggle API** (Dataset download)
- **Google Colab / Jupyter Notebook** (Training & experimentation)

## 📊**Model Performance**
- **Training Accuracy:** ~90%
- **Validation Accuracy:** ~88%  
- **Loss Function:** Binary Crossentropy (from logits)
- **Confusion Matrix:** Displays true vs predicted labels.
- **Classification Report:** Includes precision, recall, and F1-score.

## 📈**Visualization**
The project includes:

- 🔹**Accuracy Graph:** Comparison of training vs validation accuracy.  
  ![Accuracy Plot](accuracy_plot.png)

- 🔹**Loss Graph:** Training and validation loss over epochs.  
  ![Loss Plot](loss_plot.png)

- 🔹**Confusion Matrix Heatmap:** Detailed analysis of predictions.  
  ![Confusion Matrix](confusion_matrix.png)

## **Installation & Usage**
### **Installation**
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/imdb-sentiment-analyzer.git
   cd imdb-sentiment-analyzer
