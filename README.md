# Decomposition of People's Faces into Principal Components

## Project Overview

This project aims to process and analyze a dataset containing images of 38 individuals under various lighting conditions to extract 'eigenfaces'. The process involves converting each image (192x168 pixels) into a vector, performing Singular Value Decomposition (SVD) on the centered data, and reshaping the eigenvectors back into images. The project focuses on the decomposition of an image from an unseen individual using these eigenfaces, exploring reconstruction accuracy with different numbers of components, and quantifying the contribution of specific eigenfaces to the images of another individual. This provides insights into the facial characteristics captured by the eigenfaces.

**Please note:** This project is intended primarily for viewing and educational purposes. The complete code along with the results are included in the notebook. However, the dataset containing the images is not provided within this repository. The project was developed and run in Google Colab, which allows for a comprehensive view of both the code and its outcomes.

## Viewing the Project

The project is contained within a Jupyter Notebook that includes both the code and the visual results of the analysis. Since the dataset used is not included in this repository, the notebook serves as a detailed case study showcasing the methodology and findings from the analysis of the facial image data.

To view the project, simply navigate to the notebook file within this repository. For an enhanced viewing experience, you may also open the notebook in Google Colab or another Jupyter Notebook viewer that supports the notebook format.

## Project Highlights

- **Image to Vector Conversion**: Converts images of faces into vectors for analysis.
- **Singular Value Decomposition (SVD)**: Utilizes SVD to extract significant features (eigenfaces) from the dataset.
- **Eigenface Generation**: Generates eigenfaces by reshaping eigenvectors back into images.
- **Image Reconstruction**: Examines the reconstruction of images using a variable number of eigenfaces, assessing the accuracy.
- **Contribution Quantification**: Quantifies the contribution of specific eigenfaces to the facial characteristics of individuals.


