# Lightweight Energy-Efficient Diagnostic Framework

## The full code will be updated after the Paper gets published

## 🔬 Overview

This research project presents a lightweight, energy-efficient diagnostic framework for medical imaging using teacher-student knowledge distillation. The framework achieves significant model compression while maintaining high diagnostic accuracy and providing clinical-grade explainability.

**⚠️ Note: The full implementation code will be updated after the research paper review is completed.**

## 🎯 Key Achievements

- **Model Efficiency**: 30% model size reduction with minimal accuracy loss
- **High Performance**: 97.12% accuracy on CT scan classification
- **Environmental Impact**: 70% lower carbon footprint compared to baseline models
- **Scalability**: Comprehensive comparison across 25,000 augmented CT scan images
- **Explainability**: Clinical-grade interpretability with pixel-level attention maps

## 🏗️ Framework Architecture

The framework utilizes teacher-student knowledge distillation to create a lightweight diagnostic model:

- **Teacher Model**: EfficientNetB0 (provides knowledge transfer)
- **Student Model**: DSNet (lightweight, energy-efficient)
- **Knowledge Distillation**: Traditional and multi-teacher approaches compared
- **Dataset**: 25,000 CT scan augmented images

## 🔍 Explainability Features

- **Grad-CAM**: Gradient-based class activation mapping
- **LIME**: Local Interpretable Model-agnostic Explanations
- **Clinical-grade transparency**: Pixel-level attention maps for decision-making

## 🛠️ Technologies Used

- **TensorFlow 2.8**: Primary deep learning framework
- **Keras**: High-level neural network API
- **PyTorch**: Additional deep learning support
- **Vision Transformers**: Advanced architecture components
- **LIME**: Model interpretability
- **Grad-CAM**: Visual explanations

## 📊 Performance Metrics

| Metric | Result |
|--------|--------|
| Accuracy | 97.12% |
| Model Size Reduction | 30% |
| Carbon Footprint Reduction | 70% |
| Dataset Size | 25,000 CT scans |

## 🌱 Environmental Impact

This research emphasizes sustainable AI development by significantly reducing the environmental footprint of diagnostic models while maintaining clinical-grade performance.

## 📝 Status

This repository is currently under review. Full code implementation will be available following the completion of the research paper review process.

## 🤝 Contributing

Contributions will be welcome once the full code is released. Please check back after the review process is complete.

## 📄 License

This project will be licensed under the MIT License - see the LICENSE file for details.

---

*Research conducted with focus on sustainable AI and clinical explainability in medical imaging.*
