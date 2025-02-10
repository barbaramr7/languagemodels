# languagemodels

To deepen my knowledge of Natural Language Processing, I am now working with language models. This project focuses on training language models using NLTK to calculate the probability of words occurring in a text, either alone or in the context of other words. The models are trained on a corpus of text, and the project includes steps for tokenization, n-gram generation, and model training.

Again, a shoutout: as a huge literature nerd, I just had to work with a masterpiece by an amazing Brazilian poet — Carlos Drummond de Andrade.

📝 NLP Language Model Project


📌 Table of Contents

📖 Introduction

✨ Features

⚙️ Installation

🚀 Usage

📒 Notebook Overview

🤝 Contributing

📜 License


📖 Introduction

The goal of this project is to demonstrate how to build and train language models using the NLTK library. The models can predict the probability of a word occurring in a given context, which is useful for various NLP tasks such as text generation, autocompletion, and more.


✨ Features

✅ Tokenization: Splitting text into individual words or sentences.
✅ N-gram Generation: Creating n-grams (bigrams, trigrams, etc.) from the tokenized text.
✅ Language Model Training: Training a Maximum Likelihood Estimation (MLE) model to predict word probabilities.
✅ Text Generation: Generating new text based on the trained model.


⚙️ Installation

To run this project, you need to have Python installed along with the following libraries:

bash
Copy
Edit
pip install nltk
You will also need to download the NLTK data:

python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('stopwords')


🚀 Usage

Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/nlp-language-model.git
cd nlp-language-model
Open the Jupyter notebook:

bash
Copy
Edit
jupyter notebook "2. NLP - language models.ipynb"
Follow the steps in the notebook to:
✅ Load and preprocess the text corpus.
✅ Tokenize the text.
✅ Generate n-grams.
✅ Train the language model.
✅ Generate text and calculate word probabilities.


📒 Notebook Overview

The Jupyter notebook ("2. NLP - language models.ipynb") contains the following sections:

🔹 Loading the Corpus: Loading and preprocessing the text data.
🔹 Tokenization: Splitting the text into sentences and words.
🔹 N-gram Generation: Creating n-grams from the tokenized text.
🔹 Language Model Training: Training the MLE model.
🔹 Text Generation: Generating new text using the trained model.
🔹 Probability Calculation: Calculating the probability of words occurring in the text.


🤝 Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.


📜 License

This project is licensed under the MIT License. See the LICENSE file for more details.
