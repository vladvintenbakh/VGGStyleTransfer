# Style Transfer Using Pretrained VGG Model

## Project Objective
The purpose of this project is to implement image style transfer by leveraging the VGG pretrained model, focusing on transferring artistic styles from one image to another. This notebook preprocesses input images and optimizes the combination of content and style representations to produce a visually appealing output. The ultimate goal is to enable the seamless transfer of an artistic style to a target image using deep learning techniques.

### Methods Used
* Image Preprocessing
* Convolutional Neural Networks (CNNs)
* Transfer Learning
* Optimization Algorithms

### Technologies
* Python
* Jupyter/Google Colab (GPU)
* NumPy
* Matplotlib
* TensorFlow/Keras

## Project Description
This project utilizes TensorFlow to apply style transfer using the VGG network, which is pretrained on image classification tasks. The core idea is to separate and recombine the content of an input image with the style of another image. The process involves extracting features from multiple layers of the VGG network to represent both content and style.

Key steps in the project include:
1. Preprocessing images to fit the input requirements of the VGG model.
2. Extracting content and style features using specific layers from the pretrained VGG model.
3. Applying an optimization process to merge the content from one image with the style of another.
4. Visualizing the results at various stages of optimization to track the transformation.

## Project Needs
- Image preprocessing and feature extraction
- Transfer learning with pretrained models
- Optimization of content and style blending
- Data visualization and reporting

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Use the [VGG pretrained model](https://www.tensorflow.org/api_docs/python/tf/keras/applications/VGG19) available via TensorFlow's Keras API for style transfer.
3. The primary Jupyter notebook for the project, implementing the full pipeline, can be found [here](https://github.com/vladvintenbakh/VGGStyleTransfer/blob/main/VGG_Style_Transfer.ipynb).
4. Upload and run the notebook on Google Colab (ensure GPU runtime is enabled).

## Featured Notebooks
* [VGG_Style_Transfer.ipynb](https://github.com/vladvintenbakh/VGGStyleTransfer/blob/main/VGG_Style_Transfer.ipynb)
