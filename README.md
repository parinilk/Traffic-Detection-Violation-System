# 🚦 Traffic Signal Violation Detection System (TSVDS)

## 📖 Introduction

The Traffic Signal Violation Detection System (TSVDS) is an advanced computer vision-based project designed to automatically detect and report traffic signal violations at intersections. By leveraging state-of-the-art object detection and image processing techniques, TSVDS monitors vehicle behavior in real-time and identifies potential violations such as red light running and improper lane usage.

## ✨ Features

- 🚗 **Real-time object detection**: Utilizes deep learning models to detect and track vehicles, pedestrians, and other objects on the road in real-time.
- 🚨 **Violation detection**: Identifies traffic violations using sophisticated image processing techniques.
- 🎥 **Video recording**: Captures and stores video evidence of detected violations for further analysis and potential law enforcement actions.
- 🖥️ **User-friendly interface**: Includes an intuitive graphical interface for easy system operation and monitoring.

## 🛠️ How It Works

1. **Object Detection**: Employs a pre-trained deep learning model (YOLOv3) to detect vehicles and pedestrians in the video feed.
2. **Violation Detection**: Analyzes object positions and traffic signal status to determine if a vehicle has violated any traffic rules.
3. **Alerts and Recording**: Triggers alerts and records video segments when violations are detected, including license plate information for identification.
4. **User Interface**: Provides access to live video streams, recorded violations, and system settings through a graphical interface.

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- OpenCV
- TensorFlow
- Keras
- Tkinter
- Pillow
- Imageio

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/tsvds.git
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Download the YOLOv3 weights file from [this Google Drive link](https://drive.google.com/file/d/115SO4hr8LFtB316YtZd0Xm4YXVCk4nnB/view?usp=sharing) and place it in the project root directory.

### Usage

1. Run the main application:
   ```
   python Project-GUI.py
   ```

2. Use the GUI to open a video file and define the region of interest for violation detection.

3. The system will process the video and display results in real-time, saving violation detections to the specified output folder.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgements

- [OpenCV](https://opencv.org/)
- [TensorFlow](https://www.tensorflow.org/)
- [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
- [Tkinter](https://docs.python.org/3/library/tkinter.html)

---

<p align="center">Made with ❤️ by a group of friends from VIT Bhopal</p>
