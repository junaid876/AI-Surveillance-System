# AI-Powered Surveillance System for Abnormal Activity Detection

> **Real-time intelligent surveillance using deep learning to detect abnormal human behavior.**

This project detects abnormal human activities in surveillance video streams using deep learning. 
It uses a **Spatial-Temporal AutoEncoder (STAE)** trained on normal behavior and flags anomalies 
in real-time using **Euclidean distance thresholds**.

---

# Technologies Used

- Python 3.x
- OpenCV
- Keras (CNN, ConvLSTM, Conv3DTranspose)
- Tkinter (for GUI)
- NumPy
- imutils
- PIL (for image handling)

---

## Features

- Upload and preprocess surveillance frame datasets
- Normalize frames and feed into STAE model
- Train model using Conv3D and ConvLSTM layers
- Detect abnormal activity in video using prediction loss
- GUI-based interface for all operations
- Real-time alert on abnormal events (e.g., violence, running)

---
