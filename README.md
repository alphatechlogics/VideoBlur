# 🎥 YOLOv8 Video Blur

> A simple yet effective solution to blur selected objects (like faces, people, etc.) in a video using **YOLOv8**. This approach harnesses the power of Ultralytics' latest YOLOv8 object detection models for **faster** and **more accurate** detections, resulting in a highly efficient anonymization or privacy-preserving workflow.

## 🚀 Features

- **Fast Object Detection**: Leverages YOLOv8 for quick and reliable detection on video frames.
- **Configurable Blur Targets**: Specify which classes (e.g., persons, cars, faces) to blur.
- **Easy to Integrate**: Simple function calls to process each frame or entire videos.
- **High Accuracy**: YOLOv8’s improved architecture ensures better precision and recall.

## 🛠 Requirements

- **Python** 3.10+
- **OpenCV** (for video I/O and image manipulation)
- **Ultralytics** (`yolov8` or `ultralytics` Python package)
- **NumPy**
- Any other standard libraries mentioned in your code

### Installation

1. **Create and activate a virtual environment** (recommended):

   ```bash
   python -m venv env
   source env/bin/activate  # On Linux/Mac
   # or
   env\Scripts\activate  # On Windows
   ```

2. **Install dependencies:**

```bash
pip install ultralytics opencv-python numpy
```

Note: If you plan to run in a notebook environment (like Google Colab), just install them in your notebook.
