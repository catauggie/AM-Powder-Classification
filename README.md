# Powder Particle Classification with Scanning Electron Microscopy Images using Machine Learning Techniques

This repository contains the essential files for the classification and analysis of powder particles using SEM images and machine learning techniques, as described in the article *"Powder Particle Classification with Scanning Electron Microscopy Images Using Machine Learning Techniques"*.

## Key Files:

- **Cropping.ipynb**: A Jupyter notebook for cropping labeled fragments from SEM images, enabling focused analysis of powder particles.
- **Pipeline.ipynb**: Implements the HCF+PCA+XGBoost method for feature extraction and classification of powder particles.
- **YOLO.ipynb**: A notebook dedicated to training the YOLOv8 model for particle classification in SEM images.
- **contour_coordinates_Al.csv**: Contains the contour coordinates of particles from the AlSiMg powder.
- **contour_coordinates_St.csv**: Contains the contour coordinates of particles from the 316L powder.
- **contour_coordinates_Ti.csv**: Contains the contour coordinates of particles from the TiAlV powder.
- **objects_summary_Al.xlsx**: Excel file summarizing the detected objects (particles) in SEM images for AlSiMg powder.
- **objects_summary_St.xlsx**: Excel file summarizing the detected objects (particles) in SEM images for 316L powder.
- **objects_summary_Ti.xlsx**: Excel file summarizing the detected objects (particles) in SEM images for TiAlV powder.

## Folders:

- **train14**: Contains the best model configuration along with its statistics, providing the optimal setup for particle classification.
- **SEM**: Contains the raw SEM images of powder particles, used for the classification tasks in the repository.

This collection provides an end-to-end solution for powder particle classification, combining data preprocessing, model training, and post-processing analysis.

## Installation and Usage

To get started, clone the repository and open the Jupyter notebooks to explore the various methods used for classification. Ensure you have all required libraries installed before running the notebooks.
