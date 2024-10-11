# GAN_CT_Scan_Medical_Imaging
This repository contains a final-year project developed for the Private University of Fez, Morocco. The project uses Generative Adversarial Networks (GANs) to generate synthetic CT scan images based on FDG-PET/CT and MRI data of soft tissue sarcomas.

# Project Description
The aim of this project is to augment medical imaging datasets using GANs, improving diagnostic accuracy and model generalization in machine learning tasks. The model is trained on a dataset available on Kaggle here.

Note: This project and the accompanying Jupyter notebook were created in French as part of a university requirement.

# Contents
- Data Loading and Preprocessing: The CT scan data is loaded from .h5 files, followed by preprocessing steps to prepare it for training.
- GAN Architecture Definition: The Generative Adversarial Network consists of a Generator and a Discriminator. The Generator creates synthetic images, while the Discriminator evaluates them against real images.
- Training Process: The training loop alternates between training the Generator and Discriminator to improve the quality of generated images.
- Image Generation: Synthetic images are generated and saved throughout the training process for evaluation.
- Evaluation: The performance of the GAN is assessed by comparing the synthetic images to real CT scans.
