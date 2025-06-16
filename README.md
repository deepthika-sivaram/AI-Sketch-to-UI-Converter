# AI-Sketch-to-UI-Converter

This project converts hand-drawn UI sketches into functional HTML code using deep learning. It integrates a custom YOLOv8-based detector with a CNN + Attention + Transformer + GRU pipeline to reconstruct user interfaces from visual input.

## 📁 Files and Structure

- `notebooks/`: Jupyter notebooks containing training, evaluation, and pipeline integration.
- `requirements.txt`: Python dependencies.

## 📊 Highlights

- Object detection using **YOLOv8s**
- Custom **CNN** feature extractor
- **Self-Attention** and **Transformer** for UI layout modeling
- **GRU**-based HTML generation
- **OCR** integration for realistic text capture
- Supports multiple HTML **themes** (warm, dark, minimal, etc.)

## 🗃 Dataset

- **Sketch2Code Dataset**: [Kaggle](https://www.kaggle.com/datasets/vshantam/sketch2code)

## 📄 License

This project is for academic and research purposes only.
