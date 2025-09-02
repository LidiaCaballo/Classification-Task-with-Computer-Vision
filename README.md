> **Disclaimer:** This project was developed as part of a **University of Liverpool** assignment.  
> It is for **educational purposes only** and **must not be copied, reused, or distributed** without permission, in accordance with the University's academic integrity policies.
>
> > **Disclaimer:**  
> This project was developed as part of a **University of Liverpool** assignment.  
> It is for **educational purposes only** and must not be copied, reused, or distributed without permission, in accordance with the University's academic integrity policies.

# Image Classification (PyTorch Pipeline)

A Jupyter Notebook project implementing a **deep-learning pipeline** to classify images into multiple categories using **PyTorch**.  
It includes **dataset preparation**, **train/validation/test splits**, **Custom CNN and ResNet-18 models**, **cross-validation**, **hyperparameter tuning**, and **performance evaluation** with clear visualisations.

---

## What it does
- **Data preparation**
  - Loads images from a structured folder (`Images/class_name/image.jpg`)
  - Generates **train/val/test splits** with reproducible random seeds
  - Applies augmentations and normalisation
- **Model training**
  - **Custom CNN** with configurable layers, dropout, and batch normalisation
  - **ResNet-18**:
    - Fine-tuning all layers
    - Feature-extraction mode with frozen backbone
- **Cross-validation**
  - Supports **5-fold cross-validation** for more reliable performance metrics
- **Hyperparameter tuning**
  - Lightweight **Hyperband-style search** on CNN parameters
- **Evaluation**
  - Accuracy and loss tracking per epoch
  - Confusion matrix and per-class precision/recall/F1 scores
  - Final comparison of models (CNN vs ResNet modes)

---

## Files
- `COMP534_assignment2.ipynb` — main notebook for data setup, training, evaluation, and visualisations  
- `Images/` — dataset folder organised in subfolders by class label

---

## How to Run
1. **Clone or download the project**
   ```bash
   git clone https://github.com/your-username/image-classification.git
   cd image-classification

