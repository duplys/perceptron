# Summary 🤖

This repository contains Jupyter notebooks illustrating few basics of machine learning, primarily the basics of artificial neural networks. I created it to explain working principles behind machine learning to technical leadership at the company I work for.

The learning journey starts with a simple perceptron introduced in 1957, progresses through the development of multi-layer perceptrons and recurrent neural networks (RNNs) for sequence-to-sequence tasks, and finishes with modern-day transformer architecture and large language models (LLMs). For explanations of sequence-to-sequence models, RNNs, and transformers, I primarily reference the [excellent NLP course by Lena Voita](https://lena-voita.github.io/nlp_course.html).

The following table of contents is helpful if you want to navigate the material in logical order.

## Table of contents

* [Perceptron](notebooks/perceptron.ipynb)
* [Multi-layer Perceptron (MLP)](notebooks/multi-layer-perceptron.ipynb)
  * [Backpropagation](notebooks/backpropagation.ipynb)
  * [Training an MLP](notebooks/mlp-training.ipynb)
    * [Gradient](notebooks/gradient.ipynb)
  * [MNIST example](notebooks/mnist.ipynb)
* [Sequence-to-sequence tasks](https://lena-voita.github.io/nlp_course/seq2seq_and_attention.html#seq2seq_basics_intro)
* [Encoder-decoder framework](https://lena-voita.github.io/nlp_course/seq2seq_and_attention.html#enc_dec_framework)
* [Recurring Neural Networks (RNNs)](https://lena-voita.github.io/nlp_course/seq2seq_and_attention.html#seq2seq_simple_rnn)
  * [RNN example](notebooks/rnn.ipynb)
* [Attention](https://lena-voita.github.io/nlp_course/seq2seq_and_attention.html#attention)
* [Self-Attention](https://lena-voita.github.io/nlp_course/seq2seq_and_attention.html#self_attention)
* 🚧 Positional Encoding
* 🚧 Normalization
* [Transformer architecture](https://lena-voita.github.io/nlp_course/seq2seq_and_attention.html#transformer_model_architecture)
  * [Foundation Models](https://hai.stanford.edu/news/what-foundation-model-explainer-non-experts)
  * 🚧 Generative Pre-trained Transformer
* Use cases for generative AI
  * [Retrieval-Augmented Generation (RAG)](https://qdrant.tech/articles/what-is-rag-in-ai/)
  * [Image segmentation](https://segment-anything.com/)
* Hands-on 
  * 🚧 Hands-on: GitHub Copilot
  * 🚧 Hands-on: Using LLMs
* Business impact
  * [HAI AI Index Report](https://hai.stanford.edu/research/ai-index-report)

## Running the Jupyter notebooks

The [requirements.txt](requirements.txt) file in the root of this repository lists all Python packages and their corresponding versions installed in my Python virtual environment (the file was obtained by `pip freeze > requirements.txt`).