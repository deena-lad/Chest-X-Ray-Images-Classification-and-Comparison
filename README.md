# Chest X-Ray Image Classification: Comparative Deep Learning Study

This project replicates and compares state-of-the-art deep learning techniques for classifying chest X-ray images into three categories: **COVID-19**, **Pneumonia**, and **Normal**. The study implements models such as **CNN**, **VGG16**, **VGG19**, **ResNet50**, **Xception**, and a **Hybrid VGG19+CNN**.

📄 **[View Full Report (PDF)](Seminar_Report.pdf)**

## 🧠 Techniques Used
- Convolutional Neural Networks (Custom)
- Pretrained Architectures: VGG16, VGG19, ResNet50, Xception
- Transfer Learning
- Data Augmentation
- Preprocessing: CLAHE, Normalization, Noise Reduction

## 🧪 Dataset
- Source: Mendeley Data
- Classes: COVID-19, Normal, Pneumonia
- Total: ~5200 images
- All resized to 256×256 and split into 80:20 train:test

## 📊 Results
- Best Models: VGG19, Hybrid VGG19+CNN
- Metrics: Accuracy, F1-Score, Training/Validation Loss

| Model         | Test Accuracy | F1-Score |
|---------------|---------------|----------|
| VGG19         | 97%           | 0.97     |
| VGG + CNN     | 97%           | 0.97     |
| CNN Model 1   | 95%           | 0.95     |
| ResNet50      | 87.5%         | 0.88     |

## 📁 Structure
- `/models`: Source code for each model
- `/results`: Visualizations of training progress and performance
- `/notebook`: Jupyter notebook summary
- `Report.pdf`: Full academic report

## 🚀 How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Run the model scripts or open the notebook
