# 🏠 Building Damage Detector

Computer vision model that classifies building images as **damaged** or **undamaged**.

## 📌 Problem
Manual inspection of building damage is slow and expensive.
This project explores using deep learning to automate damage detection.

## 🧠 Model
- Architecture: ResNet18 (pretrained on ImageNet)
- Framework: PyTorch
- Transfer learning with fine-tuning

## 📊 Dataset
- Small curated dataset of damaged & undamaged buildings
- Images organized using ImageFolder structure

## 📈 Results
- Accuracy: ~95% on validation data
- High recall on damaged buildings

## 🛠️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook
