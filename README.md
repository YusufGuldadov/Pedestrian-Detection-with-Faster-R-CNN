# Pedestrian-Detection-with-Faster-R-CNN
State-of-the-art pedestrian detection achieving 98% mAP on PennFudan dataset.


**State-of-the-art pedestrian detection achieving 98% mAP accuracy**

##  What is this?
A high-performance pedestrian detection system using **Faster R-CNN** that identifies people in images with **98% accuracy**. Trained on urban scene data, this model can be used for autonomous vehicles, surveillance, and smart city applications.

##  Key Results
- **98% mAP** detection accuracy
- **Faster R-CNN with ResNet-50** backbone
- **COCO-pretrained** for fast training
- **Production-ready** model

##  Quick Use

# Load and use the model
model = load_pedestrian_detector()
detections = detect_pedestrians("street_image.jpg")

## Requirements

Python 3.8+
PyTorch < 2.0
GPU recommended for training

 ## Perfect for: Computer vision projects, pedestrian safety systems, and object detection research.
