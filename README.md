## Game of Thrones Text Analysis with Word2Vec

### Overview
This project involves training a machine learning model on text data from the "Game of Thrones" series. The model uses Word2Vec for vectorization to capture the semantic relationships between words based on their context within the text. This project provides insights into the narrative structure and character interactions within the series.

### Project Structure
- **data/**: Contains the text files from the "Game of Thrones" series used for training.
- **notebooks/**: The Jupyter notebook used for preprocessing, model training, and evaluation (`game-of-thrones-word2vec.ipynb`).
- **models/**: Directory where trained Word2Vec models and word vectors can be saved.
- **src/**: (Optional) Source code for additional preprocessing, training, and evaluation scripts.
- **README.md**: This file, which provides an overview of the project and instructions for use.

### Dependencies
To run this project, you will need the following dependencies:
- Python 3.x
- numpy
- pandas
- nltk
- gensim

You can install the required packages using the following command:
```bash
pip install numpy pandas nltk gensim
