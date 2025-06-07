# Chest X-Ray Image Classification 🩻
## Deep Learning-Based Comparative Analysis of CNN Architectures

This project replicates and compares various deep learning models for classifying chest X-ray images into **COVID-19**, **Pneumonia**, and **Normal** classes. It serves both as an academic study and a practical demonstration of medical imaging analysis using CNN-based architectures.

📓 **[Interactive Notebook](./notebook/Chest_XRay_Classification.ipynb)**  
📦 **[Installation Requirements](./requirements.txt)**

---

## 📊 Project Summary

### ✅ Models Implemented
- Custom CNNs (2 architectures)
- VGG16, VGG19 (from scratch and pretrained)
- Xception (with transfer learning)
- ResNet50 (ImageNet pretrained)
- Hybrid VGG19 + CNN model

### 🧠 Techniques Used
- **Preprocessing**: Normalization, CLAHE, Noise Filtering
- **Augmentation**: Rotation, Flip, Zoom
- **Transfer Learning**
- **Evaluation**: Accuracy, F1-Score, Confusion Matrix

### 📁 Dataset Details
- Source: [Mendeley Data](https://data.mendeley.com/)
- Classes: `COVID-19`, `Pneumonia`, `Normal`
- Total Images: 5,228
- Image Size: Resized to 256×256
- Split: 80% Train / 20% Test (+ 20% Validation from Train)

---

## 🧪 Results Snapshot

| Model         | Test Accuracy | F1-Score |
|---------------|---------------|----------|
| VGG19         | 97%           | 0.97     |
| VGG + CNN     | 97%           | 0.97     |
| CNN Model 1   | 95%           | 0.95     |
| CNN Model 2   | 94.5%         | 0.95     |
| ResNet50      | 87.5%         | 0.88     |
| Xception      | 35%           | 0.35     |

> Note: Xception underperformed likely due to overfitting or domain mismatch.

---

## 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/chest-xray-classification.git
cd chest-xray-classification
