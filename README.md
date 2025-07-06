# 🔐 In Touch with Security: The Rise of Fingerprint Biometrics

An intelligent fingerprint identification system using **Gabor filters** and **Convolutional Neural Networks (CNNs)**. Developed as part of a B.Tech Minor Project in CSE (AI & ML) at BVRIT.

## 🚀 Features

- ✅ Fingerprint image preprocessing using morphological operations
- ✅ Feature extraction using Gabor Filters and CNN
- ✅ Feature fusion + PCA for dimensionality reduction
- ✅ Classifies fingerprints into: Arch, Tented Arch, Left Loop, Right Loop, Whorl
- ✅ Achieved **98.77% accuracy**

## 🧠 Techniques Used

- Convolutional Neural Network (CNN)
- Gabor Filters
- PCA (Principal Component Analysis)
- Evaluation metrics: Accuracy, Precision, Recall, F1-score

## 📂 Dataset Used

- FVC2000
- FVC2002
- FVC2004

## 📊 Results

| Classifier | Accuracy |
|------------|----------|
| CNN        | 98.77%   |
| SVM        | 97.86%   |
| Random Forest | 95.47% |

## 🖼 Sample Outputs

*(Add some plots or fingerprint images here if available)*

## ⚙️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook fingerprint_identification.ipynb
