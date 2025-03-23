# 📊 Sentiment Analysis on App Reviews using BERT

This repository contains the final project for a Deep Learning course. The project applies a fine-tuned BERT model to perform sentiment analysis on user reviews of mobile applications (from the Google Play Store).

## 📌 Project Description

This project focuses on binary sentiment classification — determining whether a given user review is **positive** or **negative**.

The model is based on **BERT (Bidirectional Encoder Representations from Transformers)** and leverages transfer learning to improve performance on relatively small datasets.

## 🚀 Features

- Data cleaning and preprocessing (lowercasing, punctuation removal)
- Text tokenization using `bert-base-uncased`
- Balanced Train / Validation / Test splits
- Fine-tuning BERT with `EarlyStopping`
- Accuracy & Loss tracking per epoch with plots
- Confusion matrix for performance insight
- Inference function for predicting sentiment on new user input

## 🧠 Technologies Used

- Python 3
- PyTorch
- HuggingFace Transformers
- scikit-learn
- matplotlib
- Google Colab / Jupyter Notebook

## 📁 File Structure

- `2_Evaluation_With_Inference_ModelPath.ipynb` — Final notebook with full pipeline
- `bert_model.pt` — Best model saved during training (optional)
- `README.md` — This file

## 📈 Example Inference

```python
predict_sentiment("I love this app, it's super useful!", best_model, tokenizer)
# Output: Positive
```

## 👨‍🎓 Author

Project by Nadav Yedid  
Submitted as part of a Deep Learning course in the MSc in Industrial Engineering and Management.
