Health & Fitness Goal Prediction

The dataset used in this project is synthetic, but was carefully constructed based on real client progress patterns observed during my work as a Health Data Analyst and Coach. It captures realistic changes in key health and fitness indicators such as gender, age, weight, height, fitness level.


In addition to these core performance metrics, the dataset has been enhanced with critical physiological and behavioral variables commonly used in applied health analytics. These include:
Body fat percentage and muscle mass percentage, estimated with respect to gender, age, and physical performance benchmarks.
Diet compliance, training frequency, and presence of serious health conditions — all introduced as independent variables relevant for predictive modeling and outcome analysis.
The dataset was designed to reflect real-world gym constraints, physiological ranges, and demographic diversity — including beginners, overweight individuals, elderly clients, special population with health problems and athletes (advanced fitness level).
Although I have worked extensively with real health and fitness data in a professional setting, for this public-facing project, I created a synthetic and anonymized dataset to protect client privacy. This approach enables demonstration of practical machine learning applications in health analytics without compromising client confidentiality. Data was generated using logical rules and physiological ranges, then validated for consistency.

This project applies supervised machine learning models to predict whether a client will achieve their fitness goal, based on health indicators and behavioral metrics. 

## 📊 Models Used
- Decision Tree (tuned + balanced)
- Random Forest
- Logistic Regression
- K-Nearest Neighbors

## 🏁 Best Model
Random Forest & KNN — both achieved 75% test accuracy.

## 📌 Key Features
- `diet_compliance_binary`
- `training_frequency_per_month`
- `health_encoded`
- `fitness_level_ordinal`

## 📈 Metrics Evaluated
- Accuracy
- Precision, Recall, F1-score
- ROC AUC, PR Curve

## 🔍 Conclusion
Comparing ensemble, linear, and instance-based models revealed strong generalization with Random Forest and KNN. Logistic regression added interpretability. This project demonstrates a complete ML workflow applied to health-focused behavior prediction.

## 🔗 How to Run
1. Open the `.ipynb` file in Jupyter or Google Colab
2. Run all cells in order


