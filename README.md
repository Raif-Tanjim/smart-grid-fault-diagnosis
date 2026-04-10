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
<img width="792" height="708" alt="image" src="https://github.com/user-attachments/assets/b10d748e-d303-4468-9c97-60a2491f71ad" />

### Fault Prediction Examples
<img width="1584" height="1583" alt="image" src="https://github.com/user-attachments/assets/364e23bd-7dee-4f36-bbc0-29624f486cb9" />

---

## Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy, Pandas  
- Matplotlib  

---

## Note
Model weights and intermediate files are not included to keep the repository lightweight and focused on implementation.

---

## Research Context
This work aligns with research in data-driven fault diagnosis and predictive maintenance in smart grid systems, where robustness under real-world conditions is a key challenge.

---

## Future Work
- Improve robustness under varying grid conditions  
- Integrate real-time monitoring systems  
- Explore multi-modal sensing approaches  

---

