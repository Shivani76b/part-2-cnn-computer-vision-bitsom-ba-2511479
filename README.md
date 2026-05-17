# Part 2: Computer Vision Problem Formulation and CNN Prototype

## Dataset Source
The dataset used in this project is available at:
https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing

Note: Dataset files are not included in this repository as per submission guidelines.

## Dataset
Surface defect image dataset with 4 classes: dent, normal, scratch, stain
Total images: 480 (120 per class) - perfectly balanced

## Problem Type
Image Classification - Classifying surface defects into 4 categories

## Task 6: CNN Concept Explanation

### What is convolution?
Convolution is a mathematical operation where a small filter slides over 
the image and detects features like edges, shapes, and textures. Each 
filter learns to detect a specific pattern in the image.

### Why is pooling used?
Pooling reduces the size of feature maps by keeping only the most 
important information. This reduces computation, memory usage, and 
helps the model focus on the most relevant features.

### Why is ReLU commonly used in CNNs?
ReLU sets all negative values to zero and keeps positive values as they 
are. It is simple, fast, and helps the network learn non-linear patterns 
without the vanishing gradient problem.

### Why are CNNs better than regular networks for image data?
CNNs use shared weights through filters which reduces parameters 
significantly. They also preserve spatial relationships between pixels 
which regular networks ignore by flattening the image.

## Task 7: Business Use Case
This surface defect detection solution can be used in Manufacturing.
Factories can use this model to automatically inspect products on 
assembly lines and detect defects like dents, scratches, and stains 
in real time, reducing manual inspection cost and improving quality.

## Model Results
- Training Accuracy: 99.74%
- Validation Accuracy: 98.96%
- Test Accuracy: 99%

## Libraries Used
- TensorFlow 2.21.0
- OpenCV
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
