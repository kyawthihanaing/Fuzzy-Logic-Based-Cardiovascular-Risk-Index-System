# A Weighted Mamdani Fuzzy Inference System for Cardiovascular Disease Risk Stratification

A research grade fuzzy logic system for cardiovascular disease risk assessment featuring certainty factor learning, operator optimization, and a transparent clinical risk index. Built with Python and validated on the UCI Heart Disease dataset (n=303). This system transforms uncertain clinical inputs into a continuous, interpretable CVD Risk Index from zero to ten.

Ideal for students, researchers, and developers working on interpretable AI or medical decision support.

---

## 🌟 Key Features

### ✔ Weighted Mamdani Fuzzy Inference System  
27 expert driven rules enhanced with learned certainty factors that scale rule reliability based on real clinical evidence.

### ✔ Operator Optimization  
Full comparison of MinMax and Product operators.  
Evaluated for accuracy, sensitivity, specificity, numerical stability, and interpretability.

### ✔ Graduated CVD Risk Index (0 to 10)  
The output is mapped into Low, Medium, High, and Very High categories aligned with ESC, SCORE2, and PREVENT clinical frameworks.

### ✔ Complete Python Implementation  
Includes fuzzification, membership functions, rule evaluation, aggregation, certainty factor integration, and centroid defuzzification.

### ✔ Full Validation Pipeline  
- Manual vs engine score comparison  
- Binary mapping test  
- Confusion matrices  
- Rule coverage and utilization analysis  
- Operator tradeoff comparison  

### ✔ Clinically Grounded Inputs  
Age, chest pain type, fasting blood sugar (continuous surrogate), total cholesterol, and resting blood pressure.

---

## 📊 Summary of Results

- 100 percent rule coverage  
- 100 percent dataset coverage  
- Perfect label consistency with MinMax  
- 64.7 percent accuracy with Product for binary mapping  
- Strong interpretability with low computational cost  

---

## 📁 Repository Structure

