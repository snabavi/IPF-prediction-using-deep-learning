# IPF-prediction-using-deep-learning
### 📄 Related Paper: [![arXiv](https://img.shields.io/badge/arXiv-YourPaperID-red)](https://arxiv.org/abs/YourPaperID)
### 👋 Introduction

Welcome to the IPF Prediction Using Deep Learning project! Idiopathic pulmonary fibrosis (IPF) is a progressive disease that irreversibly transforms lung tissue into rigid fibrotic structures, leading to debilitating symptoms such as shortness of breath and chronic fatigue. The heterogeneity and complexity of this disease, particularly regarding its severity and progression rate, have made predicting its future course a complex and challenging task. Besides, traditional diagnostic methods based on clinical evaluations and imaging have limitations in capturing the disease’s complexity.

This repository presents a deep learning approach to predict the progression of IPF using the Kaggle Pulmonary Fibrosis Progression dataset, which includes computed tomography images and clinical information. By leveraging a proposed context-aware sequential-parallel hybrid transformer model and enriching predictions with clinical information, the method achieved a Laplace Log-Likelihood score of −6.508, outperforming previous techniques. This work highlights the potential of advanced deep learning models in providing accurate predictions, aiding in the diagnosis and management of IPF. The overview of the proposed method is shown in figure below:
![Alt Text](images/overview.png)
### 📂 Repository Structure
IPF-prediction-using-deep-learning/
│── RegionGrowing/          # MATLAB scripts for data preprocessing and modeling
│── model/          # Python scripts for deep learning model training and evaluation
│── dataset/              # Sample dataset or links to dataset sources
│── results/              # Results and performance metrics
│── images/             # PNG diagrams illustrating the workflow
│── README.md             # Project description and setup guide
│── .gitignore            # Git ignore file



## Citation

If you find our code or paper useful, please cite as:

```bibtex
@article{dolatabadi2025prognostic,
  title={Prognostic Model for Idiopathic Pulmonary Fibrosis Using Context-Aware Sequential-Parallel Hybrid Transformer and Enriched Clinical Information},
  author={Dolatabadi, Mahdie and Nabavi, Shahabedin and Moghaddam, Mohsen Ebrahimi},
  journal={arXiv preprint arXiv:2503.00386},
  year={2025}
}
