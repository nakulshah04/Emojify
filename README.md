#  Emojify 😄

This project implements an **Emojifier** that maps input sentences to appropriate emojis, enhancing textual communication by capturing the underlying sentiment or context. Inspired by DeepLearning.AI's Deep Learning Specialization (Course 5: Sequence Models), it demonstrates practical applications of word embeddings and sequence models in natural language processing.&#8203;:contentReference[oaicite:2]{index=2}

## 📌 Project Overview

The Emojifier processes input sentences and predicts the most suitable emoji to accompany the text. For example:

- Input: `"I love you"`
- Output: `"I love you ❤️"`

## 📁 Required Files

The project relies on the pre-trained GloVe word vectors (`glove.6B.50d.txt`), which are not included in the repository due to size constraints.

- **Download GloVe Vectors**: [glove.6B.50d.txt](https://nlp.stanford.edu/data/glove.6B.zip)

After downloading, extract the file and place `glove.6B.50d.txt` into the `data/` directory.

## 🚀 How to Run

1. **Install Dependencies**:
Ensure you have the required Python packages installed:
   ```bash
   pip install numpy pandas keras tensorflow emoji matplotlib

2. **Prepare Data**:
Ensure the data/ directory contains:
* train_emoji.csv
* test_emoji.csv
* glove.6B.50d.txt

3. **Run the Notebook**:
Convert the py script into an .ipynb file and then open and execute it in Jupyter Notebook or any compatible environment.
