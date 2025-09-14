# Hyperspectral Image Classification using Neural Networks

## 📌 Project Overview  
This project implements a **Multi-Layer Perceptron (MLP) neural network** for **multi-class classification of hyperspectral images**.  
We experiment with three benchmark datasets:  
- **Indian Pines**  
- **Samson**  
- **Jasper Ridge**  

## ⚙️ Implementation  
- Framework: **scikit-learn (`MLPClassifier`)**  
- Activation: **ReLU**  
- Optimizer: **Adam**  
- Hidden Layers: Tuned 
- Evaluation Metrics: **Accuracy**, **Cohen’s Kappa**  
- Visualization: **Confusion Matrix** (via matplotlib)

---

## 📊 Results  
- **Indian Pines:** Accuracy = **69.61%**, Kappa ≈ **0.67**  
- **Jasper Ridge:** Accuracy = **98.70%**, Kappa = **0.9815**  
- **Samson:** Accuracy = **99.39%**, Kappa = **0.9907**  
