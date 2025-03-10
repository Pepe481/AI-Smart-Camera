Smart Camera with Object Detection and Dynamic Tracking
This project is a smart camera system designed to detect and track objects using computer vision and embedded systems. It uses:

Raspberry Pi 3B+ for object detection, video processing, and remote control.
ESP32 for camera control, motor movement, and real-time communication.
The camera is mounted on a pan-tilt platform controlled by two servo motors, allowing it to follow detected objects automatically. The goal of this project is to demonstrate proficiency in embedded systems, computer vision, RTOS, and device communication.

Features
✅ Object Detection using OpenCV on the Raspberry Pi.
✅ Pan/Tilt Control via servo motors managed by the ESP32.
✅ Real-Time Communication between Raspberry Pi and ESP32 using UART.
✅ Video Streaming over the local network using Flask/WebRTC.
✅ Embedded Systems Design with FreeRTOS on the ESP32.

Hardware Components
Raspberry Pi 3B+ (video processing, AI, web streaming).
ESP32 (camera control, motor control, communication).
2 Servo Motors (pan/tilt camera control).
Camera Module (attached to the pan-tilt platform).
