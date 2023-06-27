# Classifying-with-convnets

The task involves working with an image dataset for classification purposes. 
The dataset, called "faces dict.p," is located in the "guias/Datasets/" folder of the repository. 
It consists of 400 images of 40 different individuals. Each image is 64x64 pixels in size and has been converted to floating point values ranging from 0 to 1 after quantization to 256 grey levels.
The goal is to classify the images based on the identity of the person pictured, represented by an integer between 0 and 39.

The task is divided into two parts:

Baseline Classification Pipeline:

Select a classic machine learning algorithm (non-neural network) of your choice.
Build a pipeline using this algorithm for classification.
Estimate the classification error of the baseline pipeline.
Make efforts to improve the classification error as much as possible.
Convolutional Neural Network (CNN) Classification:

Build a CNN to classify the same dataset.
Make efforts to improve the classification error compared to the baseline pipeline.
Implement a pretrained model in addition to the hand-crafted CNN for a bonus point.
Data augmentation is encouraged, and implementing it will also earn a bonus point.
Both parts of the problem are mandatory, and completing only one part will result in not passing the course.
