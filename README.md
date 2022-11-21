# BERT Sentiment Analysis

This was project was part of my coursework for ECE 570 with Prof. Inouye.
I created a sentiment analysis model with BERT to use on the [IMDB movie reviews dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews), which are 50k reviews labeled with positive or negative sentiment.
I used [transfomers](https://huggingface.co/docs/transformers/index) and [PyTorch](https://pytorch.org) to do this.
All the code in this project is my own.

### Reproduce This Project

1. Download the IMDB dataset listed above, and put it at the root of the project as `imdb.csb`
1. Load this project into Google Drive, as it was written to only work with Google Colab
1. Run `build-dataset.ipynb` first to prepare the input
1. Run `model.ipynb` to train the model. It will save the most accurate model to the root of the project as `model.pt`
