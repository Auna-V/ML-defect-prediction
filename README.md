Software Defect Prediction using Supervised Machine Learning

This project applies supervised machine learning (Random Forest Classifier) to predict software defects using labeled software metrics data.

---

Project Structure

- `data/`: Contains `Train_data.csv` (with defects) and `Test_data.csv` (unlabeled).
- `notebook/`: Jupyter/Colab notebook for model training and prediction.
- `results/`: Final predictions with defect labels.
- `requirements.txt`: Libraries needed to run this project.

---
Features Used

Typical software code metrics like:
- LOC (Lines of Code)
- Cyclomatic Complexity
- Inheritance Depth
- Coupling, etc.

---

 ML Workflow

1. Data Preprocessing
2. Model Training (Random Forest)
3. Prediction on unseen data
4. Feature Importance Analysis
5. Export predictions to CSV

---

 ML Algorithm

- **Random Forest Classifier**  
  Chosen for its performance and interpretability.

---

 Sample Output

| Module | Predicted_Defect |
|--------|------------------|
| A      | 1                |
| B      | 0                |

---

 Result

- Achieved XX% accuracy on internal validation (if test labels available)
- `test_with_predictions.csv` is ready for defect inspection

---

## 🚀 Run it Yourself

```bash
pip install -r requirements.txt

