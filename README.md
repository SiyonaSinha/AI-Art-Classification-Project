## AI-Art-Classification-Project
This project explores whether a machine learning model can distinguish AI-generated artwork from human-created art. Using MobileNetV2 and logistic regression as a baseline, followed by fine-tuning a pretrained CNN, the project investigates how well AI can "see" the differences in style and content.

# Motivation

With generative AI growing rapidly, it is often difficult to distinguish AI-generated images from human artwork. This project aims to build a model that can reliably classify images and to explore the challenges of training and evaluating such models.

# Dataset

The dataset consists of images sourced from:

AI-generated art: various generative AI models.

Human-created art: publicly available artworks.

Note: All images were used solely for educational purposes.Results

Logistic Regression baseline: achieved reasonable classification accuracy.

Fine-tuned MobileNetV2: improved accuracy and better performance on challenging images.

Metrics were visualized through accuracy and loss curves, highlighting model learning behavior.

# Models

Baseline: Logistic Regression on features extracted from a pretrained MobileNetV2.

Fine-tuned CNN: MobileNetV2 with initially frozen layers, then gradually unfrozen to learn higher-level patterns.

# Evaluation

Performance was analyzed by comparing:

Training accuracy

Validation accuracy

Training loss

Validation loss

This analysis helped identify overfitting, evaluate generalization, and understand which images were most challenging to classify.
# Dataset Credit

This project uses the “Real and Fake AI-Generated Art Images Dataset” from Kaggle:
https://www.kaggle.com/datasets/doctorstrange420/real-and-fake-ai-generated-art-images-dataset

Credit to the dataset creator for providing AI and human artwork images for educational use.
