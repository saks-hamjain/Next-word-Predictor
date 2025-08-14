🧠 Next-word Predictor
A deep learning model built with LSTM (Long Short-Term Memory) to predict the next word in a sequence. This project demonstrates how recurrent neural networks can be trained on text data to generate context-aware predictions.

📌 Project Overview
Model Type: LSTM-based neural network

Goal: Predict the next word given a sequence of words

Dataset: Custom text corpus (nextword_dataset.txt)

Notebook: All code and training steps are documented in nextword.ipynb

📁 Repository Structure
Code
Next-word-Predictor/
├── nextword.ipynb         # Jupyter notebook with model code and training
├── nextword_dataset.txt   # Text corpus used for training
├── README.md              # Project documentation
└── LICENSE                # MIT License
🚀 How to Run
Clone the repository:

bash
git clone https://github.com/saks-hamjain/Next-word-Predictor.git
cd Next-word-Predictor
Open the notebook:

bash
jupyter notebook nextword.ipynb
Run the cells to:

Preprocess the dataset

Tokenize and vectorize text

Train the LSTM model

Generate predictions

🧪 Sample Output
Input: "The weather is"

Prediction: "nice"

📚 Dependencies
TensorFlow / Keras

NumPy

Pandas

scikit-learn

Jupyter Notebook

You can install them via:

bash
pip install -r requirements.txt
📄 License
This project is licensed under the MIT License.
