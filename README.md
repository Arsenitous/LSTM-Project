# Next Word Prediction with LSTM

This project is a web application that predicts the next word in a sequence of text using a Long Short-Term Memory (LSTM) Recurrent Neural Network. It is built using Python, TensorFlow/Keras, and Streamlit.

## 🚀 Live Demo
You can try out the live application here:
👉 **[Try the Next Word Predictor](https://lstm-project-jftczheines5vusgxbfwdh.streamlit.app/)**

## 📖 Overview
The application takes a sequence of words as input from the user and uses a pre-trained LSTM model to predict the most likely next word. LSTMs are particularly well-suited for this task because they are capable of learning order dependence in sequence prediction problems.

## ✨ Features
* **Interactive UI:** Built with Streamlit for a fast and simple user experience.
* **LSTM Neural Network:** Uses a deep learning model trained with TensorFlow and Keras to understand context and predict words.
* **Early Stopping:** The model was trained using early stopping to prevent overfitting and ensure optimal performance.
* **Cached Loading:** The application efficiently caches the model and tokenizer to ensure quick prediction responses without reloading heavy files on every interaction.

## 🛠️ Technologies Used
* **Python**
* **Streamlit** (for the web interface)
* **TensorFlow / Keras** (for building and running the LSTM model)
* **NumPy** (for numerical operations)

## 💻 How to Run Locally

If you want to run this project on your local machine, follow these steps:

1. **Clone the repository** (or download the project files).
2. **Install the required dependencies** (it is recommended to use a virtual environment):
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Streamlit application**:
   ```bash
   streamlit run app.py
   ```
4. **Open your browser** and go to `http://localhost:8501`.

## 📁 Project Structure
* `app.py`: The main Streamlit application script.
* `next_word_lstm.keras`: The saved pre-trained LSTM model.
* `tokenizer.pickle`: The saved tokenizer used to convert text into sequences.
* `requirements.txt`: List of dependencies required to run the project.
* `experiemnts.ipynb`: Jupyter notebook containing the experiments and model training code.
