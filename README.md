# Facial Emotion Recognition Using Transfer Learning

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/downloads/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://tensorflow.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)](CONTRIBUTING.md)

A deep learning project that implements facial emotion recognition using transfer learning with MobileNet architecture. The model can classify human emotions from facial expressions into four categories: Happy, Angry, Fear, and Neutral.

## 🎯 Project Overview

This project leverages the power of transfer learning to build an efficient emotion recognition system. By using a pre-trained MobileNet model as the backbone, we achieve good performance while maintaining computational efficiency suitable for real-time applications.

### Key Features

- ✅ **Transfer Learning**: Utilizes pre-trained MobileNet for efficient feature extraction
- ✅ **Real-time Classification**: Lightweight model suitable for mobile and edge deployment
- ✅ **Data Augmentation**: Comprehensive augmentation strategy to improve generalization
- ✅ **Model Persistence**: Save and load trained models for deployment
- ✅ **Visualization**: Training history and confusion matrix analysis
- ✅ **Robust Training**: Early stopping and learning rate scheduling

## 🚀 Quick Start

### Prerequisites

```bash
Python 3.7+
pip or conda package manager
```

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/facial-emotion-recognition.git
cd facial-emotion-recognition
```

2. **Install dependencies**
```bash
pip install -r requirements.txt
```

3. **Download the dataset**
   - Download the FER13 cleaned dataset
   - Extract to `../input/fer13-cleaned-dataset/` directory
   - Ensure the folder structure matches the expected format

4. **Run the training script**
```bash
python facial_emotion_recognition_using_transfer_learning.py
```

## 📁 Project Structure

```
facial-emotion-recognition/
│
├── facial_recognition.pptx                          # Presentation
├── README.md                                        # Project documentation
└── emotion_recognition_analysis.ipynb               # Jupyter notebook version
```

## 🎭 Supported Emotions

The model classifies facial expressions into four primary emotions:

| Emotion | Description |
|---------|-------------|
| **Happy** | Joyful, smiling expressions |
| **Angry** | Frustrated, angry expressions |
| **Fear** | Scared, worried expressions |
| **Neutral** | Calm, expressionless faces |


## 📋 Requirements

```txt
tensorflow>=2.8.0
keras>=2.8.0
opencv-python>=4.5.0
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.5.0
seaborn>=0.11.0
scikit-learn>=1.0.0
scikit-plot>=0.3.7
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/improvement`)
3. **Commit your changes** (`git commit -am 'Add new feature'`)
4. **Push to branch** (`git push origin feature/improvement`)
5. **Create Pull Request**

### Areas for Contribution
- Data preprocessing improvements
- Model architecture enhancements
- Real-time inference optimization
- Mobile deployment scripts
- Additional emotion categories
- Performance benchmarking

---

⭐ **Star this repository if you find it helpful!**

💡 **Found an issue or have a suggestion? Open an issue!**
