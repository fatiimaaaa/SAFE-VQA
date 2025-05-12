# Visual Question Answering (VQA) Models

This repository provides three implementations of **Visual Question Answering (VQA)** models, each using a different text-processing backbone combined with a ResNet-based image encoder:

- 🧠 `VQA_LSTM`: LSTM for question processing + ResNet variant for image features
- 🧠 `VQA_BERT`: BERT for question processing + ResNet variant
- 🧠 `VQA_MONAI`: MONAI-based image processing (for medical images) + BERT or LSTM for text

Each model outputs a predicted answer based on an input image and question.

---

## 📁 File Overview

