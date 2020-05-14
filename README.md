## Dog breed classifier using CNN and Transfer Learning
## Project Overview
In this project, the code will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.
## Import Datasets
* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
* Download the [human_dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)
##  Create a CNN to Classify Dog Breeds(Building a model on my own)
![Screenshot19](https://user-images.githubusercontent.com/31853896/81976391-173d6c80-9646-11ea-8152-86abce25dd5c.png)
  
 ## Result
 Hi, This is a dog!   
 And I predict the Breed of this dog is a ages/train/076.Golden_retriever       

![dog2](https://user-images.githubusercontent.com/31853896/81958806-1d265400-962c-11ea-82a4-526d09c9fe66.jpg)


## Summary
There are several state of the arts model we tried. First I gave to shot to OpenCv but it fails when we don't have forward facing faces. Then I tried convolutional Neural Network from scratch with above parameters.It gave an accuracy of 9% which is too low. At last i tried two state of the arts pre-trained model VGG16 and Xception. VGG16 gave an accuracy of 43% where as VGG19 gave an accuracy of 70.9% of validation dataset with 20 epochs and about 30 sec of training on GPU.
