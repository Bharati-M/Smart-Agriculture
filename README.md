# Smart-Agriculture
A computer vision system for detecting plant health issues and crop diseases in field images to enable early intervention and yield optimization.
## Project Objective
The objective of this project is to detect plant leaf diseases using Convolutional Neural Networks (CNNs).
It aims to assist farmers and researchers by providing an automated, accurate, and cost-effective system to identify diseases from leaf images — reducing crop loss and improving yield quality.
## Dataset Used
- <a
href = "https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset">
Dataset1</a>
- <a
href = "https://www.kaggle.com/datasets/fpeccia/weed-detection-in-soybean-crops">Dataset2</a>
## Question (KPIs)
- How can deep learning (CNN) be used to accurately identify plant leaf diseases from images?
- What preprocessing techniques (resizing, normalization, augmentation) most improve model accuracy?
- How can the model detect multiple crops and multiple diseases efficiently?
- Can a lightweight CNN model perform comparably to heavy pretrained models (VGG16, ResNet)?
- How can accuracy and inference speed be balanced for mobile or low-resource environments?
- What are the limitations of current deep learning models in real-field plant disease detection?
## Process
- Data Collection - Gathered data.
- Data Preprocessing - Image resizing (128×128), Normalization (0–1 range), Data augmentation (rotation, brightness, flip, zoom)
- Model Design - Built a Custom CNN using PyTorch.
- Model Training - Trained on 80% of data, validated on 20%.
- Model Evaluation - Accuracy, Precision, Recall, F1-score, and Confusion Matrix evaluated.
- Model Saving - Saved model as plant_disease_model.pth.
