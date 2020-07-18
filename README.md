# face recognition by transfer_learning
This is a part of my MLOPS task provided by Mr. Vimal Daga
In this task, I have created a face recognition model using transfer learning by VGG16 pre-trained weights. 
This model identifies faces of some popular actors such as- matthew mcconaughey, christian bale, leonardo dicaprio and Hugh jackman by transfer learning.
## Steps:
* VGG16 works on images of 244,244,so we have to resize our input images to that size
* Load the pre-trained VGG16 model
* Next we freeze the last 4 layers by setting trainable to **False
* Now make a function to give the top layer that will be ontop of all the bottom layers
* Finnaly we train those layers
* Save the model for further use
