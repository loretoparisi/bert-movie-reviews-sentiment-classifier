# bert-movie-reviews-sentiment-classifier
Build a Movie Reviews Sentiment Classifier with Google's [BERT](https://github.com/google-research/bert) Language Model

# What's this?
This is a example of building a Movie Reviews Sentiment classifier with Google's BERT (Bidirectional Encoder Representations from Transformers) NLP Language Model.

# Requirements
This code requires `scikit-learn`, `tensorflow-gpu`, `tensorflow-hub`, `bert-tensorflow`. The code is compatibile with TF <= 1.1.50 and latest available BERT model on Tensorflow Hub. To use the cpu version please install `tensorflow==1.15.0`.

```bash
pip install scikit-learn
pip install tensorflow-gpu==1.15.0
pip install tensorflow-hub
pip install bert-tensorflow
```

# How to Run
To run this project you can
- Open the IPython Notebook `src/bert_sentiment_classifier-local.ipynb` in your Juypter Notebook or 

- Import `src/bert_sentiment_classifier.ipynb`  into [Google's Colab](https://colab.research.google.com) with GPU backend.

- Open the Pyhon Interactive `src/bert_sentiment_classifier.py` in VisualStudio Code. See [here](https://code.visualstudio.com/docs/python/jupyter-support) how it works with Jupyter Notebooks and Code.

