# Multi-cam-object-tracking-and-Re-Identification
Multi camera person tracking and re-identifying person if appears in another camera. This project uses MOT concept and reid for and re-identify human ID IT uses YOLOv3 or v4 for detection , Deep-sort for tracking, and Torch-reid library for Re-Identification

## Weights
Download [YOLOv3](https://drive.google.com/file/d/1a7JI-A920lrdt6OKya-qCXx-5ZUWvkMg/view?usp=sharing) or [YOLOv4](https://drive.google.com/file/d/1pwFo4aHKPi0ztpL5tEYaXIr8RltYYQeY/view?usp=sharing), [Torch-Reid](https://drive.google.com/open?id=15Ayri_sHtrctJ1Zb8qERjvdi66y6QaI4)

Put both models into \model_data\models\

## Demo
try out your own videos by running demo.py. Under the directory \videos\output, results will be stored. You should specify the path of the videos and the version of YOLO you would like to use (v3 or v4)

Check .ipynb for reference
