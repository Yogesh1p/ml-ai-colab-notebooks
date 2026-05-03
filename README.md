# ML & AI Colab Notebooks Portfolio

This repository is a curated portfolio of my machine learning, deep learning, and AI-related notebook work. It combines hands-on experiments across generative models, neural networks, NLP/LLMs, computer vision, classical machine learning, reinforcement learning, and representation learning.

The goal of this repo is to showcase practical experimentation, model implementation, and concept exploration using Colab-friendly notebooks.

## Highlights

- Generative modeling with Variational Autoencoders and diffusion processes
- NLP and LLM experimentation with attention analysis and Qwen-based story alignment
- Computer vision work with Siamese networks and image normalization
- Representation learning with PCA, PPCA, LLE, ICA, FA, and EM
- Classical ML studies including linear classifiers, SVM workflows, and LDA/QDA
- Reinforcement learning experimentation on Atari environments
- Foundational ML studies including regularization, RBMs, and XOR networks

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
- [`notebooks/computer-vision/cnn-mnist-classification.ipynb`](notebooks/computer-vision/cnn-mnist-classification.ipynb)
  CNN-based MNIST image classification experiment.

### Representation Learning

- [`notebooks/representation-learning/pca-2d-visualization.ipynb`](notebooks/representation-learning/pca-2d-visualization.ipynb)
  PCA intuition notebook with 2D visualization and dimensionality reduction plots.
- [`notebooks/representation-learning/probabilistic-pca.ipynb`](notebooks/representation-learning/probabilistic-pca.ipynb)
  Probabilistic PCA notebook for latent-variable-based dimensionality reduction.
- [`notebooks/representation-learning/locally-linear-embedding.ipynb`](notebooks/representation-learning/locally-linear-embedding.ipynb)
  Manifold learning notebook demonstrating LLE on a Swiss roll dataset.
- [`notebooks/representation-learning/em-gaussian-mixture.ipynb`](notebooks/representation-learning/em-gaussian-mixture.ipynb)
  Expectation-Maximization workflow on synthetic Gaussian mixture data.
- [`notebooks/representation-learning/independent-component-analysis.ipynb`](notebooks/representation-learning/independent-component-analysis.ipynb)
  ICA notebook separating mixed source signals.
- [`notebooks/representation-learning/factor-analysis.ipynb`](notebooks/representation-learning/factor-analysis.ipynb)
  Factor analysis implementation for latent structure discovery.

### Classical ML

- [`notebooks/classical-ml/linear-classifier-from-scratch.ipynb`](notebooks/classical-ml/linear-classifier-from-scratch.ipynb)
  Linear classifier notebook built from simple TensorFlow components.
- [`notebooks/classical-ml/svm-colab-workflow.ipynb`](notebooks/classical-ml/svm-colab-workflow.ipynb)
  SVM-focused Colab workflow and experimentation notebook.
- [`notebooks/classical-ml/lda-vs-qda-decision-boundaries.ipynb`](notebooks/classical-ml/lda-vs-qda-decision-boundaries.ipynb)
  Comparison of LDA and QDA on synthetic classification data.

### Foundations

- [`notebooks/foundations/restricted-boltzmann-machine.ipynb`](notebooks/foundations/restricted-boltzmann-machine.ipynb)
  Introductory Restricted Boltzmann Machine experiment and sampling intuition.
- [`notebooks/foundations/regularization-bias-variance.ipynb`](notebooks/foundations/regularization-bias-variance.ipynb)
  Notebook exploring overfitting, polynomial regression, and regularization effects.
- [`notebooks/foundations/xor-neural-network.ipynb`](notebooks/foundations/xor-neural-network.ipynb)
  Small neural-network notebook exploring the XOR problem.

### Reinforcement Learning

- [`notebooks/reinforcement-learning/atari-deep-q-learning.ipynb`](notebooks/reinforcement-learning/atari-deep-q-learning.ipynb)
  Atari reinforcement learning notebook using deep Q-learning style components.

## Notes

- Most notebooks were created for experimentation and learning, so some contain Colab-specific install commands.
- Hardware-heavy notebooks may expect GPU access.
- This repository intentionally focuses on ML/AI-related work and excludes draft or unrelated notebooks.
