Real-Time Object Detection System using YOLO
Project Overview
This project is a Real-Time Object Detection System developed using the YOLO (You Only Look Once) deep learning model. The system is capable of detecting multiple objects simultaneously from live video streams or video files with high speed and accuracy. It is implemented in Python with a focus on efficient frame processing and optimized inference, making it suitable for real-world applications.

Key Features
Real-time object detection using YOLO
Supports live webcam and video input
Fast and accurate detection of multiple object classes
Optimized frame handling for smooth performance
Clean and modular Python implementation

Technologies Used
Python
YOLO (You Only Look Once)
OpenCV
NumPy
PyTorch / Ultralytics YOLO

Project Structure
Real-Time-Object-Detection/
│
├── Real-time Object Detection.ipynb
├── README.md
├── requirements.txt
└── sample_outputs/

Installation
Clone the repository:

git clone https://github.com/your-username/real-time-object-detection.git
cd real-time-object-detection

Install dependencies:
pip install -r requirements.txt  (Make sure Python 3.8 or above is installed.)

How to Run
Open the Jupyter Notebook:
jupyter notebook "Real-time Object Detection.ipynb"
Run all cells sequentially.
Allow camera access when prompted.
Detected objects will be displayed in real time with bounding boxes and labels.

Working Principle
Capture frames from webcam or video source
Preprocess frames for YOLO input
Perform object detection using the trained YOLO model
Draw bounding boxes, class labels, and confidence scores
Display results in real time

Applications
Real-time surveillance systems
Traffic monitoring and vehicle detection
Crowd analysis
Smart city applications
Autonomous and embedded vision systems
Future Enhancements
Object tracking using SORT / DeepSORT
ANPR detection with vehicle counting
Deployment using Flask or FastAPI
Model optimization using ONNX or TensorRT

Author
Aishwarya BarabdeinkedIn: https://www.linkedin.com/in/aishwarya-barabde-b7a65222b

GitHub: https://github.com/AishwaryaBarabde
