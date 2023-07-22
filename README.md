# InceptionV3-transferlearning-with-LFW-dataset
This repo contains code for a project using transfer learning with InceptionV3 to identify and name multiple people in an image. The model was trained on the LFW dataset. The project shows the effectiveness of transfer learning in improving facial recognition accuracy.

# Introduction
The goal of this project is to use transfer learning to identify and name multiple people in an image. The model was trained on the LFW dataset. The project shows the effectiveness of transfer learning in improving facial recognition accuracy. 

# Dataset
The dataset used for this project is the Labeled Faces in the Wild (LFW) dataset. The dataset contains more than 13,000 images of faces collected from the web. Each face has been labeled with the name of the person pictured. 1680 of the people pictured have two or more distinct photos in the dataset. The only constraint on these faces is that they were detected by the Viola-Jones face detector. More details about the dataset can be found [here](http://vis-www.cs.umass.edu/lfw/).

# Model
The model used for this project is the InceptionV3 model. The model was trained on the ImageNet dataset. The model was trained to classify images into 1000 classes. The model was trained on 1.2 million images. The model was trained for 2 weeks on two NVIDIA GTX 780Ti GPUs. The model achieved a top-5 accuracy of 93.33%. More details about the model can be found [here](https://arxiv.org/abs/1512.00567).

The model is here tuned to classify the LFW dataset. The model is trained to classify images into approximately 480 classes -> each class is a person in the LFW dataset.

# Results
Eventhough a low accuracy value of 43% is achieved on the dataset training it for more time and fine tuning the model will give us accuracy over 90% this 43% accuracy was achieved in just 21 hours of training on a GPU P100. The model can be trained for more time on a GPU to achieve better results. 

# Help 
I am new to this field and I am still learning. If you have any suggestions or improvements please let me know. I would love to learn from you. 
Feel free to open an issue to discuss any problems you face or any suggestions you have.