# EnginECG

This project demonstrates the development of an AI-based Engine Optimizer and Predictive Fault Diagnosis System using signal processing and machine learning techniques. The system analyzes engine vibration and acoustic signals to detect early-stage faults and performance issues.

## 🚀 Overview

An AI-driven approach to **engine fault diagnosis using sound signals**.  
By analyzing acoustic patterns produced by engine components, the system classifies **normal vs faulty conditions** without requiring physical inspection or intrusive sensors.

The complete pipeline is implemented and tested in **Google Colab**, showcasing how raw engine audio can be transformed into actionable machine intelligence.

---

## System Functionality

Engine vibration and sound signals are captured using sensors.

The system processes signals using:

FFT (Fast Fourier Transform)
Order Analysis
Spectrogram Analysis
Envelope Analysis
Extracted features are analyzed using AI models to:
Detect anomalies
Classify possible faults
Provide optimization insights

## 🏗️ Key Features

- Multi-class engine condition recognition  
- Robust audio preprocessing and normalization  
- Extraction of meaningful spectral and temporal features  
- Balanced and controlled train/test data split  
- Waveform visualization for signal-level inspection  
- Modular pipeline suitable for future expansion  

---

## 🧩 Engine Conditions Covered

### ✅ Healthy States
- Timing Chain  
- Piston Spark  
- Head Engine  
- Exhaust  

### ❌ Faulty States
- Faulty Timing Chain  
- Faulty Piston Spark  
- Faulty Head Engine  
- Faulty Exhaust  

Each condition is treated as a distinct acoustic identity.

---

## 🔄 Workflow Overview
Sensor layer 
↓
Signal Conditioning Circuit
↓
ADC
↓
Embedded Processing Unit
↓
Signal Processing
↓
AI Engine(feature extraction, anomaly detection , fault classification)
↓
Output Interface(Display)


The workflow is modular and easily adaptable to new models, datasets, or deployment targets.

---

## 📊 Dataset Strategy

- Controlled number of samples per class  
- Equal representation in training and testing  
- Transparent file-level inspection  
- Strict class-wise separation  

This ensures fair evaluation and reproducibility of results .

---

## 🛠️ Tech Stack

- Python  
- Librosa  
- NumPy  
- Pandas  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib
- Matlab 

---

## 🔮 Future Scope

- Real-time inference using edge devices (ESP32, microcontrollers)
- CNN-based learning on spectrograms
- Cloud API for live engine diagnostics
- Web or mobile dashboard for visualization
- Industrial-scale predictive maintenance systems

---

## 🎯 Applications

- Predictive Maintenance  
- Automotive Diagnostics  
- Smart Manufacturing  
- Research & Academic Projects  
- Hackathons and Innovation Challenges  

---

## 👨‍💻 Author

**Durva K and Aditya D**  
Artificial Intelligence & Data Science  
signal processing and electronics system

> “your bikes talks we help you listen.”
