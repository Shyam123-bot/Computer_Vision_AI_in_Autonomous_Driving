# Semantic Segmentation and Object Detection for Self-Driving Cars

This repository showcases the implementation of both **Semantic Segmentation Model** and **Object Detection Models** for Self-Driving Cars.

## Introduction

Semantic segmentation and object detection are critical tasks for enabling self-driving cars to perceive and navigate their surroundings safely.

### Semantic Segmentation

Semantic segmentation involves labeling each pixel in an image with its corresponding object class. This detailed understanding of the road scene aids in safe navigation and decision-making.

### Object Detection

Object detection is a fundamental computer vision task that involves identifying and locating objects of interest within an image. For self-driving cars, object detection helps in identifying various obstacles, pedestrians, other vehicles, and road signs in the environment.

## U-Net Architecture for Semantic Segmentation

The U-Net architecture is employed for semantic segmentation due to its effectiveness in capturing spatial information. It features a contracting path for context extraction and an expansive path for accurate segmentation.

## YOLOv3 and for Object Detection

For object detection, both YOLOv3 is utilized. YOLO (You Only Look Once) models are chosen for their efficiency and accuracy. They divide an image into a grid and predict bounding boxes and class probabilities for objects in each grid cell.

## Dataset

The project utilizes the following datasets from Kaggle:
- For semantic segmentation: [Semantic Segmentation for Self Driving Cars](https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge).
- For object detection: [Lyft 3D Object Detection for Autonomous Vehicles](https://www.kaggle.com/competitions/3d-object-detection-for-autonomous-vehicles).

## Results

### U-Net Semantic Segmentation
- Training accuracy: 98.02%
- Validation accuracy: 97.78%

- Loss and Accuracy curves
  ![image](https://github.com/Shyam123-bot/Computer_Vision_AI_in_Autonomous_Driving/assets/61462986/a54b5c42-653b-44c1-a4c1-43c512d5be81)


- Sample Segmentation Results:
  ![image](https://github.com/Shyam123-bot/Computer_Vision_AI_in_Autonomous_Driving/assets/61462986/2e216e8b-196b-440a-8a90-62a4b5376759)

  ![image](https://github.com/Shyam123-bot/Computer_Vision_AI_in_Autonomous_Driving/assets/61462986/8a3c4f57-42b0-44bd-a039-eff8d42cc6f3)


### YOLOv3 Object Detection
- Sample Object Detection Result:
  ![image](https://github.com/Shyam123-bot/Computer_Vision_AI_in_Autonomous_Driving/assets/61462986/b3b4cf85-b089-4e2f-a44d-82673b9c04f9)



The `code` folder contains model codes. Explore more results and the models' performance in the project's Jupyter Notebook.
You can find more models on my [Kaggle profile](https://www.kaggle.com/sudoshivam).
