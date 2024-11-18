# VisionStream AI  
_Real-Time People Detection and Analytics Using AI-Powered Video Streams_

**Description**:  
VisionStream AI is an advanced real-time video analytics system designed to simulate live camera feeds for people detection and counting using cutting-edge AI technologies. Built on NVIDIA DeepStream and Triton Inference Server, it processes multiple video streams with high efficiency, performing object detection and tracking in real-time. The system integrates a FastAPI backend for managing data pipelines and storing results in a SQL database via SQLAlchemy. It also features a dynamic dashboard for visualizing real-time detection data, enabling powerful insights and analytics at a glance.

This project demonstrates how modern AI and video processing frameworks can be combined to build scalable, high-performance solutions for real-world applications such as crowd monitoring, safety systems, and more.

## **Project Scope and Requirements**
**1. Core Functionalities:**
+ Simulated video stream that mimics a live camera feed.
+ Real-time person detection using a pre-trained model (e.g., YOLO).
+ Real-time data persistence in a database.
+ A FastAPI backend to handle inference requests and WebSocket updates.
+ Frontend dashboard to display people count in real-time.

**2. Key Technologies:**
+ DeepStream for video processing and object detection.
+ Triton Inference Server to manage inference models.
+ FastAPI for backend API services and WebSocket updates.
+ SQLAlchemy to interact with a SQLite database.
+ React for a simple frontend dashboard.

**3. Expected Outputs:**
+ Real-time counting of people detected in a video stream.
+ Ability to visualize this count on a frontend in real-time.

