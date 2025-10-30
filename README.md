# Task 7 — SVM Classification (Linear & RBF)

## Objective
Train and compare Support Vector Machines (linear and RBF) for binary classification. Visualize decision boundary in 2D using PCA. Tune hyperparameters C and gamma.

## Files
- `notebook.ipynb` — full Colab notebook (scripts and plots).
- `breast-cancer.csv` — dataset (if allowed to include).
- `README.md` — this file.

## Steps performed
1. Load dataset and EDA (check missing values, class balance).
2. Feature preprocessing (dropped non-numeric, StandardScaler).
3. PCA to 2 components for visualization.
4. Trained baseline SVMs (linear and RBF).
5. Hyperparameter tuning using GridSearchCV for C and gamma.
6. Evaluated with stratified 5-fold CV and test set.
7. Visualized decision boundaries in PCA 2D space.
8. Saved final model and preprocessing artifacts.

## How to run
1. Open `notebook.ipynb` in Google Colab.
2. Upload `breast-cancer.csv` when prompted or mount Google Drive.
3. Run cells from top to bottom.
