# Pneumonia Detection Using CNN-Based Feature Extraction

# Project Overview
Pneumonia is a serious lung infection and remains a significant health concern, especially in regions with limited access to medical experts. This project leverages the power of deep learning to automate the detection of pneumonia, reducing the dependency on expert radiologists and enabling quicker diagnosis.  
**Dataset Link** : https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia  

# Workflow
**Image Pre-processing** : Normalization, resizing (224x224), and data augmentation.  
**Feature Extraction**: Pre-trained ResNet-50 is used to extract deep features from X-ray images.  
**Classification**: A Random Forest classifier is trained on extracted features to distinguish between Pneumonia and Normal.  
**Evaluation**: Model performance is evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

# Results
Accuracy:	80.13%  
Precision:	76.60%  
Recall:	98.21%  
F1-Score:	86.07%  
