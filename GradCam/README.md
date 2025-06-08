# Grad-CAM: Visual Explanation for CNNs on Caltech-256

This project demonstrates the training of a 5-block VGG-style Convolutional Neural Network (CNN) on the Caltech-256 dataset and uses Gradient-weighted Class Activation Mapping (Grad-CAM) to visualize model interpretability.

## Folder Structure
- `codes_model/`
  - `gradcam_0.png` to `gradcam_4.png`: Sample Grad-CAM visualizations.
  - `myvgg_model.pth`: Trained VGG-style model.
  - `Task01.ipynb`: CNN training notebook.
  - `Task02.ipynb`: Grad-CAM visualization notebook.
- `report/`
  - `report.pdf`: Full report detailing methodology, architecture, results, and Grad-CAM.

## Highlights
- CNN trained from scratch on 257 classes with significant class imbalance.
- Grad-CAM used to interpret which parts of images influence predictions.
- Report includes architecture, training curves, backpropagation math, and Grad-CAM principles.

## Usage
1. Run `Task01.ipynb` to train the model (or use provided `myvgg_model.pth`).
2. Run `Task02.ipynb` to generate Grad-CAM visualizations.

---

**Note:** Large files (csv, GloVe, model weights) are gitignored.  
`myvgg_model.pth` is gitignored
