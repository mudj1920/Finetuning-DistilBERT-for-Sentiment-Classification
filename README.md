# Finetuning DistilBERT for sentiment classification

## Overview
This project focuses on performing sentiment classification on the SST-2 dataset using the DistilBERT model. The objective is to accurately classify text snippets into positive or negative categories based on their sentiment.

## Task
The task involves sentence-level sentiment classification on the Stanford Sentiment Treebank version 2 (SST-2), utilizing the DistilBERT-base-uncased model for its efficiency and performance trade-offs.

## Dataset
The SST-2 dataset, an extension of the original SST, provides a binary classification challenge focusing on sentence-level sentiment classification with labels indicating positive or negative sentiment.

## Models
We employ the `distilbert-base-uncased` model for its streamlined efficiency, which retains most of the linguistic understanding capabilities of BERT but is smaller and faster, making it ideal for sentiment classification tasks.

## Hardware and Tools
- Google Colab Pro with T4 GPU for training
- Weights & Biases for tracking metrics and visualization
- Hugging Face platform for dataset extraction

## Performance
- Training accuracy: 98.20%
- Evaluation accuracy: 87.33%
- Test accuracy on the "validation" split: 90.173%

## Potential Improvements
Recommendations include enhanced preprocessing, incorporating more contextual information, employing advanced models, applying transfer learning and fine-tuning, and data augmentation to address challenges such as sarcasm, irony, and nuanced language expressions.
