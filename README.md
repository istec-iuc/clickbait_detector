# Clickbait Detection with ANN, RNN, and LSTM  

This project explores different deep learning models (ANN, RNN, and LSTM) for detecting **clickbait headlines**.  

## 📂 Dataset  
The dataset used comes from Kaggle:  
[Clickbait Dataset](https://www.kaggle.com/datasets/amananandrai/clickbait-dataset)  
It contains news headlines labeled as:  
- **1** → Clickbait  
- **0** → Non-clickbait  

## ⚙️ Models  
I implemented and trained three models using **Keras (TensorFlow)**:  
- Artificial Neural Network (ANN)  
- Recurrent Neural Network (RNN)  
- Long Short-Term Memory Network (LSTM)  

## 📊 Results  
The models were trained and tested on the dataset. Final accuracies:  
- **ANN:** 0.9598  
- **RNN:** 0.9267  
- **LSTM:** 0.9475  

## 🚀 How to Run  
1. Clone this repository:  
   ```bash
   git clone https://github.com/istec-iuc/clickbait-detector.git
   cd clickbait-detector
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook to train the models

## 📌 Notes
- ANN, RNN, and LSTM were compared on the same dataset to evaluate their performance.
- Preprocessing included text cleaning, tokenization, and padding before feeding data into the models.
