# Threads of Evidence: Fabric Type Classification

**San José State University**  
**Authors:** Japji Batra, Bushra Naveed

---

## Overview
*Threads of Evidence* is an end-to-end machine learning and computer vision pipeline designed to classify textile fabric types from high-resolution images[cite: 1, 3]. Using the **iBUG Fabrics Dataset** (captured under four distinct illumination conditions using a photometric stereo sensor)[cite: 1, 3], the project extracts 2,048-dimensional visual feature representations via a pre-trained **ResNet50** neural architecture. 

We benchmark and evaluate several shallow and deep learning models to accurately classify fabric types across seven target categories: **Cotton, Polyester, Denim, Wool, Nylon, Silk, and Fleece**.

<img width="1592" height="1110" alt="image" src="https://github.com/user-attachments/assets/7b72233f-c6f7-41cc-b5a0-5dc477a8e291" />

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
```

<img width="1389" height="590" alt="image" src="https://github.com/user-attachments/assets/620f786d-689b-4049-88d1-6009f5d5c053" />

<img width="1189" height="671" alt="image" src="https://github.com/user-attachments/assets/02c4c9f5-0ec8-4d1f-85f8-f85c76310ba0" />

<img width="889" height="490" alt="image" src="https://github.com/user-attachments/assets/af89fa6a-b821-4aa9-9ea4-0369af6d074a" />

<img width="536" height="470" alt="image" src="https://github.com/user-attachments/assets/1e801387-8370-44ed-9492-0fc5d6a1b4b7" />

<img width="790" height="590" alt="image" src="https://github.com/user-attachments/assets/4ebafa12-767f-4be3-8f84-7280fb50cd0a" />

<img width="464" height="162" alt="image" src="https://github.com/user-attachments/assets/2fcf5b76-0bbe-4ade-983e-91f7cbe20505" />







