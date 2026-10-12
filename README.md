# SpamShield – Detecting-Spam-Emails

## About
SpamShield is a deep learning project that classifies emails as Spam or Ham (Not Spam) using Natural Language Processing (NLP) and an LSTM neural network.

## Technologies Used
- Python
- Pandas and NumPy
- NLTK
- TensorFlow and Keras
- LSTM
- Matplotlib, Seaborn and WordCloud

## Workflow
1. Load and explore the email dataset.
2. Clean the email text.
3. Remove punctuation and stopwords.
4. Convert text into numerical sequences using tokenization.
5. Apply padding to standardize sequence lengths.
6. Train an LSTM-based classification model.
7. Evaluate model performance.

## Model Architecture
Embedding → LSTM → Dense (ReLU) → Dense (Sigmoid)

## Results
- Test Accuracy: 97%
- Test Loss: 0.1202

Note: These are preliminary results from the Google Colab experiment. Further evaluation using separate validation and test sets is required.

## Dataset
- File: `spam_ham_dataset.csv`
- Contains labeled spam and ham email messages.
- Add the original dataset source and license before publishing.

## How to Run
1. Open `Detecting_Spam_Emails.ipynb` in Google Colab.
2. Upload `spam_ham_dataset.csv`.
3. Run the notebook cells in order.

## Future Improvements
- Evaluate precision, recall and F1-score.
- Generate a confusion matrix.
- Compare LSTM with Logistic Regression.
- Build a web application using React and FastAPI.

## Project Status
Notebook experiment completed and executed in Google Colab.
