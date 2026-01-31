# Blood-Cell-identification-by-TensorFlow
# Table of Contents
-[About This Dataset](#📘 About_This_Dataset)
-[Identify the cell type by Tensorflow](##Identify_the cell_type_by_Tensorflow)


##📘 About This Dataset
Accurate identification of blood cell subtypes plays a crucial role in diagnosing a wide range of blood‑related diseases. Automated image‑based classification systems can significantly improve diagnostic speed, consistency, and scalability in clinical workflows. This project uses a curated and augmented collection of blood cell images to train and evaluate deep learning models for cell‑type recognition.
Dataset Overview
The dataset includes 12,500 augmented blood‑cell images (JPEG) paired with cell‑type labels (CSV). Images are organized into four folders corresponding to the four major white blood cell subtypes:
Eosinophil
Lymphocyte
Monocyte
Neutrophil
Each class contains roughly 3,000 images, providing a balanced dataset suitable for training convolutional neural networks.
In addition to the augmented dataset, the project includes the original 410 high‑resolution images with:
subtype labels (WBC vs RBC)
bounding box annotations (JPEG + XML metadata)
These original images are stored in the dataset-master folder, while the dataset2-master folder contains 2,500 augmented images with expanded subtype labels (JPEG + CSV).
The augmentation process expands the dataset from the original class counts (88, 33, 21, and 207 images per class) to a more robust and balanced training set of ~3,000 images per category.

Acknowledgements
Dataset source:
BCCD Dataset — [https://github.com/Shenggan/BCCD_Dataset](https://github.com/Shenggan/BCCD_Dataset)
Licensed under the MIT License.

##Identify the cell type by Tensorflow

[Code and iamges lins](blood-cell-identification-with-images.ipynb)
