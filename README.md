# Blood-Cell-identification-by-TensorFlow
## Table of Contents
- [Project Overviews](#project-overviews)
- [About This Dataset](#about-this-dataset)

## Project Overviews
This project demonstrates an end‑to‑end deep learning workflow for automated blood cell classification using TensorFlow. Leveraging a curated dataset of 12,500 augmented white blood cell images, the goal is to build a reliable model capable of distinguishing between four major cell types: Eosinophil, Lymphocyte, Monocyte, and Neutrophil.
The notebook walks through the full machine learning pipeline:

Data ingestion & preprocessing  
Images are loaded from structured folders, resized, normalized, and prepared using TensorFlow’s efficient tf.data pipeline.

Exploratory visualization  
Sample images and class distributions are examined to understand dataset balance and visual characteristics.

Model development  
A Convolutional Neural Network (CNN) is constructed to learn discriminative features from cell morphology and texture.

Training & evaluation  
The model is trained on the augmented dataset and evaluated on a held‑out validation set to measure classification performance.

Prediction & interpretation  
The trained model is used to classify new images, demonstrating its ability to generalize to unseen samples.

This project highlights how deep learning can support medical image analysis by automating routine classification tasks that traditionally require expert review. The workflow is fully reproducible and serves as a practical example of applying TensorFlow to real‑world biomedical imaging problems. 

[Tensorflow code and images](blood-cell-identification-with-images.ipynb)

## About This Dataset
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



