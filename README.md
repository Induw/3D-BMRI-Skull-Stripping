# 3D Complementary Segmentation Network (CompNet) Flask App

**3D CompNet**, a web-based tool for skull stripping in Brain MRI scans using the 3D Complementary Segmentation Network (CompNet). This application was designed as my final year research project, it addresses the problem of pathological variability of skull stripping in volumetric Brain MRIs particularly near the skull boundary.

<img width="716" alt="image" src="https://github.com/user-attachments/assets/e2d44837-41e9-4154-b696-153185137db8" />

## Overview

Magnetic Resonance Imaging (MRI) is vital for brain imaging, but isolating brain tissue (skull stripping) remains challenging, especially with pathologies like tumors near the skull. The **3D CompNet** architecture integrates dual complementary pathways to simultaneously segment brain and non-brain tissues, enhancing robustness and precision. This Flask app provides an intuitive interface to upload MRI scans, process them using the trained 3D CompNet model, and visualize/download the results.

## Features

- **Advanced Skull Stripping**: Handles 3D T1-weighted Brain MRIs with complex pathologies near the skull.
- **Dual Pathways**: Combines brain and non-brain segmentation for improved accuracy.
- **Web Interface**: Built with Flask for easy file uploads and result visualization.
- **Visualization**: Displays original MRI, brain mask, and skull-stripped output for selected slices.
- **Downloadable Results**: Saves processed volumes as NumPy arrays in a downloadable ZIP file.

## Installation

### Prerequisites
- Python 3.8+
- Dependencies: Flask, TensorFlow, Keras, NumPy, NiBabel, Matplotlib, OpenCV, SciPy, MedPy
