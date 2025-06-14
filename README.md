# ivf-embryo-classification-dl

# Deep Learning for Embryo Classification in IVF 🧬🤖

This project was developed for the **World Championship 2023 - Embryo Classification Challenge** on Kaggle as part of the EEE406 - Fundamentals of Biomedical Signal Processing course.

## 🧠 Objective
To automate the assessment of embryo viability using deep learning techniques, minimizing subjectivity and improving efficiency in IVF procedures.

## 🗂️ Dataset
- ~1,000 high-resolution Day 3 & Day 5 embryo images
- Binary labels: `Good` vs `Not Good`
- 80/20 stratified train-validation split
- Public test set for Kaggle leaderboard scoring

## 🛠️ Models Used (Transfer Learning)
- ✅ MobileNetV3Large
- ✅ EfficientNetB0
- ✅ DenseNet121 (🏆 Best model with 81% val. accuracy and 0.73333 public score)

## 📊 Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion matrix analysis
- Ablation studies (augmentation, fine-tuning, regularization)

## 📁 File Structure
