# GenerativeAI with VAEs, GANs and Diffusion Models
# Introduction
The motivation for our project is to address the limitations of existing datasets
for medical imaging, especially in the context of brain MRI tumor detection for
rare types of cancer. The dataset sizes are often limited and lack diversity, leading
to overfitting and reduced performance of deep learning models. Moreover,
obtaining additional data can be challenging due to factors such as patient privacy,
the cost and time required for acquiring physical copies of medical tests,
and in our case: difficult to find rare cases of cancer. By generating more images,
we can improve the detection of rare forms of cancer and ultimately improve
their detection.
# Dataset
Brain MRI images with uncommon types of cancer are a rarity. We are leveraging the Brain Tumor MRI dataset from
Kaggle [https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset] for this project. This dataset contains 7023 images of human brain
MRI images which are classified into 4 classes: glioma, meningioma, no tumor
and pituitary. We do so in order to augment the dataset using the generated. We also compare the results of different Generative Models.
