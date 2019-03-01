# Dog-Breeds-Prediction
Predict the dogs breeds and fun application by finding dogs, and humans in images then finding the most similar dog breed to a human in an image

**Introductory abou the repository:**
We first do dog detection in images
then human face detection in images using Haar cascade (from opencv)
then we create a classifier using vgg16
then a classifier from scratch
then a classifier suing pretrained models
Later we create a small algorithm for a fun application where we test new images:
  if we find a dog, we tell users it is a dog and print the name of the most similar breed
  if we find a human, we tell users it is a human and print the name of the most similar dog breed
  if we find something else, we tell users it is non of the above.

In this repository Pytorch is used.
**Requirments:** 
 -torch
 -Numpy
 -opencv (cv2)

**Get the data**
In your terminal (or in Google Colab code cell) do the follwoin to get the dogs data set
1. to install the data as a zip file (named dogImages) type:
    !wget https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip
2. to unzip the installed zip file type:
    !unzip dogImages.zip
3.Now you should see the ZIP file being unzipped, check by typing:
    !ls
    you will see dogImages dogImages.zip images README.md
4. Type:
    !rm dogImages.zip to remove the zip file (we do not need it anymore)
5. You can see what is inside the dogImages file type:
    !ls dogImages
    You get 'train, test, valid'
Do the same to get the humen data set:
1. to install the data as a zip file (named dogImages) type:
    !wget https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip
2. to unzip the installed zip file type:
    !unzip lfw.zip
3.Now you should see the ZIP file being unzipped, check by typing:
    !ls
    you will see dogImages lfw.zip lfw images README.md
4. Type:
    !rm lfw.zip to remove the zip file (we do not need it anymore)
5. You can see what is inside the dogImages file type:
    !ls lfw
    You get 'train, test, valid'
    
   
    
