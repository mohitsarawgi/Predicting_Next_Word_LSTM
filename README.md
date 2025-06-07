# Predicting_Next_Word_LSTM
# 🔮 Next Word Prediction using Simple RNN

This project demonstrates how to build a basic language model that can predict the **next word in a sequence** using a Simple Recurrent Neural Network (RNN).

---

## 📚 Project Overview

- **Task**: Predict the next word in a sequence of text
- **Model**: Simple RNN
- **Framework**: TensorFlow / Keras
- **Dataset**: Custom or any plain text corpus (e.g., quotes, books, articles)

---

## 🧠 How It Works

1. **Text Preprocessing**  
   - Load and clean text (lowercasing, removing punctuation)
   - Tokenize the text into words
   - Create input sequences (n-grams) and corresponding next words

2. **Model Architecture**
   - Embedding layer to learn word representations
   - Simple RNN layer to capture temporal dependencies
   - Dense layer with softmax for predicting the next word

3. **Training**
   - Use categorical cross-entropy loss
   - Use softmax activation for multi-class prediction (vocabulary size)

4. **Prediction**
   - User provides a seed text
   - The model predicts the next word based on the learned patterns
