# Convolutional-Neural-Networks-for-Different-Locations-Classification

![image](https://user-images.githubusercontent.com/109751694/209491914-d7b662a5-ba81-491c-a959-06805b8b21d7.png)

# Dataset
countries data collected from Google in a variety of sizes, with 10 classes totaling 650, 65 image per class to train, validate, and test the models. Then some preprocessing was made to standardize images to 3x64x64. Following that, the original dataset was augmented with some spinning, flipping, and shifting.

![image](https://user-images.githubusercontent.com/109751694/209491953-2602fbe1-6855-45a5-98ff-ed51df920f49.png)

# OverView
Building a model that can classify data at different locations from different countries is extremely difficult, especially when using low quality photos that may be insufficiently informative to create a robust general model with high accuracy.

## Introduction
Image classification, localization, image segmentation, and object detection are examples of major problems in computer vision. Among these, image classification is the most fundamental problem. It forms the basis for other computer vision problems. In this project, we assessed a model for recognizing country name by providing an image of a famous places in it, attempting multiple models, comparing between them, and seeking for the champion model.

## Methodology
![image](https://user-images.githubusercontent.com/109751694/209492180-fbb24ffb-6da2-4eea-ab0c-cdea08f75a9a.png)


## Conclusion
Deep Learning-Based Vehicle Classification for Low-Quality Images” paper as a reference to build our models with an extra step by using
data augmentation with the champion model which is “VGG-16 + BL” in our case. Furthermore, we aim to generalize our model by adding more different locations of different countries. Also, try to enhance our model test accuracy by adding more places of the same country
to train our model with. Over and above we intend to build captioning model to describe the image which will help in recognizing the location.

## Results 
![image](https://user-images.githubusercontent.com/109751694/209492502-fe115a95-0b00-461f-96a5-072fc4581117.png)

### Champion Model
![image](https://user-images.githubusercontent.com/109751694/209492541-6f800005-4dc6-4483-9802-e6313a8e89fb.png)

## References

1. He, Tong, et al. Bag of Tricks for Image Classification with Convolutional Neural Networks. arXiv, 5 Dec. 2018. arXiv.org,
https://doi.org/10.48550/arXiv.1812.01187.
2. Tas, Sumeyra, et al. “Deep Learning-Based Vehicle Classification for Low Quality Image Sensors (Basel, Switzerland), vol. 22, no. 13
2022, p. 4740. PubMed,https://doi.org/10.3390/s22134740
