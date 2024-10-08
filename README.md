# Deep Few-Shot Learning for MRI-based Alzheimer's Diagnosis

This repository provides a deep learning framework for diagnosing Alzheimer's dementia (AD) using MRI images. It includes two key phases: data augmentation and classification, designed to enhance diagnosis accuracy, even with limited data.

## Project Overview

This project addresses the following key objectives:
- **Data Augmentation**: Using a Convolutional Cross-Modal Autoencoder (CCMAE) to generate synthetic MRI images.
- **Data Classification**: Employing a CNN-based model that fuses visual and textual features to improve AD diagnosis.

## Key Files

- **`data_augmentation.ipynb`**: This notebook demonstrates the implementation and training of the **Convolutional Cross-Modal Autoencoder (CCMAE)**, designed to generate synthetic cross-sectional MRI images for data augmentation.
  
- **`classification_model.ipynb`**: This notebook implements the **CNN-based classification model** that fuses MRI image features with textual metadata to improve diagnostic accuracy.

You can run these notebooks in [Google Colab](https://colab.research.google.com/) or locally with [Jupyter Notebook](https://jupyter.org/).

## Installation

To run the notebooks, ensure you have Python 3.x and the necessary libraries installed:

```bash
pip install -r requirements.txt
```
## Results
The project has been tested on publicly available MRI datasets. The augmentation and classification methods demonstrate significant improvements in diagnostic accuracy. The following is an example of a cross-sectional MRI image generated by the CCMAE model:


