# Global and Local Kernels Recommender Systems Project

This repository contains the full reproducibility and contribution code for the project based on the paper **"Global and Local Kernels for Recommender Systems"**. The project focuses on using deep learning methodologies to perform matrix completion in recommender systems. The code is divided into two distinct folders:

- **Original Glocal_K**: Contains the original implementation using the MovieLens 100K dataset.
- **Contribution code**: Contains the extended code that applies the approach to the MovieLens 1M dataset along with additional contributions.

---

##  Repository Structure

├── Original Glocal_K/ 
  │ ├── data/ 
    │ │ └── movielens_100k/ 
      │ │ ├── movielens_100k_u1.base 
      │ │ └── movielens_100k_u1.test 
  │ └── Glocal_K.ipynb 
├── Contribution code/ 
  │ ├── MovieLens_1M/ 
    │ │ └── data/ 
      │ │ ├── train_dataset.dat 
      │ │ └── test_dataset.dat 
  │ └── contribution_code.ipynb 
├── README.md 
└── environment.yml
