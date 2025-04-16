# Shapes and Colors Prediction Challenge

Welcome to the **Shapes and Colors Prediction Challenge**!

In this competition, participants will predict the shapes and their corresponding colors present in synthetic images. Each image contains randomly placed geometric shapes—**circles, squares, and triangles**—colored in **red, blue, or green**, rotated randomly without overlaps.

## Goal

The goal is straightforward: given an image, accurately predict which shapes and colors it contains. This problem provides a simple yet insightful testbed for **multi-label image recognition** and **object detection** tasks.

Your model should predict:

The number of shapes present (between 1 and a configurable maximum per image).
The type (circle, square, triangle) and color (red, blue, green) of each shape.


## Task

Your task is to accurately identify all shapes and their colors present in each image. For each image, you'll submit predictions in the form of a **list of tuples** (shape, color). Your submissions will be evaluated based on how closely your predictions match the true labels provided in the training set.


## Dataset
In this dataset, each image includes up to a configurable maximum number of geometric shapes:

- Shapes: circle, square, triangle
- Colors: red, blue, green

## Results
Average Jaccard Similarity on held out Validation Data consisting of 1000 images: 100.00% 
These results are achieved due to the presense of synthetic dataset and a simpler classification task.