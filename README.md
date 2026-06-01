# Bangla License Plate Detection using YOLOv9

This project focuses on detecting Bangla vehicle license plates using the YOLOv9 object detection model. The model was trained on a Bangla license plate dataset and achieved strong detection performance.

## Project Overview

License plate detection is an important computer vision task used in traffic monitoring, smart parking systems, vehicle tracking, and automatic number plate recognition systems. In this project, YOLOv9 was used to detect Bangla license plates from vehicle images.

## Model

- Model: YOLOv9
- Task: Object Detection
- Target Object: Bangla License Plate
- Platform: Kaggle
- Framework: Python, PyTorch, YOLO

## Dataset Summary

- Total Images: 4,592
- Total Bounding Boxes: 24,174
- Annotation Format: YOLO format
- Classes: License Plate

## Training Details

- Epochs: 50
- Image Size: 640
- Model Type: YOLOv9
- Training Environment: Kaggle Notebook

## Best Model Performance

| Metric | Score |
|---|---:|
| Precision | 0.980 |
| Recall | 0.976 |
| mAP@50 | 0.992 |
| mAP@50-95 | 0.645 |

## Key Features

- Bangla license plate detection
- YOLO-format dataset preparation
- Model training on Kaggle
- Model validation and performance evaluation
- Best model weight export
- Suitable for further OCR-based number plate recognition

## Technologies Used

- Python
- YOLOv9
- PyTorch
- OpenCV
- Kaggle
- Computer Vision
- Deep Learning

## Project Workflow

1. Dataset preparation
2. YOLO annotation formatting
3. Model training using YOLOv9
4. Model validation
5. Performance evaluation
6. Best model weight selection
7. Future scope: OCR integration for Bangla license plate text recognition

## Results

The YOLOv9 model achieved excellent detection performance with high precision and recall. The model successfully detects Bangla license plates from vehicle images and can be used as a base model for automatic Bangla license plate recognition systems.

## Future Improvements

- Add OCR for Bangla license plate text recognition
- Deploy the model using Flask or Streamlit
- Convert the model for real-time detection
- Improve detection on low-light and blurry images
- Create a complete ANPR system

## Author

Developed by DHD

## Keywords

YOLOv9, Bangla License Plate Detection, Object Detection, Computer Vision, Deep Learning, Kaggle, PyTorch, Vehicle Detection, License Plate Recognition
