## Dog breed classifier using CNN and Transfer Learning
## Project Overview
In this project, the code will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.
## Import Datasets
* Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
* Download the [human_dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip)
##  Create a CNN to Classify Dog Breeds
<img width="404" alt="sample_cnn" src="https://user-images.githubusercontent.com/31853896/81956048-7c826500-9628-11ea-8001-3d41438fb0dd.png">   

## Create a CNN to Classify Dog Breeds "using Transfer Learning" 
 * Using VGG19 pretrained Model *
## Test The Algorithm
Test your algorithm at least six images on your computer.  Feel free to use any images you like.  Use at least two human and two dog images.  
 ## Result
 predict_breed 'Data-Scientist-Nanodegree/Test-Image/dog2.jpg'
Hi, This is a dog!   

And I predict the Breed of this dog is a ages/train/076.Golden_retriever       

![dog2](https://user-images.githubusercontent.com/31853896/81958806-1d265400-962c-11ea-82a4-526d09c9fe66.jpg)
predict_breed 'Data-Scientist-Nanodegree/Test-Image/23.jpg'

Hi, This's a human!        

If you were a dog, I predict that would be a ... ages/train/132.Xoloitzcuintli!!    

![23](https://user-images.githubusercontent.com/31853896/81959128-a0e04080-962c-11ea-8dcb-444116736433.jpg)

Hi, This's a human!
If you were a dog, I predict that would be a ... ages/train/049.Chinese_crested!!

![IMG_20180930_175657886](https://user-images.githubusercontent.com/31853896/81959541-3c71b100-962d-11ea-8688-f4ba81b289b3.jpg)

Hi, This is a dog!
And I predict the Breed of this dog is a ages/train/034.Boxer
![dog3](https://user-images.githubusercontent.com/31853896/81959626-60cd8d80-962d-11ea-979a-bab7150196fd.jpg)

 Hi, This's a human!
If you were a dog, I predict that would be a ... ages/train/044.Cane_corso!!
![191_n](https://user-images.githubusercontent.com/31853896/81959742-91152c00-962d-11ea-8bcd-473a519d2f6f.jpg)
## Summary
There are several state of the arts model we tried. First I gave to shot to OpenCv but it fails when we don't have forward facing faces. Then I tried convolutional Neural Network from scratch with above parameters.It gave an accuracy of 9% which is too low. At last i tried two state of the arts pre-trained model VGG16 and Xception. VGG16 gave an accuracy of 43% where as VGG19 gave an accuracy of 70.9% of validation dataset with 20 epochs and about 30 sec of training on GPU.
