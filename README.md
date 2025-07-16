# Breast Cancer Classification Analysis

## 📌 Introduction
Breast cancer remains one of the most prevalent and life-threatening diseases, affecting 1 in 8 women in the United States. Early and accurate detection is crucial to improve treatment outcomes and reduce mortality rates. This project applies several machine learning classification models to predict whether a breast tumor is **benign** or **malignant** based on data from fine needle aspirate (FNA) biopsies.

We utilized:
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- **Logistic Regression**
- **Decision Trees**
- **Random Forest**
- **Neural Networks**

The goal is to build models that minimize false negatives, where a malignant tumor is misclassified as benign, potentially leading to dangerous treatment delays.

---

## 🚀 Project Impact
- **Medical Decision Support:** Assists healthcare providers in diagnosing breast cancer more accurately and cost-effectively.
- **Cost-Benefit Optimization:** We integrated a **cost-benefit matrix** to reflect real-world medical costs associated with false positives and false negatives.
- **Feature Insights:** Identified critical features such as **symmetry, compactness, concave points, and area_worst** as the most predictive indicators of malignancy.
- **Model Performance:** Achieved **up to 98.23% accuracy** with the pruned Decision Tree model, with significant potential savings and improved diagnostic reliability.

---

## 📊 Model Summary
| Model               | Accuracy | Net Benefit |
|---------------------|----------|-------------|
| K-Nearest Neighbors | 96.5%     | $3.37M      |
| Naive Bayes         | 92.5%     | $3.24M      |
| Logistic Regression | 93.9%     | $3.37M      |
| Decision Tree       | **98.23%**| **~$3.4M**  |
| Random Forest       | 93.86%    | $3.19M      |
| Neural Networks     | ~96%      | $2.96M      |

---

## 🧩 Conclusion
The **pruned Decision Tree model** emerged as the most effective, achieving the highest accuracy with minimal false predictions. This suggests that machine learning can significantly aid in the early detection of breast cancer, potentially reducing unnecessary treatments and healthcare costs.

Future enhancements could include:
- Incorporating more diverse biopsy datasets.
- Expanding the analysis with more advanced deep learning models.
- Real-world testing in clinical environments for validation.
