# titanic_Survival.py
# 🚢 Titanic Survival Prediction
This project demonstrates a basic logistic regression model to predict the survival of passengers on the Titanic. It uses a small manually defined dataset consisting of passenger IDs and binary survival outcomes.
## 📘 Overview
- **Goal**: Predict whether a passenger survived (`1`) or not (`0`) based on their ID (as a proxy feature).
- **Model Used**: Logistic Regression
- **Libraries**: `scikit-learn`, `numpy`, `matplotlib`
> ⚠️ **Note**: This is a simplified example with very limited data and a single feature (Passenger ID), and is **not meant for real-world analysis**.
---
## 📊 Dataset
```python
x_survived_ID = [[101], [102], [103], [104], [105]]
y_survived_or_not = [1, 1, 1, 0, 0]
````
* `x_survived_ID`: Passenger IDs (used as the only feature)
* `y_survived_or_not`: Survival status (1 = survived, 0 = did not survive)
---
## 🧠 Model
* **Algorithm**: Logistic Regression
* **Training/Test Split**: 80% training, 20% testing
* **Evaluation**:
  * Prints predictions on the test set
  * Displays accuracy score
  * Shows a bar chart comparing actual vs predicted outcomes
---
## 📈 Visualization
A bar graph compares actual vs predicted survival status for test passengers:
* Blue bars: Actual survival
* Orange bars: Predicted survival
---
## 💻 How to Run
1. Ensure the required libraries are installed:
```bash
pip install scikit-learn numpy matplotlib
```
2. Run the script:
```bash
python titanic_survival_prediction.py
```---
## 🧪 Output Example
```
Predictions: [1]
Accuracy: 100.0%
``
And a bar chart will be shown visually comparing actual vs predicted outcomes.
## 🚧 Limitations
* Uses only passenger ID as a feature (not meaningful for real prediction)
* Tiny dataset; not suitable for model evaluation
* Intended for **educational/demo** purposes only
