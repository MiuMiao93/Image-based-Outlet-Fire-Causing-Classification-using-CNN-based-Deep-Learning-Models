# Image-based-Outlet-Fire-Causing-Classification-using-CNN-based-Deep-Learning-Models
This repository contains the code and dataset for a study exploring the use of deep learning object detection models for finding the source of fire in case of sockets. The study focuses on detecting the origin of fires in multi-socket outlets by classifying them into "burnt-in" and "burnt-out" categories.

## Overview

Accidents caused by electrical device fires are a common and serious issue in the Republic of Korea, resulting in significant harm to both lives and infrastructure. Investigating the cause of these fires involves various authorities. However, the lack of advanced digital forensic tools makes this task challenging.

This project introduces a novel dataset and a suite of CNN models to assist in the identification and classification of fire origins in multi-socket outlets. The dataset contains 6006 images, categorized into "burnt-in" and "burnt-out," and the models tested include:

- YOLOv5
- YOLOv6
- YOLOv8
- Faster-RCNN
- RetinaNet
- SSD

The study found that the YOLOv5s model performed best, achieving 89.1% mAP@0.5 with an inference speed of around 22 fps on an RTX 3050 GPU.

## Key Features

- **Dataset**: 6006 images of post-fire multi-socket outlets.
- **Model Implementation**: Includes implementations of YOLO-series (v5, v6, and v8), Faster-RCNN, RetinaNet, and SSD.
- **Performance Metrics**: Evaluation based on mAP@0.5, model size, and inference time.
- **Application**: The trained models are deployed into application for further evaluation.

## Application Demonstration

Here's a demonstration of the project:

![Demo of Application](https://github.com/MiuMiao93/Image-based-Outlet-Fire-Causing-Classification-using-CNN-based-Deep-Learning-Models/blob/main/demo_app.gif)

## Availability OF Data and materials
Please contact the corresponding author for data requests. We use Visual Studio Code as coding IDE and Jupyter Notebook as training IDE, which includes support for Python programming. Our demo application is developed with Python language as back-end and PyQT5 as front-end GUI. 
