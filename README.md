# Pothole-detection
 
 This project makes use of Tensorflow's Object Detection API to detect and count the number of potholes in an image. 

### Built With

* [Tensorflow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)

## Getting Started

### Prerequisites

* Clone the git repository to your local machine.

  ```sh
  git clone https://github.com/aryamansharma01/Pothole-detection.git
  ```

### API Installation

1. Run the following code
   ```sh
   sudo apt install -y protobuf-compiler
   cd models/research
   protoc object_detection/protos/*.proto --python_out=.
   cp object_detection/packages/tf2/setup.py .
   python -m pip install .
   ```
3. Install OpenCV module
   ```sh
   pip install opencv-python-headless==4.1.2.30
   ```
