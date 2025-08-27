# 🎬 Movie Review Sentiment Analysis (RNN)

This project implements a **Sentiment Analysis model** using a **Simple RNN** in TensorFlow/Keras.  
It predicts whether a movie review is **positive** or **negative**.

## 📂 Project Structure
---

├── simple-rnn.ipynb # Model building and training
├── prediction.ipynb # Notebook for testing predictions
├── app.py # Streamlit app for user input
├── simple_rnn_imdb.h5 # Trained RNN model
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── .gitignore # Ignored files (e.g., myenv)

📊 Dataset

This project uses the IMDB movie reviews dataset available in keras.datasets.imdb.
It contains 50,000 reviews, split equally into training and testing sets.

🧠 Model
Embedding Layer → Convert words into dense vectors.
SimpleRNN Layer → Capture sequential information.
Dense Layers → Final classification (positive / negative).

📈 Results

Training Accuracy: ~86–96% (varies by run)
Validation Accuracy: ~75–77%

⚠️ Note: Due to random initialization, results can slightly differ per run.

🎯 Usage
▶️ Run Streamlit App

Start the app:
streamlit run app.py

Open browser at:
http://localhost:8501
Enter a review (e.g. "This movie was fantastic!") → get sentiment prediction.

Example:
Input:
The film was boring and a complete waste of time.

Output:
Sentiment: Negative

Prediction Score: 0.0000001637


