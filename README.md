# Garbage Detection Using YOLOv8
## Project Overview

This project focuses on detecting different types of garbage using **YOLOv8** object detection. The goal is to classify and locate waste materials in images or live videos to assist in automated waste management solutions.

**Key Features:**
- Detects multiple classes of garbage: Plastic, Metal, Glass, Paper, Organic, etc.
- Real-time detection on images and videos.
- Implemented using **YOLOv8** for high accuracy and speed.
- Can be extended to a web or mobile demo for practical usage.

---

## Dataset

The dataset used is a custom garbage dataset with the following classes:

| Class    | Examples |
|----------|----------|
| Plastic  | Bottles, wrappers |
| Metal    | Cans, spoons, utensils |
| Glass    | Bottles, jars |
| Paper    | Newspapers, cardboard |
| Organic | Food waste, leaves |

**Notes:**
- Dataset is split into **training** and **testing** sets.
- Images are annotated in **YOLO format** (`.txt` files with bounding boxes).

---

## Requirements

- Python 3.8+
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV
- Matplotlib
- Numpy


```bash
pip install -r requirements.txt
