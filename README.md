# Face Recogntion using PCA and SVM

## Introduction 
This project showed fundamentals of PCA and SVM algorithms and combined them to recognize human faces. 

## General info 
- Language: Python 
- Dataset: Labeled Faces in the Wild (LFW) 
- Technique: PCA and SVM

## Repository's structure
- `intro_PCA.ipynb`: fundamentals of PCA using sklearn. 
- `intro_SVM.ipynb`: fundamentals of SVM using sklearn.
- `face_recog.ipynb`: combine PCA and SVM to recognize faces. 
- `requirements.txt`: essential packages of the project. 

## Details on face recognition
- Dimensionality reduction: used PCA to extract 150 features on human faces - the results are called *eigenfaces*.
- Built some human faces from eigenfaces and showed the information (variance) retained. 
- Built model with PCA as preprocessor and SVM as classifier and made pipeline. 
- Used grid search and cross validation to select parameters of the classifier. 
- Predicted and assessed the accuracy of the model. 

Here are the eigenfaces obtained from using PCA with 150 components:

![eigenfaces](https://github.com/haongnd2280/Face-Recognition-using-PCA-and-SVM/blob/main/images/eigenfaces.png)

and some image reconstruction from eigenfaces: 

![reconstruction](https://github.com/haongnd2280/Face-Recognition-using-PCA-and-SVM/blob/main/images/eigenfaces_reconstruct.png)

and some predictions using SVM:

![predict](https://github.com/haongnd2280/Face-Recognition-using-PCA-and-SVM/blob/main/images/predict.png)
