
# Vehicle Detection on Indian Roads Using Drone View 

## Introduction
This project focuses on detecting vehicles on Indian roads in drone view.The solution leverages Nvidia's Jetson Nano with DeepStream and a custom-trained YOLOv5 model. 
This system intends to develop a model for drones recognising the vehicles on Indian roads aiding for autonomous navigation and class count for traffic density
- **Real-time Detections:** Utilizes Nvidia Jetson Nano for edge enabling faster predictions and lower latency.
- **Real-time Counting:** It uses YOLOV5 for counting the vehicle classes seperately.
- **Custom Training:** YOLOv5 model trained on a custom dataset annotated using Roboflow.

## Prerequisites

### Jetpack Installation
1. **Install Jetpack 4.6.1**:
   Follow the instructions provided in the [Nvidia official documentation]([https://developer.nvidia.com/embedded/jetpack](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)).

### Increase Swap Size
Increase the swap size on your Jetson Nano to ensure smooth operation. You can follow this [guide]([https://www.youtube.com/watch?v=7n9RgLE6uqU](https://www.forecr.io/blogs/programming/how-to-increase-swap-space-on-jetson-modules)) for instructions.

### Clone Repository
Clone this repository and navigate to the project directory:
```bash
git clone https://github.com/yourusername/vehicle-detection-drone.git
cd vehicle-detection-drone
