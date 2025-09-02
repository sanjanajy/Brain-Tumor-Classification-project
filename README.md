# Brain Tumor Classification using VGG16 & Grad-CAM 🧠

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/username/Brain-Tumor-Classification/blob/main/notebook/Project_colab_BTC.ipynb)

## 📌 Project Overview
This project classifies **MRI brain scans** into **four categories**:
- No Tumor
- Meningioma Tumor
- Pituitary Tumor
- Glioma Tumor  

It leverages **VGG16 (Transfer Learning)** for classification and **Grad-CAM** for explainability, providing visual heatmaps to highlight tumor regions.  

In addition, an **interactive dashboard (built in Colab)** was developed to:
- Enter patient details (Name, Age, Gender, Patient ID)
- Upload MRI image
- View classification results with accuracy & confidence chart
- Assess tumor **danger level**
- Download a **detailed report** (PDF) with patient details & prediction results

---

## 🚀 Features
- 🔍 **Multi-class classification** (4 tumor categories)  
- 📊 **Accuracy & confidence charts**  
- 🖼️ **Grad-CAM heatmap visualization** for interpretability  
- 📑 **Report generation** (downloadable PDF with patient details & results)  
- 🎛️ **Interactive dashboard in Google Colab** for a smooth user experience  

---

## 🛠️ Tech Stack
- **Python**
- **TensorFlow / Keras** (VGG16 Transfer Learning)
- **OpenCV** (image processing)
- **Matplotlib, Seaborn** (visualizations)
- **Pandas** (data handling)
- **ReportLab** (PDF report generation)

---

## 📊 Results
### Training Performance
![Accuracy Curve](outputs/accuracy_chart.jpg)

### Grad-CAM Visualization Example
![Grad-CAM Example](outputs/gradcam_visualization.jpg)

---

## ▶️ How to Use
1. Clone this repo:
   ```bash
   git clone https://github.com/username/Brain-Tumor-Classification.git
   cd Brain-Tumor-Classification

