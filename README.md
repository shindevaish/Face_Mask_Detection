# Face_Mask_Detection
Using CNN and Transfer Learning

A deep learning-based model that detects whether a person is wearing a face mask or not using image classification techniques.

---

## Project Overview

This project uses a pre-trained deep learning model to classify images into:
- With Mask  
- Without Mask  

The model is trained using transfer learning (InceptionV3) and achieves high accuracy.

---

## Dataset

The dataset used in this project is sourced from Kaggle:

🔗 [Face Mask Detection Dataset](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)

### Details:
- Two classes:
  - With Mask
  - Without Mask
- Contains labeled images for supervised learning
- Suitable for image classification tasks

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **InceptionV3 (Transfer Learning)**
- **FastAPI (Backend)**
- **HTML, CSS (Frontend)**

---
## Model Details

- Base Model: **InceptionV3**
- Approach:
  - Transfer Learning (Feature Extraction)
- Final Training Results:
  - Accuracy: **99.27%**
 
> Model evaluated on training dataset after final epoch.

## Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/face-mask-detection.git
cd face-mask-detection
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```