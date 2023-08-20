# Emoji Prediction Using LSTM

This project demonstrates how to use an LSTM-based model to predict emojis from text input. It uses pre-trained word embeddings and TensorFlow/Keras for building and training the model.

## Getting Started

1. **Clone the Repository:** Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Akanksham12/emoji-prediction-lstm.git
   cd emoji-prediction-lstm

2. **Install Dependencies:** Make sure you have the required dependencies installed. You can install them using pip:  
   ```bash 
   pip install pandas numpy emoji tensorflow keras matplotlib seaborn

3. **Dataset and Pre-trained Embeddings:** Download the following files and place them in the project directory:  
   train_emoji.csv: Training data with text and emoji labels.  
   test_emoji.csv: Test data with text and emoji labels.  
   glove.6B.50d.txt: Pre-trained word embeddings for text representation.  Downloading link: [glove.6B.50d.txt](https://www.kaggle.com/datasets/watts2/glove6b50dtxt)
  
4. **Project Structure:**  
   train_emoji.csv: Training data file.  
   test_emoji.csv: Test data file.  
   glove.6B.50d.txt: Pre-trained word embeddings file.  
   Emoji prediction Using Machine Learning.ipynb: Jupyter Notebook containing the code for the project.

5. **Usage**  
   Open the emoji_prediction.ipynb notebook using Jupyter Notebook or Jupyter Lab.  
   Run each cell in the notebook sequentially to load and preprocess the data, create the LSTM model, and train it.  
   After training, you'll see accuracy and loss graphs to evaluate the model's performance.  
   The model's performance on the test data will be evaluated and displayed.  
   The confusion matrix will provide insights into the model's classification performance.  
   The notebook will also show examples of predicted emojis compared to the actual emojis for the test data.  