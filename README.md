# Electronics Components Object Detection with YOLOv11

This repository contains a fine-tuned YOLOv11 model for detecting various electronics components. The model is trained on the ElectroCom61 Dataset and can be used to detect components such as resistors, capacitors, transistors, and more in images.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model Training](#model-training)
- [Credits](#credits)

---

## Overview

The goal of this project is to create a deep learning model capable of accurately identifying and localizing electronic components within images. Leveraging YOLOv11's state-of-the-art architecture, the model can detect multiple component types with high precision, making it suitable for use in automated inspection and quality control for electronics manufacturing.

## Dataset

The model was trained on the ElectroCom61 Dataset, which includes labeled images of various components with over 61 classes. Each component is annotated with bounding boxes and class labels, facilitating object detection tasks.

### Classes

The dataset includes the following classes (components):
- back_bumper
- back_door
- back_glass
- back_light
- front_bumper
- front_door
- front_glass
- front_light
- hood

## Installation

To use this project, ensure you have Python and the necessary dependencies installed. Follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Tejax-v2/Car-Components-Segmentation.git
    cd Car-Components-Segmentation
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
4. **Dataset Preparation**:
   Ensure the Car parts Dataset is in the working directory.

## Model Training

The model is trained using YOLOv11, with adjustments to hyperparameters specific to segmenting components. 

Follow the notebook `YOLOv11-Instance-Segmentation.ipynb` for further instructions

## Credits
- Dataset: [ElectroCom61](https://universe.roboflow.com/segmentation-9q8ob/car-parts-llqro/dataset/1)
- Reference: [Roboflow](https://github.com/roboflow/notebooks/blob/main/notebooks/train-yolov8-instance-segmentation-on-custom-dataset.ipynb)
- Model: [Ultralytics](https://github.com/ultralytics/ultralytics)
