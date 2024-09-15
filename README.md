# Breast-Cancer-Ultrasound-Segmentan-using-4-Deep-Learning-Frameworks

All these models were tested on the Breast Cancer Ultrasound Dataset found on Kaggle. 
The link to the dataset is https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset
Most of these models require the dataset to be in slightly different formats, easiest way to convert the dataset from one format to another is download the dataset from kaggle and upload it to Roboflow workspace. From there you can export the dataset in different formats.
For Segformer, Mask R-CNN, and FCN start a roboflow project on semantic segmentation, upload the dataset, and export it as png segmentation masks.
For segformer add the _classes.csv to both images and masks folders.
For YOLOv8, start a roboflow project on instance segmentation, upload the dataset, and export is as YOLOv8.
This projects provides a comparative view of these 4 models performing the tast of segmenting the breast cancer tissue in the image.
The results are as follows:
