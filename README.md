# breast-histology-image-classification
Classifying cancerous breast histology images using Convolutional Neural Network in TensorFlow.
This dataset consists of 5547 breast histology images of size 50 x 50 x 3, curated from [Andrew Janowczyk website](http://www.andrewjanowczyk.com/use-case-6-invasive-ductal-carcinoma-idc-segmentation/)
and used for a data science tutorial at [Epidemium](http://www.epidemium.cc/). The goal is to classify cancerous images (IDC : invasive ductal carcinoma) vs non-IDC images.

The neural network is implemented as a python class and the complete TensorFlow session can be saved to or restored from a file.
We also implement tensor summaries, which can be visualized with TensorBoard. 
