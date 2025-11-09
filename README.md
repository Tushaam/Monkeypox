# **A Robust Transformer Architecture with Broad Attention for Monkeypox Lesion Detection in Skin Images**

This repository introduces B2MViT (Broad Attention Multiscale Vision Transformer) — a hybrid deep learning framework that integrates multiscale feature extraction with transformer-based global attention for highly accurate skin lesion classification.
The model is developed to advance Monkeypox detection from dermoscopic images by effectively capturing both fine-grained local textures and global contextual patterns.

B2MViT achieves an exceptional average accuracy of 99.69% across 5-fold cross-validation on the Monkeypox Skin Lesion Dataset, outperforming standard CNN and transformer-based baselines.
In addition to conventional performance metrics, statistical significance testing (p-value = 0.01219) further validates its superiority over the ResNet50 baseline model.


# **Repository structure**

Dataset/
-It contains the links for the dataset used for the research.

Proposed model/
-It contains the code files for the proposed model.

# **Dataset Description**
1) **Monkeypox Skin Lesion Dataset(MSLD)**:  Contains a total number of 228 images, among which 102 belongs to the 'Monkeypox' class and the remaining 126 represents the 'Others' class i.e., non-monkeypox (chickenpox and measles) cases.After augmentation, The classes 'Monkeypox' and 'Others' have 1428 and 1764 images, respectively.
2) **Monkeypox Skin Image Dataset(MSID)**:  Contains a total number of 770 images, among which 107 belong to 'chickenpox' class, 91 to 'measles' , 279 to 'Monkeypox', 293 to 'Normal'

# **Evaluation metrics used**
1) Accuracy
2) F1 Score
3) Precision
4) Recall
5) ROC-AUC curve
6) Confusion matrix

**Statistical analysis and visualization**:
1) GRADCAM
2) chi-square test
3) paired t-test
4) Computational metrics: Model parametric count , FLOPs, Inference time, Throughput
