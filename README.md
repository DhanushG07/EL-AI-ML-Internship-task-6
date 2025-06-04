# EL-AI-ML-Internship-task-6

# KNN Classification – Iris Dataset | Task 6

## Internship Task – AI & ML | Elevate Labs

### Objective
Implement the K-Nearest Neighbors (KNN) algorithm to classify iris flower species using machine learning techniques. The focus is on understanding instance-based learning, optimal K selection, and visualizing decision boundaries.

## Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn (KNeighborsClassifier)  
- Matplotlib, Seaborn  
- Google Colab / Jupyter Notebook

## Dataset: Iris Dataset
- Source: UCI Repository on Kaggle  
- Total Samples: 150  
- Features:  
  - SepalLengthCm  
  - SepalWidthCm  
  - PetalLengthCm  
  - PetalWidthCm  
- Target Classes:  
  - Iris-setosa  
  - Iris-versicolor  
  - Iris-virginica

## Steps Performed

1. Data Loading & Exploration  
   Loaded Iris.csv and performed basic EDA.

2. Feature Normalization  
   Scaled features using StandardScaler for better distance measurement.

3. Model Building  
   Used KNeighborsClassifier from sklearn.

4. K Optimization  
   Tested different values of K (1 to 10) and selected the best.

5. Evaluation Metrics  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report

6. Visualization  
   - Plotted accuracy vs. K  
   - Visualized decision boundaries using Sepal features (2D)

## Visual Outputs
- Accuracy Comparison by K  
- Confusion Matrix  
- Decision Boundary Plot (K = 3)

All plots and outputs are included in the notebook.

## Repository Structure
 Iris.csv
 knn_iris.ipynb
 README.md
 images/
 decision_boundary.png (optional)

 
## Author
Dhanush G  
Email: dhanushg0710@gmail.com  
LinkedIn: https://www.linkedin.com/in/dhanush-g-805492345


