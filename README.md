Plant Pathology Classification 🍎🌿
A PyTorch-based deep learning model for detecting apple leaf diseases (healthy, multiple_diseases, rust, scab) using SE-ResNeXt50. Includes data augmentation, class balancing, and submission-ready prediction pipelines.

PyTorch
License: MIT
Kaggle Dataset

Key Features:
✅ Pretrained SE-ResNeXt50 with custom head
✅ Stratified train-val split & class weighting
✅ Comprehensive metrics (F1, Precision, Recall)
✅ Test-time inference pipeline
✅ Achieves 97.5% validation accuracy

Quick Start:

bash
Copy
git clone https://github.com/SaKinLord/plant-pathology.git  
pip install -r requirements.txt  
python train.py  
Dataset:
Official competition dataset:
https://www.kaggle.com/competitions/plant-pathology-2020-fgvc7/data
