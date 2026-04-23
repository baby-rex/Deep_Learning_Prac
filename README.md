# Deep Learning Practice

This repository contains a structured set of hands-on experiments developed while learning and implementing deep learning concepts using PyTorch. It progresses from fundamental tensor operations to building, training, and optimizing neural networks, including convolutional architectures and transfer learning techniques.

The work emphasizes understanding internal mechanics, implementing training pipelines, and experimenting with model performance improvements.

---

## Repository Structure

```id="g3l8cz"
.
├── fundamentals/
│   ├── 1_Basic_Pytorch_Tensors.ipynb
│   ├── 2_pytorch_autograd.ipynb
│   ├── 3_pytorch_training_pipeline.ipynb
│
├── core_modules/
│   ├── 4.5_pytorch_nn_module.ipynb
│   ├── 5_pytorch_training_pipeline_using_nn_module.ipynb
│   ├── 6_pytorch_training_pipelinedataset_dataloader.ipynb
│
├── experiments/
│   ├── 7_Ann_fmnist_gpu.ipynb
│   ├── 8_ANNfmnist_optimized_optuna.ipynb
│   ├── 9_CNN_fmnist.ipynb
│   ├── 9.5_CNN_fmnist_optuna.ipynb
│   ├── 10_Transfer_learning_fmnist.ipynb
```

---

## Overview

### Fundamentals

Covers the foundational building blocks of PyTorch:

* Tensor operations and memory handling
* Automatic differentiation (autograd)
* Manual implementation of training loops

---

### Core Modules

Focuses on writing scalable and maintainable deep learning code:

* Model construction using `nn.Module`
* Structured training pipelines
* Data handling with `Dataset` and `DataLoader`

---

### Experiments on Fashion-MNIST

#### Artificial Neural Networks (ANN)

* Implementation of fully connected networks
* GPU-based training
* Performance evaluation

#### Hyperparameter Optimization

* Use of Optuna for tuning model parameters
* Improving model performance through systematic search

#### Convolutional Neural Networks (CNN)

* Implementation of CNN architectures
* Comparison with ANN performance
* Feature extraction and spatial learning

#### CNN Optimization

* Hyperparameter tuning applied to CNN models
* Performance improvements and observations

#### Transfer Learning

* Applying pretrained models to Fashion-MNIST
* Understanding feature reuse and adaptation

---

## Technologies Used

* Python
* PyTorch
* Optuna
* Jupyter Notebook

---

## Key Learnings

* End-to-end understanding of deep learning workflows
* Differences between ANN and CNN performance
* Importance of data pipelines in training efficiency
* Practical impact of hyperparameter tuning
* Fundamentals of transfer learning

---

## Objective

The goal of this repository is to:

* Build strong practical intuition in deep learning
* Move from basic implementations to optimized models
* Prepare for real-world machine learning and AI systems

---

## Future Work

* Implementation of advanced architectures (ResNet, EfficientNet)
* Experimentation with larger datasets
* Model evaluation metrics and benchmarking
* Deployment of trained models

---

## Note

This repository reflects an iterative learning process. The focus is on clarity of implementation, experimentation, and gradual improvement rather than production-level optimization.
