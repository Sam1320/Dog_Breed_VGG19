# Dog Breed Classifier with VGG19 network using Transfer learning

<img src="https://github.com/Sam1320/Dog_Breed_VGG19/blob/master/dogs_output.png">

Convolutional Neural Network(CNN) project for Udacity's [Machine Learning Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t). I learned how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, my algorithm identifies the dog's breed (specifying it's confidence). If supplied an image of a human, the code identifies the resembling dog breed. If neither a human nor a dog are provided as input, the app recognizes it ignorance about the non-human & non-Dog Realm.

## Network Structure

* First I used [VGG16](https://arxiv.org/abs/1409.1556) to learn to train a model using Transfer learning.
* For the final model I used VGG19's bottleneck features (Output after convolutional layers) as input to my own architecture.

**VGG16 & VGG19** 

<img src="https://github.com/Sam1320/Dog_Breed_VGG19/blob/master/VGG_image.png">

**My Architecture**

<img title="My Architecture" src="https://github.com/Sam1320/Dog_Breed_VGG19/blob/master/Fine_tuning.png">


## Completed Project & Evaluation
* [Project Notebook](https://github.com/Sam1320/Dog_Breed_VGG19/blob/master/dog_app.ipynb)
* [Project Review](https://github.com/Sam1320/Dog_Breed_VGG19/blob/master/Project_Review.pdf)

## Contents

- Intro
- Step 0: Import Datasets
- Step 1: Detect Humans
- Step 2: Detect Dog
- Step 3: Create a CNN to Classify Dog Breeds (from Scratch)
- Step 4: Create a CNN to Classify Dog Breeds (using Transfer Learning)
- Step 5: Write Your Algorithm
- Step 6: Test Your Algorithm

## Example Outputs
<img src="https://github.com/Sam1320/Dog_Breed_VGG19/blob/master/dog_output.png">
<img src="https://github.com/Sam1320/Dog_Breed_VGG19/blob/master/human_output.png">
<img src="https://github.com/Sam1320/Dog_Breed_VGG19/blob/master/octopus_output.png">


