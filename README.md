# Realtime-object-detection

This project demonstrates a real-time object detection application for Android, utilizing TensorFlow Lite for mobile machine learning inference. It captures live video from the device's camera, processes each frame, and identifies objects in real-time.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Features
- Real-time object detection using the device's camera.
- Uses TensorFlow Lite for efficient on-device ML model inference.
- Displays bounding boxes and labels around detected objects.

## Requirements
- Android Studio Arctic Fox (2020.3.1) or higher.
- Android device running Android 8.0 (API level 24) or higher.
- TensorFlow Lite compatible device.

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Milind-Ranjan/Realtime-object-detection.git
   cd Realtime-object-detection
   ```
2. **Open in Android Studio:**
	-	Open Android Studio and select “Open an Existing Project.”
	-	Navigate to the cloned repository and open the Realtime-object-detection project.
3.	**Sync Project with Gradle Files:**
	-	Once the project opens, sync it with Gradle to download necessary dependencies.
4.	**Run the App:**
	-	Connect an Android device (with Developer Mode enabled).
	-	Click “Run” in Android Studio, and select the connected device.
## Usage
- Once the app is launched, it will request permission to access the device’s camera.
- The camera will start, and objects will be detected in real-time.
-	Detected objects will appear with labels and bounding boxes.
