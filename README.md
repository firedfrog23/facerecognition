# CELEB A Gender Classification

# Dataset
The CelebFaces Attributes (CelebA) Dataset is an extensive collection of celebrity face images compiled by researchers at MMLAB, The Chinese University of Hong Kong. This dataset includes more than 200,000 images featuring 10,000 celebrities, each annotated with 40 different attributes such as age, gender, and hair color. Due to its diversity and richness, CelebA serves as an excellent resource for training deep learning models in various computer vision applications.
Deep learning models trained on the CelebA dataset can be applied to multiple tasks, including facial attribute classification, face recognition, and face generation. The dataset’s annotated attributes also enable the development of models capable of accurately determining a person's gender based on facial features, which is the primary focus of the model in this notebook.

# Requirement
1. Numpy
2. Matplotlib
3. Tensorflow
4. Seaborn
5. Sklearn

# Workflow
1. Drop Duplicate
2. Sampling 5000 images
3. Encoding
4. Dataset Split as Training, Validation, Testing (70:15:15)
5. Data Augmentation
6. Model Training
7. Model Testing

# Base Model
1. VGG 16
2. ResNet
3. GoogleNet

# Conclusion
VGG16 has the highest accuracy at 90%, with higher precision for Class 0 but slightly lower performance for Class 1.
ResNet50 achieves an accuracy of 88%, offering a better balance between precision and recall for both classes, along with a relatively stable F1-score.
GoogLeNet has the lowest accuracy among the three models at 83%, with higher precision for Class 0 but a more noticeable imbalance in the F1-score.

VGG16 is the best model in terms of overall accuracy (90%), but ResNet50 is more balanced and stable in handling both classes.
