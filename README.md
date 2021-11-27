# VGG16-Chest-CT-Scan-Classification


# Tensorflow based Chest-CT-Scan-Classification
# Objective
To use Computer Vision techniques of Deep Learning to correctly identify & classify Chest CT Scan into:
  Adeno Carcinoma, Large Cell Carcinoma, Normal, and Squamous Cell Carcinoma.
  
I have build a CNN model that would classify the chest CT scan dataset into 4 categories mentioned above. I have used VGG-16 model architecture and weights to train the model for this multi-classification problem. 
Metric used to justify model performance: Accuracy


<p align="center">
    <img width="700" height="300" src = 'https://github.com/pranavtushar/VGG16-Chest-CT-Scan-Classification/blob/main/Images/adeno-carcinoma.png'
</p>

<p align="center">
    <img width="700" height="300" src = 'https://github.com/pranavtushar/VGG16-Chest-CT-Scan-Classification/blob/main/Images/large-cell-carcinoma.png'
</p

  <p align="center">
    <img width="700" height="300" src = 'https://github.com/pranavtushar/VGG16-Chest-CT-Scan-Classification/blob/main/Images/normal.png'
</p>
    <p align="center">
    <img width="700" height="300" src = 'https://github.com/pranavtushar/VGG16-Chest-CT-Scan-Classification/blob/main/Images/squamous-cell-carcinoma.png'
</p>

To use these images in our Deep Learning Model, we need to pre-process these images first.

<p align="center">
    <img width="750" height="200" src = 'https://github.com/pranavtushar/VGG16-Chest-CT-Scan-Classification/blob/main/Images/pre-processing.png'
</p>
  
Data Augmentation is used to increase the size of training dataset, and for improving deep learning robustness.
  <p align="center">
    <img width="750" height="200" src = 'https://github.com/pranavtushar/VGG16-Chest-CT-Scan-Classification/blob/main/Images/data-augmentation.png'
</p>
<!-- <p> Model Architecture </p>
    
   <p align="center">
    <img width="750" height="200" src = 'https://github.com/pranavtushar/VGG16-Chest-CT-Scan-Classification/blob/main/Images/model.png'
</p> -->
 <p> Evaluation Parameters</p>
     
   <p align="center">
    <img width="750" height="200" src = 'https://github.com/pranavtushar/VGG16-Chest-CT-Scan-Classification/blob/main/Images/evaluation-parameters.png'
</p> 
          
          
<p> Conclusion </p>
    
In this project, I have used VGG 16 Convolutional Neural Network Model to classify the Chest CT-Scan of a subject into 4 different classess. Accuracy of the model can be increased by using a increasing the size of the dataset,or by generating synthetic datasets using GANs, by tuning the hyperparameters and by using state of the art CNN models like Attention based CNN, Vision Transformers, etc.
