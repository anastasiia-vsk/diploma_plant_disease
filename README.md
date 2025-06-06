# 🌿 Plant Disease Detection using Computer Vision

**Final Qualification Project:** *Automation of Plant Disease Detection Using Computer Vision Technology in Precision Agriculture*

## 🎯 Project Goal
The goal of this project is to develop a computer vision model for the automatic detection and classification of plant diseases using images from the [PlantVillage dataset](https://github.com/spMohanty/PlantVillage-Dataset).  
The model focuses on identifying visual symptoms on plant leaves across multiple crops such as tomatoes, corn, potatoes, etc.

This project aims to improve agricultural productivity by:
- enabling early detection of diseases before they become widespread,
- reducing crop losses and minimizing the overuse of chemical treatments,
- providing a foundation for integration into drone-based monitoring or mobile diagnostic tools in the context of precision farming.

Solving the task of visual classification of plant diseases showcases the potential of computer vision technologies for automating agricultural workflows and accelerating innovation in the agri-tech sector.


## 🧠 Technologies Used
- **Python 3** – core programming language
- **PyTorch + Torchvision** – for CNN model development and pretrained ResNet18
- **NumPy, Matplotlib, Seaborn** – for data manipulation and result visualization
- **scikit-learn** – for metrics like accuracy and confusion matrix
- **tqdm** – for training progress monitoring


## 📊 Results
- Achieved **~95% validation accuracy** using a fine-tuned ResNet18 CNN
- Supports classification of **38 plant disease categories** (healthy and infected)
- Model trained on **~54,000 images**, with 80/20 train-validation split
- Includes **confusion matrix**, misclassified examples, and **class-wise metrics**
- Training time with GPU (Colab): ~7 minutes per epoch
- Model generalizes well, can be adapted for field or drone-captured imagery


## 📚 References
- [PlantVillage Dataset on GitHub](https://github.com/spMohanty/PlantVillage-Dataset)
- [Deep Residual Learning (ResNet)](https://arxiv.org/abs/1512.03385)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)

---
👩‍🎓 *Anastasiia, 2025 – State University of Trade and Economics (DTEU)*

