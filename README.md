
# 🔥 Real-Time Fire Detection Using YOLOv8, OpenCV & Deep Learning

<div align="center">

<img src="https://img.shields.io/badge/AI-Powered-red?style=for-the-badge" />
<img src="https://img.shields.io/badge/YOLOv8-Ultralytics-green?style=for-the-badge" />
<img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-blue?style=for-the-badge" />
<img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-orange?style=for-the-badge" />
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" />

<br><br>

# 🚨 AI-Based Intelligent Fire Detection & Safety Monitoring System

### Real-Time Fire Detection through Computer Vision and Deep Learning

---

### 🎓 Digital Image Processing (DIP) Semester Project  
### 👨‍💻 Developed by Ghayoor Khan

</div>

---

# 📖 Introduction

Fire accidents remain one of the major causes of damage to human life, industrial infrastructure, forests, and public property worldwide. Traditional fire alarm systems mainly rely on smoke sensors and heat detectors, which may fail in large-scale environments or open spaces.

With the advancement of **Artificial Intelligence**, **Computer Vision**, and **Deep Learning**, visual fire detection systems have become more accurate, scalable, and intelligent.

This project presents a **Real-Time Fire Detection System** developed using:

- YOLOv8 (You Only Look Once)
- OpenCV
- PyTorch
- Python

The system detects fire directly from live webcam video streams using AI-powered object detection techniques.

The project combines concepts of:
- Digital Image Processing
- Computer Vision
- Deep Learning
- Real-Time Object Detection
- Intelligent Surveillance Systems

---

# 🎯 Project Objectives

The primary objectives of this project are:

✅ Detect fire in real time using Artificial Intelligence  
✅ Apply Digital Image Processing concepts practically  
✅ Train a custom YOLOv8 object detection model  
✅ Build an intelligent safety monitoring system  
✅ Explore real-world Computer Vision applications  
✅ Improve understanding of Deep Learning workflows  

---

# 🧠 Core Technologies Used

| Technology | Purpose |
|---|---|
| Python 3.10 | Core programming language |
| YOLOv8 | Real-time object detection |
| OpenCV | Video processing & visualization |
| PyTorch | Deep learning framework |
| NumPy | Numerical operations |
| Roboflow | Dataset management & annotation |
| VS Code | Development environment |

---

# 🔍 About YOLOv8

YOLOv8 (You Only Look Once Version 8) is a state-of-the-art real-time object detection model developed by Ultralytics.

It is widely used because of:
- high speed,
- strong accuracy,
- lightweight architecture,
- and real-time performance.

In this project, YOLOv8 was trained specifically to detect fire from images and live video streams.

---

# 📂 Dataset Collection & Preparation

## 🌐 Dataset Source

The fire dataset used in this project was collected from:

### 🔗 Roboflow

Roboflow is a professional Computer Vision platform used for:
- dataset management,
- image annotation,
- preprocessing,
- augmentation,
- and YOLO dataset export.

The dataset contained:
- fire images,
- labeled annotations,
- training images,
- validation images,
- and testing samples.

---

# 🗃️ Dataset Structure

The dataset was organized according to YOLO object detection format.

```bash
dataset/
│
├── train/
│   ├── images/
│   ├── labels/
│   └── labels.cache
│
├── valid/
│   ├── images/
│   ├── labels/
│   └── labels.cache
│
├── test/
│   ├── images/
│   └── labels/
│
└── data.yaml
````

---

# 📑 About data.yaml

The `data.yaml` file contains:

* dataset paths,
* class names,
* training configuration,
* and validation information.

It acts as the main configuration file for YOLOv8 training.

---

# 🧪 Project Workflow

The system works in two major phases:

---

# 1️⃣ Training Phase

During training:

✔ Fire dataset loaded
✔ YOLOv8 pretrained model initialized
✔ Dataset processed into batches
✔ Deep learning training performed
✔ Model optimized over multiple epochs
✔ Best weights saved automatically

---

# 📊 Model Training

The YOLOv8 model was trained using:

* custom fire dataset,
* GPU/CPU processing,
* object detection techniques,
* and supervised learning methods.

### Training Details

| Parameter      | Value          |
| -------------- | -------------- |
| Model          | YOLOv8n        |
| Epochs         | 30             |
| Framework      | PyTorch        |
| Detection Type | Fire Detection |
| Dataset Format | YOLO           |

---

# 💾 Trained Weights

After successful training:

```bash
best.pt
```

was generated as the best-performing trained model.

Additional files generated:

* training graphs,
* metrics,
* loss curves,
* validation results,
* and inference outputs.

---

# 📂 Training Output Structure

```bash
runs/
└── detect/
    ├── train/
    └── train2/
        ├── weights/
        │   ├── best.pt
        │   └── last.pt
        │
        ├── args.yaml
        ├── results.csv
        ├── confusion_matrix.png
        ├── labels.jpg
        └── training graphs
```

---

# 2️⃣ Real-Time Detection Phase

In the detection phase:

🎥 Webcam captures live video
🧠 YOLOv8 processes each frame
🔥 Fire regions detected instantly
📦 Bounding boxes drawn
📈 Confidence scores displayed

The system performs detection in real time with smooth visualization.

---

# ⚙️ Detection Pipeline

```text
Webcam Input
      ↓
Frame Capture
      ↓
YOLOv8 Inference
      ↓
Fire Detection
      ↓
Bounding Box Visualization
      ↓
Real-Time Output Display
```

---

# 🛠️ Installation Guide

## Step 1 — Clone Repository

```bash id="x1m4pv"
git clone https://github.com/your-username/Real-Time-Fire-Detection-Using-YOLOv8-and-OpenCV.git
```

---

## Step 2 — Navigate to Project Folder

```bash id="g8q2tz"
cd Real-Time-Fire-Detection-Using-YOLOv8-and-OpenCV
```

---

## Step 3 — Install Dependencies

```bash id="m7n5kc"
pip install -r requirements.txt
```

---

# 📦 requirements.txt

```txt
ultralytics
opencv-python
numpy
```

---

# ▶️ Running the Project

# 🔹 Train Custom Model

```bash id="p3d8yf"
python train.py
```

---

# 🔹 Start Real-Time Fire Detection

```bash id="r5x1lj"
python detect.py
```

---

# 📸 System Output

The system generates:

✅ Real-time fire detection windows
✅ Bounding boxes
✅ Confidence score display
✅ Trained model weights
✅ Training graphs & metrics
✅ Detection visualizations

---

# 🌍 Real-World Applications

This system can be used in:

🏭 Industrial safety monitoring
🌲 Forest fire surveillance
🏢 Smart building systems
🚨 Emergency alert systems
🏠 Home automation
📹 Intelligent CCTV monitoring
🛡️ Public safety infrastructure

---

# 🚀 Future Improvements

This project will continue to evolve into a more intelligent smart safety system.

Planned future enhancements include:

🔔 Automatic alarm integration
📱 SMS and mobile notifications
☁️ IoT-enabled monitoring
🌫️ Smoke detection capability
📷 Multi-camera CCTV support
🌐 Web dashboard integration
🧠 Improved AI model accuracy
📡 Cloud-based monitoring system
🚨 Emergency response automation

---

# ⚡ Advantages of the System

✔ Real-time detection
✔ AI-powered monitoring
✔ Faster than traditional systems
✔ Cost-effective solution
✔ Scalable architecture
✔ Intelligent surveillance support

---

# ⚠️ Current Limitations

* Detection quality depends on dataset quality
* Extreme lighting conditions may affect accuracy
* Smoke-only situations remain challenging
* Performance varies depending on hardware

---

# 🧠 Skills Demonstrated

This project demonstrates practical expertise in:

* Artificial Intelligence
* Computer Vision
* Deep Learning
* YOLOv8 Model Training
* Object Detection
* OpenCV Integration
* Dataset Preparation
* Real-Time AI Systems
* Digital Image Processing
* Python Development

---

# 🎓 Academic Contribution

This project was developed as a major semester project for:

# Digital Image Processing (DIP)

The project combines theoretical image processing concepts with practical AI implementation to solve real-world safety problems.

It reflects:

* practical learning,
* research mindset,
* implementation ability,
* and problem-solving skills.

---

# 👨‍💻 Developer

# Ghayoor Khan

Computer Science Student
Passionate about:

* Artificial Intelligence
* Computer Vision
* Deep Learning
* Intelligent Safety Systems

---

# 📚 References

* Ultralytics YOLOv8 Documentation
* OpenCV Official Documentation
* PyTorch Documentation
* Roboflow Dataset Platform

---

<div align="center">

# ⭐ AI-Powered Smart Fire Detection System

### Future intelligent surveillance and emergency monitoring solution

If you found this repository useful, consider giving it a star ⭐

</div>
