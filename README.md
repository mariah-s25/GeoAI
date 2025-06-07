# ResNet-Based U1652 Geo-Localization (Simplified MBEG)

This repository contains a simplified training pipeline for cross-view geo-localization on the U1652 dataset, using a Dual-ResNet-based model.

It is adapted from the original [MBEG (Multi-Branch Embedding Guidance)](https://github.com/Reza-Zhu/ACMMM23-Solution-MBEG) solution presented at **ACM MM 2023**, but removes Local Perception Network (LPN) and uses a simpler Dual-ResNet model for training and evaluation.

---

## 🔍 Original Source & Attribution

This project is based on the official MBEG solution available here:

> 🔗 https://github.com/Reza-Zhu/ACMMM23-Solution-MBEG

We specifically adapted components from:
- `U1652_test_and_evaluate.py`
- `train.py`
- Model and dataloader utilities

We thank the authors for their open-source contribution.

---

## 📁 Contents

- `train.py`: ResNet training script using satellite and drone view data from U1652.
- `light_model.py`: Simple ResNet-based architecture.
- `subset_dataloader.py`: Loads a subset of U1652 for faster training.
- `utils.py`: Utility functions (e.g., seed setup, config parsing, model saving).
- `config.yaml`: Training hyperparameters.
