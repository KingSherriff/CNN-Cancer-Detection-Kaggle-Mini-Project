To get the data for the project please go to https://www.kaggle.com/competitions/histopathologic-cancer-detection/data
# A CNN-based tool for lymph node cancer histology image classification

**A deep learning tool for binary (present/absent) classification of histopathology images.**

## Overview
This project develops a Convolutional Neural Network (CNN) system to assist in the pathological analysis of lymph node cancer tissue slides.

**Key Features:**
- **Dual Classification:** Predicts present/absent status of cancer in images.
- **Ready-to-Use Demo:** An interactive Jupyter Notebook allows users to test the model on new images. (Coming Soon)
- **Reproducible Research:** Complete training code and methodology are openly documented.

## Quick Start: Test the Model
Want to see the model in action? Follow these steps to test it on a sample image:

1.  **Clone this repository and install dependencies:**
    ```bash
    git clone https://github.com/KingSherriff/CNN-Cancer-Detection-Kaggle-Mini-Project.git
    cd CNN-Cancer-Detection-Kaggle-Mini-Project
    pip install -r requirements.txt
    ```
2.  **Launch the interactive demo:**
    - Open [`demo_histology_model.ipynb`](demo_histology_model.ipynb) in Jupyter Notebook or Google Colab.
    - Follow the instructions to load a pre-trained model and run inference.
3.  **View Results:** The demo will display the classification

## Project Structure
```text
├── demo_histology_model.ipynb        # Interactive demo to test & explain predictions
├── research_methodology.ipynb        # Full experimental pipeline (EDA, training, analysis)
├── requirements.txt                  # Python dependencies
└── models/
    └── best_model.h5                 # Best-performing trained model
```

## Image Requirements for Inference

For the best results with the demo, input images should meet the following requirements:
- **Format:** PNG or JPEG.
- **Origin:** Ideally from the [pcam](https://github.com/basveeling/pcam) dataset or similar sources.

## Detailed Methodology & Research

For a deep dive into the data exploration, model architectures, training procedures, and result analysis, please see the complete research notebook:
**[`research_methodology.ipynb`](research_methodology.ipynb)**
