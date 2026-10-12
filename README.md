# Detecting-Spam-Emails

Overview

SpamShield is a deep learning project that classifies email messages into two categories: Spam and Ham (Not Spam) using Natural Language Processing (NLP) and Long Short-Term Memory (LSTM) networks.

Technologies Used

Programming Language: Python

Data Processing: Pandas, NumPy

NLP: NLTK, Keras Tokenizer

Deep Learning: TensorFlow, Keras, LSTM

Visualization: Matplotlib, Seaborn, WordCloud

Dataset

Dataset: Spam/Ham Email Dataset

Total Samples: 5,171

Classification: Binary (Spam / Ham)

Dataset Source: [Add original dataset link and license]

Project Workflow

Load and explore the email dataset.

Handle class imbalance using downsampling.

Clean text by removing punctuation and stopwords.

Convert text into integer sequences using tokenization.

Apply padding to standardize sequence lengths.

Build an LSTM-based deep learning model.

Train and evaluate the model.

Model Architecture

Embedding Layer: Converts token IDs into dense word vectors.

LSTM Layer: Learns sequential patterns from email text.

Dense Layer: Uses ReLU activation.

Output Layer: Uses sigmoid activation for binary classification.

Model Performance

Metric

Result

Test Accuracy

97.00%

Test Loss

0.1202

Optimizer

Adam

Loss Function

Binary Cross-Entropy

Note: These are preliminary results reproduced in Google Colab. The original notebook uses the test data for validation during training, so a separate held-out test evaluation is needed to confirm generalization performance.

How to Run

Download Detecting_Spam_Emails.ipynb.

Open the notebook in Google Colab.

Upload spam_ham_dataset.csv.

Update the dataset path if necessary.

Install any missing dependencies.

Execute all cells sequentially.

Project Status

Notebook experiment completed and executed successfully in Google Colab.

Future Improvements

Evaluate precision, recall, F1-score, and confusion matrix.

Use separate training, validation, and test sets.

Compare LSTM with TF-IDF and Logistic Regression.

Integrate the trained model with FastAPI and React.

Deploy the application.

Learning Outcomes

Practiced NLP preprocessing and text tokenization.

Explored embedding layers and LSTM networks.

Gained experience training and evaluating binary classification models.

Learned to execute deep learning experiments using Google Colab.
