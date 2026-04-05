# Crystal Property Prediction using CNNs

This project explores the use of Convolutional Neural Networks (CNNs) for predicting properties of crystalline materials using 2D representations of unit cells combined with tabular features.

## 📌 Objectives
- Predict material properties (energy, bandgap, cohesion)
- Compare CNN, tabular and hybrid models
- Evaluate impact of dataset size and image resolution
- Analyze embedding of crystal symmetry

## 🧠 Models
- CNN (image-based)
- MLP (tabular)
- Hybrid CNN + Tabular
- Hybrid + Symmetry Embedding

## 📊 Results
- Strong dependency on dataset size
- Limited impact of image resolution
- Hybrid models outperform single-input models
- Symmetry embedding showed minimal impact

## 📁 Dataset
Based on Materials Project (MPtrj dataset).  
Only final relaxed structures were used.
https://next-gen.materialsproject.org/contribs/projects/MPtrj_2022_9
## ⚙️ Installation

```bash
pip install -r requirements.txt
