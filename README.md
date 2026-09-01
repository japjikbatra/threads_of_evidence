# Threads of Evidence: Fabric Type Classification

**CS 171 Term Project**  
**San José State University**  
**Authors:** Japji Batra, Bushra Naveed

---

## Overview
*Threads of Evidence* is an end-to-end machine learning and computer vision pipeline designed to classify textile fabric types from high-resolution images[cite: 1, 3]. Using the **iBUG Fabrics Dataset** (captured under four distinct illumination conditions using a photometric stereo sensor)[cite: 1, 3], the project extracts 2,048-dimensional visual feature representations via a pre-trained **ResNet50** neural architecture. 

We benchmark and evaluate several shallow and deep learning models to accurately classify fabric types across seven target categories: **Cotton, Polyester, Denim, Wool, Nylon, Silk, and Fleece**.

---

## Requirements & Dependencies

The project is implemented in Python (v3.10+) utilizing PyTorch, Scikit-Learn, and Torchvision. 

### Core Dependencies
```text
torch>=2.0.0
torchvision>=0.15.0
scikit-learn>=1.2.0
pandas>=1.5.0
numpy>=1.23.0
matplotlib>=3.6.0
Pillow>=9.0.0
kagglehub>=0.2.0

<img width="1592" height="1110" alt="image" src="https://github.com/user-attachments/assets/7b72233f-c6f7-41cc-b5a0-5dc477a8e291" />


