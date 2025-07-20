NeuroPark: AI-based 3D Vehicle Detection & Smart Parking System 🚗🧠
This repository contains the final version of the NeuroPark 3D vehicle detection project. Developed in collaboration with Neurosoft, it transforms 2D traffic camera images into accurate and interpretable 3D vehicle scenes for applications such as traffic monitoring, smart parking, and urban mobility analytics.

✨ Project Highlights
Real-time object detection and depth estimation from single RGB images.

3D bounding box generation and point cloud visualization.

Accurate spatial alignment and world coordinate transformation.

Validated with LiDAR-based measurements.

🔧 Technologies Used
Object Detection: YOLOv8 (Ultralytics)

Depth Estimation: MiDaS (Monocular Depth Estimation)

Point Cloud & Visualization: Open3D

Image Processing & Lane Detection: OpenCV

Mathematical Operations: NumPy, PyTorch, SciPy (SVD & PCA)

Visualization & Plotting: Matplotlib

🚩 Scene Processing Pipeline
Object Detection: Vehicles detected using YOLOv8 (cars, trucks, buses, motorcycles).

Depth Estimation: Depth map generated using MiDaS.

Point Cloud Generation: RGB images combined with depth to create 3D colored point clouds.

Bounding Box Construction: Oriented bounding boxes calculated using PCA and validated against LiDAR measurements.

Coordinate Transformation: Boxes and clouds aligned to world coordinates using extrinsic matrices.

📈 Performance
Average processing time: ~5-6 seconds per high-res image.

Approx. FPS: 0.15–0.20 FPS (ideal for batch analysis or near-real-time scenarios).

✅ Use Cases
Intelligent Traffic Monitoring

Smart Parking Systems

Urban Mobility Analytics

Autonomous Driving Research

📌 Project Team
Caner Olcay

Batın Topbaşoğlu

Myra Shah

🤝 Acknowledgments
Special thanks to supervisors Cezary Dołęga and Paweł Mrówka from Neurosoft for their valuable guidance and support.

