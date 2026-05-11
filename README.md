# Detection of Mandibular Condylar Degeneration Using CNN

## Overview
This project focuses on the automated detection of mandibular condylar degeneration from panoramic dental X-ray images using Convolutional Neural Networks (CNN). The system aims to assist in early diagnosis through deep learning-based medical image analysis and explainable AI techniques.

---

## Features
- Automated condyle degeneration detection
- Deep learning-based image classification
- Explainable AI visualization using Grad-CAM
- Medical image preprocessing and augmentation
- Performance evaluation using accuracy and confusion matrix

---

## Dataset Samples

### Normal vs Degenerated Condyles

| Normal | Degenerated |

---

## Annotation / ROI Detection

<img width="591" height="292" alt="roi" src="https://github.com/user-attachments/assets/f75e7dc5-5a9e-4f9f-b828-05d477af0810" />

---

### Pipeline
```text
Panoramic X-ray
       ↓
Image Preprocessing
       ↓
Condyle Region Extraction
       ↓
CNN Feature Extraction
       ↓
Classification
       ↓
Prediction Output
```

---

## Model Architecture

<img width="700" height="407" alt="archit_resnet18" src="https://github.com/user-attachments/assets/5bd22f64-836c-47b8-800a-84f901b02322" />

---

## Training Performance

### Accuracy Graph
<img width="875" height="615" alt="epoch" src="https://github.com/user-attachments/assets/d878dfeb-4b50-465e-b263-72f40fa6e9a5" />

---

## Evaluation Metrics

### Confusion Matrix
<img width="1145" height="912" alt="confu_test" src="https://github.com/user-attachments/assets/47ceb830-7a48-4816-96a0-487af7945eca" />

---

## Explainability using Grad-CAM

<img width="1087" height="642" alt="grad (1)" src="https://github.com/user-attachments/assets/3f1e5ada-7064-4343-9389-aede19b013d5" />


The Grad-CAM visualization highlights the regions influencing the CNN prediction, improving interpretability and trust in medical diagnosis.

---

## Prediction Results

<img width="2793" height="1316" alt="P0007_R_D_L_D-dicom-00001" src="https://github.com/user-attachments/assets/580c0a47-ae99-40c3-9ea7-7cf5732cf517" />

---

## Technologies Used
- Python
- TensorFlow / PyTorch
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
  
---

## Future Improvements
- Multi-class degeneration classification
- Real-time clinical integration
- Improved explainability techniques
- Larger dataset training

---

## Author
Devika S
