# BCI Competition IV-2a Baselines

This repo provides baseline implementation for the BCI Competition IV Dataset 2a using multi-band Riemannian geometry features.

## ✅ Method: FB-TS + Alignment + SVC
- Feature: Filter Bank Covariances + Block Diagonal + Tangent Space
- Optional Alignment: ProcrustesAlignment from `pyriemann`
- Classifier: SVM (RBF kernel)

## 📊 Results

| Method                | 10-Fold Accuracy | LOSO Accuracy |
|----------------------|------------------|---------------|
| FB-TS (+Alignment)   | 61.73 ± 3.54 %   | 31.44 ± 3.53 % |

## 📂 Structure

