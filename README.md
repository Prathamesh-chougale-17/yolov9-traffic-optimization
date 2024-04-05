<!-- write readme for traffic optimisation using yolov9 -->
# Traffic Optimisation using YOLOv9

## Introduction
This project aims to optimise traffic flow by detecting vehicles and traffic lights using YOLOv9. The project is divided into 3 parts:
1. Vehicle Detection
2. Counting Vehicles 
3. Allocating Traffic Lights time based on the number of vehicles detected

## Vehicle Detection
The first part of the project is to detect vehicles using YOLOv9. The model is trained on the [COCO dataset](https://cocodataset.org/#home) and the weights are used to detect vehicles in the video.

## Counting Vehicles
The second part of the project is to count the number of vehicles detected in the video. The number of vehicles detected is used to allocate time to the traffic lights.

## Allocating Traffic Lights time
The third part of the project is to allocate time to the traffic lights based on the number of vehicles detected. The more the number of vehicles detected, the more time is allocated to the traffic lights.

## Conclusion
The project aims to optimise traffic flow by detecting vehicles and traffic lights using YOLOv9. The number of vehicles detected is used to allocate time to the traffic lights. The project can be further improved by training the model on custom dataset and fine-tuning the weights.

## Packages Used
1. PyTorch
2. OpenCV (cv2==4.9.0)
3. Ultralytics==8.1.42

## Installation
1. Clone the repository
2. Create a new conda environment using the following command:
```bash
conda create -n yolov9 python=3.8
```
3. Activate the conda environment using the following command:
```bash
conda activate yolov9
```
4. Install PyTorch using the following command:
```bash
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
```
5. Install OpenCV using the following command:
```bash
conda install conda-forge::opencv
```
6. Install Ultralytics using the following command:
```bash
conda install -c conda-forge ultralytics
```
7. Set the Kernel of traffic_detection.ipynb to yolov9
8. You are all set to run the project.

## Contributor

- [Prathamesh Chougale](https://www.linkedin.com/in/prathamesh-chougale/)