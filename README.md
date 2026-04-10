# Smart Grid Fault Diagnosis System

## Overview
This project presents a data-driven approach to fault diagnosis in smart grid systems using phasor measurement unit (PMU) data. The focus is on developing reliable models that can detect faults under dynamic and noisy real-world conditions.

Reliable fault detection is critical for preventing power outages, reducing economic loss, and maintaining grid stability in modern energy systems.

---

## Problem
Modern power grids rely on accurate and timely fault detection to ensure stability and prevent cascading failures.

However, real-world challenges include:
- Noisy sensor measurements  
- Dynamic system behavior  
- Variability in operating conditions  

Traditional models often struggle to generalize across these conditions.

---

## Dataset
- PMU-based fault data represented as structured signals/images  
- Multi-class classification of fault types  

Phasor Measurement Units (PMUs) provide time-synchronized measurements of voltage and current across the grid, enabling precise monitoring of system behavior.

Due to size considerations, a curated dataset (~300MB) is included for experimentation.

---

## Fault Types
- Line-to-ground faults  
- Line-to-line faults  
- Three-phase faults  
- Voltage disturbances  

---

## System Approach

### Models
- Deep learning models for fault classification  
- Feature extraction from PMU data  

### Pipeline
- Data preprocessing and normalization  
- Model training and validation  
- Performance evaluation using classification metrics  
- Visualization of results (confusion matrix, predictions)

---

## Challenges
- Noise and variability in sensor data  
- Class imbalance in fault scenarios  
- Generalization across different grid conditions  

---

## Results & Observations
- Deep learning models can effectively detect fault patterns in structured data  
- Performance varies significantly under changing conditions  

> Most errors observed were not due to model limitations, but due to variability in real-world sensor data and changing grid conditions.

This highlights that fault diagnosis is not purely a modeling problem, but a system-level challenge involving data quality, variability, and robustness.

This suggests that improving performance requires better integration of sensing, preprocessing, and modeling rather than focusing solely on model architecture.

---

## Visual Results

### Confusion Matrix
![Confusion Matrix](results/confusion_matrix.png)

### Fault Prediction Examples
![Predictions](results/sample_output.png)

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  

---
