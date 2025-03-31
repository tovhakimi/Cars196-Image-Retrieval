# Image Retrieval System - Configuration 2

This project implements an Image Retrieval System using deep learning techniques for feature extraction and Nearest Neighbors for image similarity search.

## Description
The purpose of this configuration is to build an image retrieval system capable of finding similar images from a dataset based on deep learning embeddings. It utilizes the best pre-trained model from Configuration 1 and applies various distance metrics to evaluate image similarity.

## Features
- Utilizes a pre-trained model from Configuration 1 for feature extraction.
- Implements Cosine, Euclidean, and Combined (Weighted) distance metrics for image retrieval.
- Evaluates retrieval performance using Precision and Recall.
- Provides visualization of results with similarity plots.

## Requirements
The requirements for this project are specified in the `requirements.txt` file.

## Instructions
1. Clone the repository and navigate to the project directory.
2. Install the required packages using:
```
pip install -r requirements.txt
```
3. Upload the necessary files (`stanford_cars_with_class_names.xlsx`, `experiment_2_weights.pth`, and the cropped images dataset).
4. Run the notebook and follow the instructions to test the image retrieval system.


## Output
- Similarity results displayed in plots showing the top K most similar images for a given query.
- Precision and Recall plots for evaluation.
