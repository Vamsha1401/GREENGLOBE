# Green Globe: A Futuristic Internet of Things Device for Greenhouse Monitoring

## Overview

**Green Globe** is an advanced IoT-based system designed to revolutionize greenhouse monitoring and management. By leveraging cutting-edge technologies, including Arduino microcontrollers, real-time data analysis, machine learning algorithms, and cloud-based services, Green Globe enables automated, efficient, and intelligent greenhouse operations. The system monitors environmental conditions, captures and analyzes images of plants, predicts potential issues, and provides actionable insights to optimize plant health and yield.

## Table of Contents

- [Project Features](#project-features)
- [System Architecture](#system-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Results](#results)


## Project Features

- **Environmental Monitoring**: Continuously monitors temperature, humidity, and other environmental factors critical to plant growth.
- **Real-Time Data Analysis**: Utilizes machine learning algorithms to analyze data in real-time and predict potential issues.
- **Image Processing**: Captures and processes images of plants to assess their health, detect diseases, and provide timely interventions.
- **Cloud Integration**: Stores data and images securely on Firebase Cloud, allowing for real-time access and analysis.
- **Automated Control**: Supports automated decision-making and control mechanisms to maintain optimal greenhouse conditions.
- **User-Friendly Interface**: Includes a web-based dashboard for easy monitoring, data visualization, and system control.

## System Architecture

The Green Globe system is built upon a robust architecture that integrates hardware components, such as Arduino microcontrollers and sensors, with advanced software modules for data processing, analysis, and control.

1. **Arduino Microcontroller**: Acts as the central processing unit for sensor data collection and initial data processing.
2. **Sensors**: Collects environmental data, including temperature, humidity, light intensity, and soil moisture.
3. **Camera Module**: Captures images of plants for health assessment and disease detection.
4. **Machine Learning Algorithms**: Analyzes sensor data and images to predict issues and suggest remedies.
5. **Firebase Cloud**: Stores data and images, providing real-time access and scalability.
6. **User Interface**: A web-based dashboard for monitoring and controlling the greenhouse environment.

## Installation

### Prerequisites

- Arduino IDE installed on your computer.
- Python 3.x with the required libraries (`NumPy`, `Pandas`, `OpenCV`, `TensorFlow` or `PyTorch`, `Firebase Admin SDK`).
- A Firebase project with Realtime Database and Storage configured.
- A compatible Arduino board (e.g., Arduino Uno, Mega).

### Step-by-Step Guide

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/yourusername/Green-Globe.git
   cd Green-Globe
   ```
2. **Set Up Arduino IDE:**
- Open the Arduino IDE.
- Load the .ino file from the arduino/ directory.
- Connect your Arduino board and upload the sketch.
3. **Install Python Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Configure Firebase:**
- Set up Firebase configuration in firebase_config.json.
- Ensure that the Firebase Admin SDK is properly initialized in the Python script.
5. **Run the Python Scripts:**
   ```sh
   python main.py
   ```

## Usage

- Deploy the Arduino system in your greenhouse.
- Monitor real-time data via the web dashboard.
- Analyze environmental data and plant health through the integrated machine learning models.
- Receive alerts and recommendations for maintaining optimal conditions and addressing potential plant health issues.

## Hardware Requirements

- Arduino Board (e.g., Arduino Uno, Mega)
- DHT11 Temperature and Humidity Sensor
- ESP32 Camera Module
- Soil Moisture Sensor
- Light Intensity Sensor
- Internet Connectivity (Wi-Fi Module)
- Power Supply

## Software Requirements

- Arduino IDE
- Python 3.x
- Firebase Admin SDK
- Required Python libraries (NumPy, Pandas, OpenCV, TensorFlow/PyTorch)


## Results


![image](https://github.com/user-attachments/assets/46058035-17b6-40a4-b5c3-317762cd7440)

**User interface for controlling the Robot**


  
![image](https://github.com/user-attachments/assets/045f262f-9c13-44ee-aa0d-d6cc072bd5b8)

**Green Globe Collecting Data in Green House**

  
![image](https://github.com/user-attachments/assets/fda99b99-fa6d-473d-82e3-46fe1c30350e)

**Data Recorded**

  
![image](https://github.com/user-attachments/assets/e8e6ee67-6208-4a63-bde4-06575a2ec888)

**Visualisation of Data Recorded**

  
![image](https://github.com/user-attachments/assets/58f83a71-6d27-4954-ac5e-c1ac127854bb)

**Analysis Obtained from the Captured Image**

  
![image](https://github.com/user-attachments/assets/2e5f9dd8-38ab-426d-a409-e6e96e9f02bb)

**SMS Notification Directly to Users Mobile**

