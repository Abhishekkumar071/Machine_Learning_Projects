# IMDB Sentiment Analysis (Simple RNN)

This project implements a **Recurrent Neural Network (RNN)** to perform sentiment analysis on the IMDB Movie Reviews dataset.

---

## 📂 Project Files
- `main.py` → Main script to train the RNN model  
- `embedding.py` → Word embedding setup  
- `simplernn.py` → RNN model architecture  
- `prediction.py` → Script to test/predict sentiment on new reviews  
- `simple_rnn_imdb.h5` → Saved trained model  
- `requirements.txt` → Dependencies list  

---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
Train the model:

bash
Copy code
python main.py
Run predictions:

bash
Copy code
python prediction.py
🏆 Model Info
Architecture: Embedding → SimpleRNN → Dense

Dataset: IMDB Movie Reviews (50,000 reviews)

Accuracy: ~82–85% on validation data

📌 Requirements
Python 3.x

TensorFlow / Keras

NumPy, Matplotlib
