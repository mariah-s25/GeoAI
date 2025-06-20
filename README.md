# ResNet-Based U1652 Geo-Localization (Simplified MBEG)

This repository contains a training pipeline for cross-view geo-localization on the U1652 dataset, using a Dual-ResNet-based model.

It is adapted from the original [MBEG (Multi-Branch Embedding Guidance)](https://github.com/Reza-Zhu/ACMMM23-Solution-MBEG) solution presented at **ACM MM 2023**, but removes Local Perception Network (LPN) and uses a Dual-ResNet model for training and evaluation.

---

## 🔍 Original Source & Attribution

This project is based on the official MBEG solution available here:

> 🔗 https://github.com/Reza-Zhu/ACMMM23-Solution-MBEG

We specifically adapted components from:
- `settings.yaml`
- `Preprocessing.py` into `Modified_Preprocessing.py`
- `model_.py` into `dualresnet.py`
- `train.py`
- `U1652_test_and_evaluate.py`

---
  
The notebook [`ResNet_U1652.ipynb`](./ResNet_U1652.ipynb) contains the code implementation and can be used to run the training and testing.
