# comparing-classification-prediction-models

As the title of this repo stated, I compare some classification algorithms on a dataset to predict a variable of the dataset.

The algorithms I used are:
- K-Nearest Neighbour
- Support Vector Machine Classification (with 3 different kernels)
- Decision Tree
- Random Forest
- XGBoosted Decision Tree
- XGBoosted Random Forest
All of them are compared without hyperparameter tuning. The algorithm with the highest F1-Score is to be chosen for a hyperparameter tuning and then re-evaluated.

The chosen model then is deployed here: https://huggingface.co/spaces/HaritsGH/Contraception-Method

The EDA still can be improved by finding more insights, and the model maybe can be improved by choosing a different set of features.
