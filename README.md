# Autonomous Vehicle Prototype: Real-Time Perception & Navigation

An AI-driven robotics project developed to demonstrate autonomous navigation, obstacle avoidance, and real-time object detection using edge computing.

## 🚀 System Architecture
This project integrates high-performance hardware with optimized computer vision pipelines to achieve low-latency decision-making in dynamic environments.

### 🛠️ Hardware Stack
* **Compute:** NVIDIA Jetson TX2 (Pascal Architecture)
* **Vision:** Intel RealSense Depth Camera (D400 Series)
* **Chassis:** Custom robotic platform with high-torque DC motors
* **Communication:** V2V (Vehicle-to-Vehicle) enabled modules

### 💻 Software Stack
* **Language:** Python, C++
* **AI/CV Frameworks:** OpenCV, TensorFlow, TensorRT
* **Algorithms:** YOLOv5 (Detection), A* / Dijkstra (Pathfinding), Sensor Fusion

## 🌟 Key Features
* **Real-Time Object Detection:** Utilizes a custom-trained detection model optimized for the Jetson TX2.
* **Latency Optimization:** Leveraged **NVIDIA TensorRT** to accelerate inference, reducing perception lag by **40%**.
* **Depth-Sensing & Mapping:** Integrated Intel RealSense to generate 3D point clouds for precise spatial awareness and obstacle distancing.
* **Dynamic Path Planning:** Implemented sensor fusion (LiDAR/Vision) to enable smooth lane-following and emergency braking.

## 📊 Performance Metrics
| Feature | Optimization | Result |
| :--- | :--- | :--- |
| Inference Speed | TensorRT FP16 | ~30 FPS |
| Detection Accuracy | YOLOv5 Training | 92% mAP |
| Reaction Time | Optimized Pipeline | < 50ms |

## 📁 Project Structure
* `/src`: Core logic for navigation and detection.
* `/models`: Pre-trained and optimized engine files.
* `/scripts`: Deployment and calibration scripts for the RealSense camera.
* `/docs`: Technical specifications and thesis research.


## 📜 Research Context
This project served as the basis for my Undergraduate Thesis: **"Research on the application of AI and Machine Learning algorithms to design a working prototype of an autonomous vehicle."**

---
Developed by [Aayush Nepal](https://github.com/Aayushnepal09)
