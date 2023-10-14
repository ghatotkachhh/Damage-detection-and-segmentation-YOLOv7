# Damage-detection-and-segmentation-YOLOv7
Hackathon - Cosmoligence\n
Data - https://eod-grss-ieee.com/dataset-detail/OWlUN0k3T0tnNVo2Rk5mNjFxTkhwZz09\n
Data description - A train folder with images and a json file for labelling description 
Step1 - To create the data usable for yolo format which is a train folder with two subfolders image and labels both containing same number of files a text and a jpg file, text file containing labeling description
Step2 - To create yolo usable format, a python code was used
Step3 - Loading the yolo v7 widths and model in google colab using the github repository (https://github.com/WongKinYiu/yolov7)
Step4 - Modifying the data.yaml file to train it for custom dataset that is for only 4 classes
Step5 - Mounting the drive in google colab and uploading the dataset that is the train and val folder containing label and image subfolder each
Step6 - Uploading the initial weights of the yolov7 model from https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt
Step7 - Training the model for 64 epochs and testing it with 0.5 confidence
