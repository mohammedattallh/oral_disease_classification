# 🦷 Oral Disease Classification  

## 📌 Project Overview  

This project implements a **deep learning-based system** for classifying oral diseases using **Convolutional Neural Networks (CNNs)**.  
It leverages a **fine-tuned EfficientNet-B4** model trained on a curated dataset of oral disease images to detect the following conditions:

- Calculus  
- Caries  
- Gingivitis  
- Mouth Ulcer  
- Oral Cancer  
- Oral Lichen Planus  
- Tooth Discoloration  
- Hypodontia  

### 🧠 System Components  
- **Training Pipeline:** Data preparation, augmentation, model training, and evaluation.  
- **Deployment:** A user-friendly web interface built with **Gradio** for uploading images, viewing predictions, visualizing **Grad-CAM** results, and receiving **evidence-based recommendations**.

The model achieves **high accuracy** in multi-class classification and employs **Grad-CAM** for explainability — highlighting regions of interest in the input images to enhance trust and interpretability.


---

## 🚀 Features

- **🧩 Multi-Class Classification:** Supports **8 oral disease classes** for comprehensive diagnosis.  
- **🧠 Data Augmentation:** Utilizes **Albumentations** for robust and diverse training samples.  
- **🏗️ Model Architecture:** Custom **EfficientNet-B4** with dropout and batch normalization for improved generalization.  
- **🔥 Explainability:** Generates **Grad-CAM heatmaps** to visualize model focus areas and enhance interpretability.  
- **💬 Recommendations:** Provides **evidence-based medical advice** tailored to predicted diseases and confidence levels.  
- **🖼️ Gradio Interface:** Interactive demo for image uploads, displaying **top-2 predictions**, **Grad-CAM heatmaps**, and detailed recommendations.  
- **📊 Evaluation Metrics:** Includes **accuracy**, **classification report**, and **confusion matrix** for model assessment.

---

## 🧠 Tech Stack
| Category | Tools / Libraries |
|-----------|-------------------|
| Deep Learning | PyTorch, timm |
| Augmentation | Albumentations |
| Evaluation | Scikit-learn, Seaborn, Matplotlib |
| Interface | Gradio |
| Visualization | pytorch-grad-cam |

---
### 🔸 Web App Interface  
![App Preview](https://github.com/mohammedattallh/oral_disease_classification/blob/main/result1.png)

---

### 💡 Recommendations  

This section provides insights and potential improvements for future work and research.  

![App Preview](https://github.com/mohammedattallh/oral_disease_classification/blob/main/result2.png)
