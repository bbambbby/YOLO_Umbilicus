# YOLOv26 Umbilicus Detection for AR-Guided Tele-Palpation

## Project Overview

This project develops a computer vision model to detect the umbilicus from abdominal images using the YOLOv26 object detection architecture.

The work is part of a project on an Augmented Reality (AR)-guided tele-palpation system for telemedicine.

This repository demonstrates the complete workflow for training and evaluating an object detection model for umbilicus localization.

---

## Objective

The objectives of this project are to:

- Develop an object detection model capable of automatically detecting the umbilicus from abdominal images  
- Use the YOLOv26 architecture to localize the umbilicus using bounding box prediction  

---

## Dataset

The dataset was annotated using Roboflow, where bounding boxes were manually drawn around the umbilicus in each abdominal image.

The dataset contains a total of 176 images, divided into training, validation, and test sets:

- **Training set:** 123 images (~70%)  
- **Validation set:** 35 images (~20%)  
- **Test set:** 18 images (~10%)

All images were resized to 640 × 640 pixels and exported in YOLO format, which includes images and corresponding label files containing normalized bounding box coordinates.
Here to access the [DATA SET]( https://drive.google.com/drive/folders/14K-HQpxv69dpJ0g1lqePd0bbalBUiIsx?usp=drive_link)
