# Suspicious Movement Detection in Super Mart using YOLOV11 X-Pose Model

## Overview
This project implements a **YOLOV11 X-Pose Model** to detect suspicious movements of individuals inside a supermarket. The goal is to enhance security by identifying unusual or potentially dangerous behaviors using advanced pose estimation and real-time object detection techniques.

## Features
- **Real-time detection** of human movements inside a supermarket.
- **Pose estimation** for detecting suspicious behaviors.
- Integration of **YOLOV11** for precise object detection.
- **Optimized for speed and accuracy** using deep learning frameworks.
  
## Dataset
The dataset used for training consists of CCTV footage from a supermarket. It contains labeled data with human poses and annotations for suspicious and non-suspicious behaviors.

## Model
- **YOLOV11 X-Pose**: A powerful model combining YOLO’s object detection with human pose estimation, allowing for accurate movement tracking and analysis.
  
## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/supermart-suspicious-movement-detection.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the detection script:
   ```bash
   python main.py --source <your-video-source>
   ```

## Usage
- The model can be applied to live video streams from CCTV cameras.
- For pre-recorded footage, replace `<your-video-source>` with the file path.
  
## Results
- The model achieves an accuracy of **72%** in detecting suspicious movements.
- Pose estimation allows for tracking keypoints to identify specific behaviors, enhancing the overall detection capability.

## Folder Structure
```
├── dataset_path/                # Dataset folder with video files
├── Python file                  # Python files for multiple operations
```

## Future Work
- **Multi-person tracking**: Implementing multi-person tracking for crowded environments.
- **Behavior classification**: Extending the model to classify behaviors like loitering, theft, etc.
- **Edge computing**: Optimizing the model for real-time deployment on edge devices.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
