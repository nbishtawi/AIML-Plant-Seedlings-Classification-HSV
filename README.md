# Plant Seedlings Classification (HSV)

This project focuses on classifying different species of plant seedlings using image data and handcrafted features extracted from the HSV (Hue, Saturation, Value) color space. The project was developed as part of an AIML course to explore classical computer vision pipelines in contrast to deep learning methods.

---

## Goals
- Build a machine learning pipeline to classify plant seedlings into species.  
- Extract robust features from raw image data using the HSV color space.  
- Compare classification accuracy across different algorithms (e.g., Random Forest, SVM, Logistic Regression).  

---

## Methodology
1. **Data Preprocessing**
   - Raw images converted into HSV color space.  
   - Features extracted (color histograms, statistical moments, etc.).  
   - Images stored in `images.npy` for efficient loading.  

2. **Feature Engineering**
   - Focus on handcrafted HSV-based features rather than end-to-end CNNs.  
   - Emphasis on interpretability of color-based cues in plant identification.  

3. **Model Training**
   - Multiple ML algorithms applied (Random Forest, SVM, Logistic Regression).  
   - Performance compared across daily, weekly, and aggregate classification tasks.  

---

## Results
- Models achieved **strong classification accuracy** using only handcrafted HSV features.  
- Random Forest consistently outperformed baseline classifiers.  
- Demonstrated that classical feature engineering can still be effective in image classification.  

---

## Notes
- Dataset provided in processed form (`images.npy`, `Labels.csv`) for reproducibility.  
- Original raw image dataset was not included due to storage limitations.  
