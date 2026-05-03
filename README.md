# ML & AI Colab Notebooks Portfolio

This repository is a curated portfolio of my machine learning, deep learning, and AI-related notebook work. It combines hands-on experiments across generative models, neural networks, NLP/LLMs, computer vision, and representation learning.

The goal of this repo is to showcase practical experimentation, model implementation, and concept exploration using Colab-friendly notebooks.

## Highlights

- Generative modeling with Variational Autoencoders and diffusion processes
- NLP and LLM experimentation with attention analysis and Qwen-based story alignment
- Computer vision work with Siamese networks and image normalization
- Representation learning with PPCA and Locally Linear Embedding
- Foundational ML studies including regularization and RBMs

## Repository Structure

### Generative Models

- [`notebooks/generative-models/variational-autoencoder-mnist.ipynb`](notebooks/generative-models/variational-autoencoder-mnist.ipynb)
  PyTorch implementation of a Variational Autoencoder trained on MNIST.
- [`notebooks/generative-models/diffusion-mean-covariance.ipynb`](notebooks/generative-models/diffusion-mean-covariance.ipynb)
  Notebook exploring how diffusion changes the mean and covariance of a distribution over time.

### NLP / LLM

- [`notebooks/nlp-llm/attention-sentence-similarity.ipynb`](notebooks/nlp-llm/attention-sentence-similarity.ipynb)
  Sentence representation experiment using transformer hidden states and cosine similarity.
- [`notebooks/nlp-llm/qwen-story-alignment-4bit.ipynb`](notebooks/nlp-llm/qwen-story-alignment-4bit.ipynb)
  Qwen 2.5 7B 4-bit workflow for story alignment experiments.
- [`notebooks/nlp-llm/qwen-story-alignment-fp16.ipynb`](notebooks/nlp-llm/qwen-story-alignment-fp16.ipynb)
  Qwen 2.5 1.5B fp16 notebook for alignment-style prompting and generation analysis.

### Computer Vision

- [`notebooks/computer-vision/siamese-mnist-similarity.ipynb`](notebooks/computer-vision/siamese-mnist-similarity.ipynb)
  Siamese network experiment for similarity learning on image pairs.
- [`notebooks/computer-vision/global-local-contrast-normalization.ipynb`](notebooks/computer-vision/global-local-contrast-normalization.ipynb)
  Visual preprocessing notebook covering global and local contrast normalization.

### Representation Learning

- [`notebooks/representation-learning/probabilistic-pca.ipynb`](notebooks/representation-learning/probabilistic-pca.ipynb)
  Probabilistic PCA notebook for latent-variable-based dimensionality reduction.
- [`notebooks/representation-learning/locally-linear-embedding.ipynb`](notebooks/representation-learning/locally-linear-embedding.ipynb)
  Manifold learning notebook demonstrating LLE on a Swiss roll dataset.

### Foundations

- [`notebooks/foundations/restricted-boltzmann-machine.ipynb`](notebooks/foundations/restricted-boltzmann-machine.ipynb)
  Introductory Restricted Boltzmann Machine experiment and sampling intuition.
- [`notebooks/foundations/regularization-bias-variance.ipynb`](notebooks/foundations/regularization-bias-variance.ipynb)
  Notebook exploring overfitting, polynomial regression, and regularization effects.

## Notes

- Most notebooks were created for experimentation and learning, so some contain Colab-specific install commands.
- Hardware-heavy notebooks may expect GPU access.
- This repository intentionally focuses on ML/AI-related work and excludes draft or unrelated notebooks.
