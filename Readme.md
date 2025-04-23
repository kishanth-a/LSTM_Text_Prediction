# 🧠 LSTM Text Prediction

## 📖 Project Description

This project implements a **Next Word Prediction** model using **Long Short-Term Memory (LSTM) / Gated Recurrent Unit (GRU)** neural networks. Trained on Shakespeare's *Hamlet*, the model predicts the next word in a given text sequence, demonstrating applications in text autocompletion and language modeling.

---

## 🛠️ Tech Stack

**Programming Language:**
- Python

**Libraries & Frameworks:**
- TensorFlow / Keras
- NumPy
- Pandas

**Tools:**
- Jupyter Notebook
- Streamlit (for deployment)

**Dataset:**
- `hamlet.txt` (Shakespeare's *Hamlet*)

---

## ✨ Features

- **Data Preprocessing:** Tokenization and sequence generation from raw text.
- **Model Architecture:** Embedding layer followed by LSTM layers and Dense output.
- **Training Enhancements:** Early stopping to prevent overfitting.
- **Deployment:** Streamlit application for interactive predictions.

---

## ✅ Installation Requirements

Make sure you have Python installed. Then install the required packages using the command below:

```bash
pip install -r requirements.txt
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/kishanth-a/LSTM_Text_Prediction.git
cd LSTM_Text_Prediction
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Application

```bash
python app.py
```

Once the server is running, open your browser and navigate to:

```
http://localhost:5000/
```

---

## 📸 Screenshots or Demo

*Include screenshots of the application interface or a link to a live demo here.*

---

## 📁 Project Structure

```plaintext
LSTM_Text_Prediction/
├── app.py
├── experiemnts.ipynb
├── hamlet.txt
├── next_word_lstm.h5
├── next_word_lstm_model_with_early_stopping.h5
├── requirements.txt
├── tokenizer.pickle
└── venv/
```

- `app.py`: Flask application for deployment.  
- `experiemnts.ipynb`: Jupyter Notebook with model training and evaluation.  
- `hamlet.txt`: Dataset used for training.  
- `next_word_lstm.h5`: Trained model file.  
- `next_word_lstm_model_with_early_stopping.h5`: Trained model with early stopping.  
- `requirements.txt`: List of dependencies.  
- `tokenizer.pickle`: Saved tokenizer object.  
- `venv/`: Python virtual environment directory.

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

## 📬 Contact / Links

- **GitHub:** [kishanth-a](https://github.com/kishanth-a)
- **LinkedIn:** [Kishanth A](https://www.linkedin.com/in/kishanth-arunachalam/)
```
