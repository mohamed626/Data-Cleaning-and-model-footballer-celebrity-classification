# Data-Cleaning-and-model-for-footballer-celebrity-classification
- we need to build end to end machine learning project or data science project for footballer celebrity image classification, but first we need download the dataset and cleaning it , and build the machine learning model.
- There are 4 different ways of collecting data for our project:
   1.Manually download images from google images.
   2.Use python and web scrapping to automate downloading images from google (https://towardsdatascience.com/image-scraping-with-python-a96feda8af2d)
   3.Use a chrome extention called fatkun
   4.Buy these images from third party vendor who is selling images database. 
  I use fatkun and download set of images for 5 footballer and upload this datasett in google drive which this link                                                         (https://drive.google.com/drive/folders/1_ZG4u_DBFFdn1WPtdOzMrV3QXnqKxCB4?usp=sharing).you can download it.

- now we are going to clean images that it is suitable to train our classifier. We mostly identify a person in a photo with a face. Hence we will use opencv and a technique called haar cascades to detect if a face and two eyes are clearly visible or not. If they are than we keep the image otherwise we discard the image. Majority of the data cleaning work will be done using python code but there will be some cleaning work that we will have to do manually
- we will use cropped images and apply wavelet transform to extract meaning features that can help with image identification. 
- Using wavelet transform and a raw pixel image we will create our X and use class labels as y. These X and y will be used for model training. 
- Once we have X and y after applying feature engineering techniques, we can now create simple SVM model to get a feel of how it is going to perform on image classification. 
- the accurcy from svc model is 0.82, bacause the dataset is small


# In short, we're going to do this. 
1) How to build end to end machine learning or data science project
2) Use Opencv library for face and eyes detection
3) data cleaning using opencv face detection and feature engineering using wavelet transforms
4) Model building using SVM
