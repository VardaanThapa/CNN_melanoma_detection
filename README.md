# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of 
melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- What is the background of your project?
--- Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential 
to reduce a lot of manual effort needed in diagnosis.

- What is the business probem that your project is trying to solve?
--- We are trying to create a multiclass classification model using a custom convolutional neural network in TensorFlow, 
which accurately predicts Melanoma using image of the cancer. 

- What is the dataset that is being used?
--- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC).


## Conclusions
- CNN model might get overfit if the amount of data is not significant
- Class imbalance can affect the accuracy negatively
- Image augmentation technique can be used to handle both data scarcity and class imbalance problem
- The accuracy and overfit/underfit issue improves with class-rebalance, dropsouts and normalization


## Technologies Used
 - tensorflow : 2.17.1
 - numpy : 1.26.4
 - pandas : 2.2.2
 - matplotlib : 3.7.2


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad along with IIIT-B
- Thanks Shivam Garg (Upgrad instructor) for his guidance


## Contact
Created by Vardaan Thapa [@VardaanThapa] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->
