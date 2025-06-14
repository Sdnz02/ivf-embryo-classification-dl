# ivf-embryo-classification-dl

# Deep Learning for Embryo Classification in IVF

This project was developed for the **World Championship 2023 - Embryo Classification Challenge** on Kaggle as part of the EEE406 - Fundamentals of Biomedical Signal Processing course.

## Objective
To automate the assessment of embryo viability using deep learning techniques, minimizing subjectivity and improving efficiency in IVF procedures.

## 🗂Dataset
- ~1,000 high-resolution Day 3 & Day 5 embryo images
- Binary labels: `Good` vs `Not Good`
- 80/20 stratified train-validation split
- Public test set for Kaggle leaderboard scoring

##  Models Used (Transfer Learning)
- MobileNetV3Large
- EfficientNetB0
- DenseNet121 (🏆 Best model with 81% val. accuracy and 0.73333 public score)

## Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion matrix analysis
- Ablation studies (augmentation, fine-tuning, regularization)

## File Structure
├── Baseline_for_Embryo_Classification_Last.ipynb # Full training and evaluation pipeline

├── Report_Deep Learning for Embryo Classification in IVF.pdf # Full methodology and results

├── EEE406-Slide_Suat-Abdulkadir-Berkay.pptx # Presentation slides

├── Submission & Leaderboard Clarification.pdf # Late submission explanation to Kaggle

└── README.md


## 🏅 Kaggle Competition Result
- Public score: **0.73333**
- Estimated rank: **15th globally**
- Note: Due to late submission, team `"kadirdaglar"` did not appear on the official leaderboard, but result was valid and acknowledged in academic context.

## 📌 Team Members
- Suat Deniz – 2006102002  
- Abdulkadir Dağlar – 2006102033  
- Berkay Caplık – 2206102900  

## 🔮 Future Work
- Grad-CAM visualizations for clinical interpretability
- Larger dataset collection
- Multi-class classification aligned with clinical grading
- Ensemble model for performance boost

## 📄 License
This project is intended **solely for academic demonstration purposes** as part of EEE406 coursework. Redistribution, modification, or commercial use of the code is **not permitted** without explicit permission from the authors.

Please note: The dataset used in this project belongs to the [Kaggle World Championship 2023 Embryo Classification](https://www.kaggle.com/competitions/world-championship-2023-embryo-classification) and is subject to their terms of use.


