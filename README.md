# CV_SP23

## Introduction:
A popular method for classifying images is BoVW. The concept behind this method is comparable to NLP's "bag of words," except that in this technique, image features are used as words.
Bag of Visual Words (BoVW) is one of the pre-deep learning techniques used in computer vision to create picture embeddings. BoVW can be used for object detection, picture classification, and content-based image retrieval.

A summary of the five stages involved in comparing images with the bag of visual words approach is as follows:

1. Extrapolate visual details

2.  Make graphic language

3.  Utilize these visual terms to create sparse frequency vectors

4.    Using tf-idf, adjust frequency vectors for pertinent data

5.    Utilize similarity or distance measures to compare vectors




In this assignment/project two datasets are trained by using SIFT feature detector and using classifiers such as SVM and Random Forest.

The following Image illustrates the methodology of BOVW: 

![The-procedure-of-scene-classification-based-on-the-bag-of-visual-words-BoVW-model](https://user-images.githubusercontent.com/54496815/224587502-2d721fff-7eae-458d-b4c9-8e519b9307fa.png)

## Instructions:
This code can be set up using Google colab or by using Jupyter Notebook. Dataset is uploaded on Google drive and can be mounted by using Google colab.

## Instructions for Training and Testing:
Train and Testing Data is uploaded on Google drive but can be made public if requested or can be accessed through a little searching.

Dataset is uploaded on Google drive and can be mounted by using Google colab.

The train and test for the flower dataset is 80/20.

## Visual Results:

The following Result is of Object Dataset being made keypoints of using SIFT:

![Obj-SIFT](https://user-images.githubusercontent.com/54496815/224585989-931bd3fe-43cb-473a-84e4-8e7351042e4d.png)

he following Result is of Flower Dataset being made keypoints of using SIFT:

![Flower-SIFT](https://user-images.githubusercontent.com/54496815/224586217-7878074e-4320-4b0d-a1de-b25f4696b4d6.png)

![Complete-Vocabulary](https://user-images.githubusercontent.com/54496815/224586306-61f253d0-3819-4324-973c-3d254f359ce8.png)

![Frequencies](https://user-images.githubusercontent.com/54496815/224586316-44b4a864-7c1e-4114-8ee9-c8d7762d127a.png)

![Obj-Histogram](https://user-images.githubusercontent.com/54496815/224586324-df3bf1f2-ed24-4255-8db0-49c8a696ca16.png)

## Qualitative Results:

![Obj-Classification(Accuracy)](https://user-images.githubusercontent.com/54496815/224586432-c9effa8f-089b-46cb-9e75-ce87a00c4a43.png)
