# BERT Sentiment Analysis

This was project was part of my coursework for ECE 570 with Prof. Inouye. I created a sentiment analysis model with BERT to use on the [50k IMDB movie reviews dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews). I used [transfomers](https://huggingface.co/docs/transformers/index) and [PyTorch](https://pytorch.org) to do this.

### Reproduce This Project

1. Download the imdb dataset listed above, and put it at the root of the project as `imdb.csb`
1. Load this project into Google Drive, as it was written to only work with Google Colab.
1. Run `build-dataset.ipynb` first to prepare the input
1. Run `model.ipynb` to train the model. It will save the most accurate model to the root of the project as `model.pt`
