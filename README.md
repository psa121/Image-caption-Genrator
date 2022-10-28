# Image-caption-Genrator
Image caption generator is a process of recognizing the context of an image and annotating it with relevant captions using deep learning, and computer vision. It

# Dataset
The Flickr8K dataset is used for the model training of image caption generators. The dataset can be downloaded directly from the below links. The downloading process takes some time due to the large size(1GB) of the dataset. In the below image you can check all the available files of the Flickr_8k_text folder. The most important file is Flickr 8k.token which is storing all the image names with the captions respectively. 8091 images are stored inside the Flicker8k_Dataset folder and the text files with captions of images are stored in the Flickr_8k_text folder.

https://www.kaggle.com/datasets/adityajn105/flickr8k

# vgg 16 transfer learning

![download](https://user-images.githubusercontent.com/96285947/198582206-021a09cd-1682-4962-a9a6-17b5b14352ba.png)


# Prediction

generate_caption("1001773457_577c3a7d70.jpg")

---------------------Actual---------------------

startseq black dog and spotted dog are fighting endseq

startseq black dog and tri-colored dog playing with each other on the road endseq

startseq black dog and white dog with brown spots are staring at each other in the street endseq

startseq two dogs of different breeds looking at each other on the road endseq

startseq two dogs on pavement moving toward each other endseq

--------------------Predicted--------------------

startseq two dogs play with each other in the grass endseq

![download (1)](https://user-images.githubusercontent.com/96285947/198582458-9b3f9c16-09b4-46e2-8faa-ea7e84fe7298.png)

