# Applications-of-Data-Science

OptIForest — Replication & Application

Goal: Replicate OptIForest on AD data, then apply to Credit-Card Fraud and a synthetic California Housing dataset.


Files:

1) Replica.ipynb: Reproduces OptIForest on the original AD dataset with NumPy patch, baseline IsoForest, and metrics/plots.

2) ExistingData(CreditCard).ipynb: Loads creditcard.csv, preprocesses, compares IsolationForest vs OptIForest, and visualises AUC-ROC/AUC-PR.

3) NewData(CaliforniaHousing).ipynb: Builds a synthetic anomaly set from California Housing, runs both models, and reports side-by-side metrics/plots.

4) requirements.txt 

5) README.md


How to run (Colab):

Open a notebook → run the first setup cell (safe clone + NumPy patch). 

For credit-card, upload creditcard.csv when prompted. Run all cells.


Notes: Raw creditcard.csv is not included. Outputs/processed data are generated at runtime.
