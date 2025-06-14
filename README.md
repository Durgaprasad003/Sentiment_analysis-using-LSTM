# 🎬 IMDB Sentiment Analysis using LSTM

This project is a deep learning-based Sentiment Analysis model built using **LSTM (Long Short-Term Memory)** networks. It classifies **movie reviews** from the IMDB dataset as either **positive** or **negative**.

---

## 📌 Project Highlights

- 🧠 Built using **LSTM** – a powerful RNN for handling text sequences
- 📊 Uses **Keras Tokenizer** and **Padding** for text preprocessing
- 📈 Evaluates model accuracy and predicts sentiment on new reviews
- ✅ Binary classification with output: `positive` or `negative`

---

## 📁 Dataset

- **Source**: IMDB movie review dataset
- **Data**: 50,000 reviews (25k train, 25k test)
- **Labels**: `positive`, `negative`

---

## 🏗️ Model Architecture

```python
model = Sequential()
model.add(Embedding(input_dim=5000, output_dim=128, input_length=200))
model.add(LSTM(units=128, dropout=0.2, recurrent_dropout=0.2))
model.add(Dense(units=1, activation='sigmoid'))

🛠️ How to Run
Clone this repo
Install required libraries
Run the notebook or Python file
Try your own reviews using predict_sentiment()


📚 Libraries Used
TensorFlow / Keras
scikit-learn
pandas
numpy

🙋‍♂️ Author
Name: Durgaprasad
Goal: Learn English & Deep Learning
💡 Interested in Machine Learning, Python, and New Technologies

