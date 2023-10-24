
![Screenshot (137)](https://github.com/KamranUmer/MRI-Tumor-Detection/assets/86089489/af615f8b-4729-4ddd-b820-5e09ea5c0cec)


# MRI Brain Tumor Segmentation with YOLOv7

This repository contains the code and resources for training a brain tumor segmentation model using YOLOv7 on a custom dataset of MRI images. YOLOv7 is a state-of-the-art object detection algorithm known for its accuracy and real-time performance. By leveraging YOLOv7, we can efficiently segment brain tumors in MRI images, which can be used to aid in diagnosis and treatment planning.

# Dataset:
To train the brain tumor segmentation model, we collected and annotated a custom dataset of MRI images of patients with brain tumors. The dataset includes images from different patients with different types of brain tumors. The annotations contain bounding box coordinates for the tumor in each image.

# Model Training:
The training pipeline involves several steps, including data preparation, model configuration, training, and evaluation. Here's an overview of the training process:

# Data Preparation:
We divided the dataset into training and validation sets. Each image was resized and preprocessed to match the input requirements of the YOLOv7 model.
We also applied data augmentation techniques to the training set to artificially increase the size of the dataset and improve the generalization ability of the model.
# Model Configuration:
YOLOv7 requires a configuration file specifying the model architecture and hyperparameters. We fine-tuned the configuration file according to our specific requirements, such as the number of classes (tumor in our case) and anchor sizes.
Model Training: We trained the YOLOv7 model using the prepared dataset and configuration. The training involved optimizing the model's weights to minimize the segmentation loss and improve its ability to identify and segment brain tumors accurately. We used the Adam optimizer with a learning rate of 0.0001 and trained the model for 100 epochs.
# Model Evaluation: 
To assess the performance of the trained model, we evaluated its accuracy on the validation set. We computed metrics such as Dice coefficient, sensitivity, and specificity to measure the model's effectiveness in brain tumor segmentation. The model achieved a Dice coefficient of 0.85, sensitivity of 0.9, and specificity of 0.95 on the validation set.

# Contact : 

If you have any question or suggestion fell free to contect at kamranumer080@gmail.com .
