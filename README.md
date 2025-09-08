# 🧠 Deep Learning for Brain Tumor Detection

This repository contains the implementation and comparative analysis of three deep learning models—YOLOv8n, a custom CNN, and ResNet18—for detecting brain tumors from MRI images.

## 📌 Overview

- **Dataset**: MRI images from Kaggle, containing 4 classes: Glioma, Meningioma, No Tumor, Pituitary.
- **Total Samples**: 7023 images (5712 train, 1311 test)
- **Models Compared**:
  - YOLOv8n (Object Detection)
  - Custom CNN (Classification)
  - ResNet18 (Transfer Learning)

## 🚀 Results

| Model       | Overall Accuracy | Best Class Accuracy | Weakness |
|-------------|------------------|---------------------|----------|
| YOLOv8n     | Low (Glioma <20%)| Meningioma: 94%     | Poor on Glioma |
| Custom CNN  | 72.83%           | -                   | Underfitting |
| ResNet18    | **98.67%**       | Pituitary: 99.51%   | -        |

## 🛠️ Technologies Used

- Python
- PyTorch
- OpenCV
- Ultralytics (YOLOv8)
- TensorBoard
- Gradio (for UI)
- Google Colab

## 📊 Key Metrics

- mAP50, mAP50-95 (for YOLO)
- Accuracy, Loss (for CNN and ResNet18)
- Confusion Matrix
- Class-wise Precision/Recall

## 🧪 How to Run

1. Clone the repo:
```bash
git clone https://github.com/HadieSadeghi4/brain-tumor-detection-dl.git
cd brain-tumor-detection-dl


## 📈 Conclusion
ResNet18 outperformed both YOLOv8n and the custom CNN model, making it a reliable choice for medical imaging applications requiring high accuracy.

## 📜 License
This project is for academic purposes. Please cite the original dataset and authors if used.

## 👩‍💻 Author
**Hadie Sadeghi**  
Technical and Vocational University, Iran  
**Supervisor:** Mehdi Davaran

## 📚 References
- [Kaggle Dataset](https://www.kaggle.com/)  
- [Ultralytics YOLO](https://ultralytics.com/)  
- [PyTorch ResNet](https://pytorch.org/vision/stable/models.html#resnet)

## 🏷 Keywords
Brain Tumor Detection, Deep Learning, YOLOv8, CNN, ResNet18, MRI, Medical Imaging, Python, PyTorch

