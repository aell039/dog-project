## Welcome

This project forms part of the coursework for Udacity's Data Science Nanodegree. Read on for more information on how this project is structured, or check out my blog post which summarises the best bits: https://medium.com/@aell039/what-dog-breed-do-you-look-like-bda24a56543a

## Project Motivation

The motivation for this project is to create a convolutional neural network with the ability to classify dogs by their breed, and also to make fun predictions using images of humans.

## Libraries used

- Keras - to create our neural network
- OpenCV (cv2) - image manipulation and associated functions
- matplotlib - for drawing bounding boxes on images
- PIL - loading images


## Files in this repo

haarcascades	Face detector model, used to determine if we are working with an image of a human
images		Imagery used in the notebook (not training or testing images)
requirements	yml files for system setup
saved_models	checkpoints of the best models
test_images	A selection of images to test the model with
LICENSE.txt	Licensing info
README.md	What you're reading now
dog_app.ipynb	Jupyter notebook containing all the steps of this project
extract_bottleneck_features.py	Helper function to extract bottlenecks


## Results

The notebook goes into more detail, but to summarise: the code in this successfully creates and trains a model to determine dog breed with over 80% accuracy. The final cells of the notebook roll this into a function that can be called on any source image you like.


