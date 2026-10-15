# TinyML Animal Detection

A lightweight deep learning model for animal classification (Cat vs Dog), optimized for edge and resource-constrained devices.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1c0Fjhid_rE6nUMdQyKXPYgrvR3uFico3?usp=sharing)

**Live Notebook:** [Open in Google Colab](https://colab.research.google.com/drive/1c0Fjhid_rE6nUMdQyKXPYgrvR3uFico3?usp=sharing)

## Results
- Validation Accuracy: **92.88%**
- TFLite Model Size: **635.4 KB**
- Architecture: MobileNetV2 (alpha=0.35) + small classifier head
- Framework: TensorFlow / Keras + TensorFlow Lite

## Features
- Fully runnable on Google Colab
- Automatic dataset download (no manual data needed)
- Model quantization for TinyML deployment
- Clear evaluation with confusion matrix and classification report

## How to Run
1. Click the **Open in Colab** badge above (or use the link)
2. Enable GPU runtime (Runtime → Change runtime type → T4 GPU)
3. Run all cells in order

## Files
- `TinyML_Animal_Detection.ipynb` – Full training & conversion pipeline
- `animal_detection_tiny.tflite` – Quantized model ready for edge devices

## Author
Maryam Fagbo  
Computer Science student | Edge AI & Efficient Deep Learning
