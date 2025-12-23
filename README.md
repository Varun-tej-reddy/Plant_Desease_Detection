# Plant_Desease_Detection
MobileVit is a plant disease detection app designed for farmers. It uses image processing and machine learning to scan uploaded plant leaf images, predict plant diseases, and display the disease name for early crop protection.
Here is a clean, professional README.md section that clearly explains how you did the project, based exactly on your points.
You can copy–paste this directly into your GitHub README.

-> Project Implementation Overview

This project focuses on building a plant disease detection mobile application designed for farmers, with special attention to edge-device deployment and real-world usability.

Technology Stack
	•	Frontend & App Development: Flutter
	•	Backend & Database: MySQL
	•	AI Models: MobileViT and Efficient model

Model Selection & Design Approach

To ensure the application works efficiently on mobile and edge devices, careful model selection was done.

• Traditional ViT Limitation

The traditional Vision Transformer (ViT) model, although highly accurate, is computationally heavy and contains a large number of parameters. Due to this, it is not suitable for deployment on edge devices such as mobile phones used by farmers in field conditions.

• MobileViT Model

To overcome these limitations, MobileViT was used.
MobileViT is a hybrid deep learning model that combines:
	•	Convolutional Neural Networks (CNN) for local feature extraction
	•	Vision Transformers (ViT) for capturing global contextual information

This hybrid approach significantly reduces the number of parameters while maintaining high accuracy, making it suitable for mobile and edge-device deployment.

• Efficient Model Integration

An Efficient model is used alongside MobileViT to further improve performance and efficiency.
This model helps in:
	•	Reducing computational overhead
	•	Improving inference speed
	•	Enhancing the overall efficiency of the MobileViT model

🌾 Real-World Usage

The application is built using Flutter, allowing universal OS deployment across Android and iOS devices. Farmers can easily carry mobile devices to fields, capture or upload plant images, and get disease predictions in real time.

This approach ensures low latency, portability, and practical usability in real agricultural environments.
