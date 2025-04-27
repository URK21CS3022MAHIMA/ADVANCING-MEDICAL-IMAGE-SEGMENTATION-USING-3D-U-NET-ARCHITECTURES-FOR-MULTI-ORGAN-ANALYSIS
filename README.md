# ADVANCING-MEDICAL-IMAGE-SEGMENTATION-USING-3D-U-NET-ARCHITECTURES-FOR-MULTI-ORGAN-ANALYSIS
Medical image segmentation is a crucial task in modern healthcare, enabling precise identification and analysis of anatomical structures across various imaging modalities like MRI and CT scans.
# ScanHippoHealth 🧠💊

<div align="center">
  <img src="screenshots/logo.png" alt="ScanHippoHealth Logo">
</div>


ScanHippoHealth is a sophisticated MRI segmentation project specifically designed for the segmentation of the Hippocampus. The project utilizes the dataset provided by the [Medical Segmentation Decathlon](http://medicaldecathlon.com/) for Generalizable 3D Semantic Segmentation.

## Overview

The project employs a 3D-Unet architecture for accurate segmentation. The architecture diagram can be found below- 

<div align="center">
  <img src="Segmentation_Architecture.png" alt="Architecture Diagram">
</div>

## Features 🚀

- **User Authentication:** Secure (Input Validations) login, logout, and registration functionalities are integrated.
- **Data Security:** User passwords are hashed and salted using the bcrypt library before storage in the MYSQL database.
- **MRI Segmentation:** Users can upload MRI images in `.nii.gz` format through the user-friendly Flask application.
- **Prediction and Visualization:** The model predicts the MRI images and displays six slices of the input image along with the corresponding mask. This aids in visualizing the segmentation results. The displayed output showcases six slices due to the nature of the input MRI, which constitutes a 3D volume, making it unfeasible to display entirely.

## Contributing 🤝

- T Mahima Rani - (thaddimahima@karunya.edu.in)

