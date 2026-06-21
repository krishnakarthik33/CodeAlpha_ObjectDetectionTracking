# 🎯 Object Detection and Tracking

A real-time Object Detection and Tracking system developed as part of the CodeAlpha Artificial Intelligence Internship.

## 📌 Project Overview

This project uses YOLOv8 and OpenCV to detect and track multiple objects in real-time through a webcam or video file. Each detected object is enclosed within a bounding box and tracked across frames.

## 🚀 Features

- Real-time object detection
- Multi-object tracking
- YOLOv8 pre-trained model
- Bounding boxes and confidence scores
- Webcam support
- Video file support
- Fast and accurate detection

## 🛠️ Technologies Used

- Python
- OpenCV
- YOLOv8
- Ultralytics
- NumPy

## 📂 Project Structure

CodeAlpha_ObjectDetectionTracking/
│
├── app.py
├── requirements.txt
├── yolov8n.pt
├── coco.txt
│
├── videos/
│ └── sample.mp4
│
└── README.md

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/CodeAlpha_ObjectDetectionTracking.git
```

### Navigate to Project Folder

```bash
cd CodeAlpha_ObjectDetectionTracking
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

## 📹 Input Sources

### Webcam

```python
cap = cv2.VideoCapture(0)
```

### Video File

```python
cap = cv2.VideoCapture("videos/sample.mp4")
```

## 🎯 Detectable Objects

YOLOv8 can detect:

- Person
- Car
- Bicycle
- Bus
- Truck
- Dog
- Cat
- Laptop
- Chair
- Bottle
- Mobile Phone

and many more objects.

## 📊 Output

The system displays:

- Object Labels
- Bounding Boxes
- Confidence Scores
- Tracking IDs

in real-time.

## 🏆 Internship Task

Task 4 – Object Detection and Tracking

Completed for the CodeAlpha Artificial Intelligence Internship.

## 👨‍💻 Author

Likith Kumar
