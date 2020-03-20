#  Dog Breed Cliassification Project
[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

Welcome to the Convolutional Neural Networks (CNN) project in the AI Nanodegree! In this project, you will learn how to build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images.  Given an image of a dog, your algorithm will identify an estimate of the canine’s breed.  If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

Along with exploring state-of-the-art CNN models for classification and localization, you will make important design decisions about the user experience for your app.  Our goal is that by completing this lab, you understand the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline.  Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.  Your imperfect solution will nonetheless create a fun user experience! 

---

### Stack
  
- Pytorch 
- numpy
- panda 
- matplotlib

---

### Dataset

- Download the [Dogs dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
- Download the [Human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)

---

### Accyracy Results 

- Using my CNN architecture give me a 11% for 50 epoch 
- Using transfer learning by try ResNet50 get a 81% for 15 epoch 

---

### What I leant in this project 

- Using openCV library for human detection and get a good accuracy 
- Solid understanding of how convolutional neural network work in depth
- Understand main concepts like ( **Convolution layer** , **pooling layer** , **batch normalization** , **regularization** , **bais and variance** , **activation functions** , **kernal** , **feature maps**)

- Split dataset to three parties and what is role of each part ( training , testing , validation)
- Create my own CNN architecture and try different architectures to get better accuracy and through these architectures give me more understanding in CNN 
- Apply transfer learning for human detection and for dog classification in the last step


