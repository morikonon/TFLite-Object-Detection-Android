# Object Detection with TensorFlow Lite

A lightweight Android application that demonstrates real-time object detection using the **TFLite Task Library**. This project uses a pre-trained **SSD MobileNet V1** model to identify objects within images and visualize them with bounding boxes.

## Features
* **Real-time Detection:** Identifies objects from images.
* **ML Integration:** Powered by `tensorflow-lite-task-vision`.
* **Visual Feedback:** Draws bounding boxes and confidence scores.

## Tech Stack
* **Language:** Kotlin
* **ML Engine:** TensorFlow Lite
* **Build System:** Gradle (Target SDK 33)

## Quick Start
1. **Clone the repo:**
   ```bash
   git clone https://github.com/morikonon/TFLite-Object-Detection-Android.git
2. **Setup Model:** Ensure mobilenetv1.tflite is located in app/src/main/assets/.
3. **Build & Run:** Open in Android Studio and run on an emulator or physical device.

## Configuration Details
The project is configured with jvmTarget = "1.8" and includes necessary Material Components and Kotlin dependencies for compatibility with modern Android Studio environments.
