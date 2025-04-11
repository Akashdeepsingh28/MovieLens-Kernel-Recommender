# MovieLens Recommender System with Global & Local Kernels

This project reproduces the deep learning architecture proposed in the paper **"Global and Local Kernels for Recommender Systems"** using the MovieLens 1M dataset.

##  Project Structure
- `src/`: Contains all core Python scripts.
- `data/`: Folder to place `train_dataset.dat` and `test_dataset.dat`.
- `results/`: Stores final metrics and logs.
- `notebook/`: Demo collab notebook.

##  Model Overview
A deep autoencoder is enhanced with:
- **Global Kernel**: Holistic pattern extraction
- **Local Kernel**: Personalized similarity structure

##  Requirements
```bash
pip install -r requirements.txt
