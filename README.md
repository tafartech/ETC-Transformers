# Ensemble Text Classifier with Transformers (ETC-Transformers)

This repository contains the implementation of a multi-class text classification framework based on a diverse stacking ensemble method utilizing transformer models. This approach is inspired by the research paper "Optimizing Multi-Class Text Classification: A Diverse Stacking Ensemble Framework Utilizing Transformers" by Anusuya Krishnan.

## Overview 
Customer reviews play a crucial role in assessing customer satisfaction, gathering feedback, and driving improvements for businesses. Analyzing these reviews provides valuable insights into customer sentiments, including compliments, comments, and suggestions. Text classification techniques enable businesses to categorize customer reviews into distinct categories, facilitating a better understanding of customer feedback.

However, challenges such as overfitting and bias limit the effectiveness of a single classifier in ensuring optimal prediction. This study proposes a novel approach to address these challenges by introducing a stacking ensemble-based multi-text classification method that leverages transformer models. By combining multiple single transformers, including `BERT`, `ELECTRA`, and `DistilBERT`, as base-level classifiers, and a meta-level classifier based on `RoBERTa`, an optimal predictive model is generated.


# Model TrainingData Preparation: 
1. Load and preprocess the dataset.
2. Model Initialization: Initialize base-level transformer models (BERT, ELECTRA, DistilBERT) and meta-level model (RoBERTa).
3. Training Loop: Train the base-level models and use their outputs as features for the meta-level model.
4. Model Saving: Save the trained model for later use.

**The proposed ensemble model demonstrates improved accuracy and robustness in multi-class text classification tasks compared to single transformer models. Detailed results and performance metrics are available in the research paper.**

## References
- Krishnan, A. (2023). "Optimizing Multi-Class Text Classification: A Diverse Stacking Ensemble Framework Utilizing Transformers". [Big Data Mining and Analytics](https://arxiv.org/abs/2308.11519). DOI: 10.26599/BDMA.2023.9020xxx.
