# Breast Cancer Ultrasound Segmentation on 4 Deep Learning Segmentation Frameworks
# Dataset
All these models were tested on the Breast Cancer Ultrasound Dataset found on Kaggle. 
The link to the dataset is https://www.kaggle.com/datasets/aryashah2k/breast-ultrasound-images-dataset
# Dataset Format
Most of these models require the dataset to be in slightly different formats, easiest way to convert the dataset from one format to another is download the dataset from kaggle and upload it to Roboflow workspace. From there you can export the dataset in different formats.

For Segformer, Mask R-CNN, and FCN start a roboflow project on semantic segmentation, upload the dataset, and export it as png segmentation masks.
For segformer add the _classes.csv to both images and masks folders.
For YOLOv8, start a roboflow project on instance segmentation, upload the dataset, and export is as YOLOv8.

# Results
This projects provides a comparative view of these 4 models performing the tast of segmenting the breast cancer tissue in the image.

The results are as follows:
YOLOv8-seg mAP@50%: 99.3%
Mask R-CNN mAP@50%: 95.2%
Segformer mIoU: 77.1%
FCN mIoU: 65.8%

# Model Checkpoints and Inference
All the traained models are on this google drive link: https://drive.google.com/drive/folders/1s_iCNc77am7KRbIMt5V_QCeQ9uJJ6OSc?usp=drive_link

You can download any of these models and test inference on new images or use them for transfer learning on similar data.
