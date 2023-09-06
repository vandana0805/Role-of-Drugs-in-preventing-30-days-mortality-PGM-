# Role-of-Drugs-in-preventing-30-days-mortality-PGM-
Ranking of drugs that prevent mortality in patients with STEMI. The system is implemented using the Autoencoder/PCA to get the best covariates to 30 days mortality on highly imbalanced data using different ML/DL techniques, and the deepSHAP method is used for model explainability and ranking.
FILES:
Both the files are .ipynb so use a notebook to run them, preferably Google Colaboratoty.
PGM_Project.ipynb is the main source code and Copy_of_PGM_Project_SHAP.ipynb is the file where SHAP is implemented

LIBRARIES:
Make sure all the dependencies are satisfied

DATASET:
The dataset needs to be properly loaded.
The analysis has been done on both datasets but primarily the master dataset has been used for training models.

EXPLANATION:
Rest of the code is fairly self-explanatory.
We first perform the Pandas Profiling
The baselines are executed next
Next, the model is trained and evaluated on 5-fold cross-validation.
Finally SHAP is run on specific features while suppressing the other attributes using PCA.
