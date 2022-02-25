# AirCraft-Detection-Using-Mask-RCNN


For this Project I have used Mask-RCNN for the purpose of Aircraft Detection.

First We will try to understand what is Mask R-CNN?

-The Mask R-CNN model introduced in the 2018 paper titled “Mask R-CNN” is the most recent variation of the family models and supports both object detection and object    segmentation.

-Mask-RCNN is nothing but an extension of R-CNN that adds an output model for predicting a mask for each detected object.    


*Steps Involved :
 
 1) First we will import all the required libraries that we will require in this mini project.
 2) In this I am extracting the mrcnn zip file from  https://pysource.com/extra_files/Mask_RCNN_basic_1.zip This file consistes all the files required.
 3) We are using tensorflow as the backend in this project.
 4) We cannot directly use the zip file on colab notebook, so we have to unzip it.
 5) For creating the dataset I collected around 25 images of an aircraft for training purpose.
 6) I used an AI website named makesence.ai for labelling the aircraft and creating the annotations.
 7) For labelling I used the polygon feature, An important part to remember while labelling using a polygon we need to end the label at the starting point again in order to complete the entitre polygon.
 8) After the labelling is done we need to export the file with an extension coco json format.
 9) Then we need to upload the dataset file and the annotation files on the colab notebook.
 10) Once the file is uploaded we need to extract the images that we are using to train. So for this purpose we are using the inbuilt function named as extract_images.
 11) After extracting images we can now check and display sample images from the dataset how it is working.
 12) Now we can start training of our model. Basically it needs 5 epochs to train which can take a very long time so only 2 epoch can be enough to detect our object.
 13) The results that are generated are quite amazing which shows that mask-rcnn is really powerful in object detection.

      
