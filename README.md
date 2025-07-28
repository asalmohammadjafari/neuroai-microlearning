# 🧠 AvicennaFlow: Biologically Plausible Learning in CNNs

This repository contains the official codebase for the project:

**"Biologically Plausible Learning in CNNs: A Comparison of Backpropagation, Feedback Alignment, and Kolen–Pollack Algorithms for Image Classification"**

📚 **Conducted as part of the [Neuromatch Academy NeuroAI Program](https://neuroai.neuromatch.io/), July 2025.**

---

## 🧬 Project Summary

AvicennaFlow investigates **biologically plausible learning rules** in convolutional neural networks, comparing:

- **Backpropagation (BP)**
- **Feedback Alignment (DFA)**
- **Kolen–Pollack Algorithm (DKP)**

We analyze these algorithms on **MNIST** and **CIFAR-10** datasets using multiple metrics:
- Accuracy and training dynamics  
- Gradient signal-to-noise ratio (SNR)  
- Cosine similarity of gradients  
- Representational similarity (RSA & RDMs)  
- Robustness to adversarial attacks (FGSM)

---

## ⚙️ Setup

1. Install dependencies:

```bash
pip install -r requirements.txt
````

2. Run the notebook:

```bash
jupyter notebook AvicennaFlow_Project.ipynb
```

> ⚠️ Run cells in order for correct setup and training.

---


## 🧪 Evaluation Methods

* 🔬 **RDMs & RSA**: Compare internal representations layer-wise.
* 📊 **Cosine Similarity**: Between BP and DKP/DFA gradients.
* 🎯 **Adversarial Accuracy**: Under FGSM attacks.
* 🌀 **t-SNE Visualization**: Feature space separation.
* 📉 **Gradient SNR**: Assess clarity of learning signal.

---

## 🖼️ Sample Visualizations

Key results are stored in the [`plots/`](./plots) directory, including:

- RDM analyses (CIFAR-10 & MNIST)  
- Representational paths  
- Gradient SNR comparisons  
- t-SNE embeddings  
- Adversarial accuracy plots
