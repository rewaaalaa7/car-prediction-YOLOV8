# Car and Traffic Light Object Detection with YOLOv8

## Overview

This project involves training a YOLOv8 model for car and traffic light object detection using the Ultralytics framework. The model is trained on a dataset of images containing cars and traffic lights, with bounding box annotations.

## Highlights

- **Preprocessing**: Preprocessed and normalized bounding box coordinates.
- **Training**: Trained the model for 20 epochs with early stopping.
- **Performance**: Achieved a mAP50 of 0.682 and mAP50-95 of 0.419 on the validation set.
- **Experiment Tracking**: Integrated MLflow for experiment tracking and logging.
- **Visualization**: Visualized results using Matplotlib.

## Setup

### Prerequisites

- Python 3.10 or higher
- GPU with CUDA support (optional but recommended for faster training)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/car-traffic-light-detection.git
   cd car-traffic-light-detection
2. Install the required packages:
   ```bash
   pip install -r requirements.txt

### Dataset

The dataset should be organized as follows:

data/
├── train_data/
│   ├── images/
│   └── labels/
├── val_data/
│   ├── images/
│   └── labels/
└── yolo.yaml

### Results

The model achieved the following performance metrics on the validation set:

mAP50: 0.682
mAP50-95: 0.419

### Visualization

The results are visualized using Matplotlib, showing bounding boxes and confidence scores on detected objects.

### Future Work

Improvement: Further tune the model to improve mAP50-95.
Expansion: Apply these skills to more complex computer vision tasks.

### Contributing

Feel free to contribute to this project by opening issues or submitting pull requests.

### License
This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgments

Ultralytics for the YOLOv8 framework.
MLflow for experiment tracking and logging.
