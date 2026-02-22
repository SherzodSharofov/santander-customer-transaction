# santander-customer-transaction

santander-customer-transaction/
├── README.md
├── data/                          # original data(train and test)
├── lgbm_with_optuna.ipynb         # EDA, model training and hyperparameter optimization with Optuna
├── lgbm_with_optuna.db            # SQLite database for saving Optuna optimization progress
├── lgbm_best_model.joblib         # saved model with pipeline
├── api_source_for_model.ipynb     # FastAPI service with the trained model
├── testing_api.ipynb              # testing API and making predictions
└── submission.csv                 # submission file with final predictions
