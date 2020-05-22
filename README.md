# MSBD5002 Highway Tollgates Traffic Flow Prediction Course Project
## Introduction
1. The programming language used in this project is python 3.
2. The packages used in this project including: pandas, numpy, sklearn, scipy, matplotlib, seaborn, pytorch, skorch, xgboost, lightgbm, etc.
## Project Details
### Data processing
Codes about `Loading data` and `Data preprocessing`, original data and processed data are kept in `dataprocessing` folder.
1. Run `Previous 2-hour train.ipynb`, it can generate '2h_route_avg_train.xlsx'.
2. Run `Previous 2-hour test.ipynb`, it can generate `2h_route_avg_test.xlsx`.
3. Run `5002_data_preprocessing.ipynb`, it can generate `training_nn.csv` and `test_data.csv`.
4. These files already exist in `processed_data` folder, to rewrite these files, you need to uncomment the corresponding code block.
### Models and evaluation
Codes about `Prediction algoritm` and `Performance` and our models are kept in `models` folder.
1. Run `Training part` in `Train and Ensemble Models.ipynb`, it can generate `.pkl` files of our models.
2. Run `Ensemble model and Evaluation in validation dataset` part in `Train and Ensemble Models.ipynb`, it can load pre-trained models and get responding results and perform prediction on validation data and compute MAPE of the ensemble model.
3. Run  `Prediction on test data` part in `Train and Ensemble Models.ipynb`, it can generate `submission.csv`.

### Submission
Our submission file is kept in `submission` folder named `submission.csv`.
