# Skin-Lesion-Classification-using-Deep-Learning

## Introduction 

A transfer learning apporach is used for the classification of Skin Lesions. A VGG-16 architecture and weights pre-trained from VGG-model is used for the classification. 
This work was part of Challenge in University of Girona as part of Medical Imaging and Applications(MAIA) course. In the first challenge, the classification is binary task, 
where it is to classify skin lesion images into Benign and Malignant. In the second challenge, the classification is 3 class problem, where the problem is to classify the skin lesion images to 
melanoma vs benign keratosis vs basal cell carcinoma.


The project is carried out in Python3 with Tensorflow framework and Keras API. 
## Dataset
The lesion images come from the HAM10000 Dataset. The subset of the data from HAM10000 was used for training the model. 6000 images were randomly split into Training and Validation and 1015 images were used for testing for Challenge 1. For challenge 2, 2500 images of all 3 classes were randomly split into Training and Validation and 226 images were used for testing purpose.  


## Dependencies
- Python 3
- Keras
- Jupyter Notebook 


