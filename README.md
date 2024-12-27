# House-Price-Prediction
Predicting house price with linear regression and with feature selection

## Tech :hammer_and_wrench: Languages and Tools :

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original.svg" title="Jupyter Notebook" alt="Jupyter Notebook" width="40" height="40"/>&nbsp;
  <img src="https://assets.st-note.com/img/1670632589167-x9aAV8lmnH.png" title="Google Colab" alt="Google Colab" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" title="Numpy" alt="Numpy" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg"  title="Pandas" alt="Pandas" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/scikitlearn/scikitlearn-original.svg"  title="Sci-kit Learn" alt="Sci-kit Learn" width="40" height="40"/>&nbsp;
</div>

## Run the Notebook on Google Colab

You can easily run this code on google colab by just clicking this badge [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AsadiAhmad/House-Price-Prediction/blob/main/Code/House_Price_Prediction.ipynb)

## Algorithms used

- Pearson Correlation : for features selection
- Mutual Information : for feature seletion
- Linear Regression algorithm : for training model

## About the Dataset
### Download Dataset
you can use this Dataset with clicking this badges :

Train set : [![Static Badge](https://img.shields.io/badge/Trainset-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/House-Price-Prediction/blob/main/Dataset/train.csv)

Test Set : [![Static Badge](https://img.shields.io/badge/Testset-red?style=for-the-badge&logo=databricks&labelColor=fcfbd4)](https://github.com/AsadiAhmad/House-Price-Prediction/blob/main/Dataset/test.csv)

### Using Dataset on jupyter notebook
on the step 3 of the code file you can easily use the dataset like importing this code:
```sh
train_set_url = "https://raw.githubusercontent.com/AsadiAhmad/House-Price-Prediction/refs/heads/main/Dataset/train.csv"
test_set_url = "https://raw.githubusercontent.com/AsadiAhmad/House-Price-Prediction/refs/heads/main/Dataset/test.csv"

pd.set_option('display.max_rows', None)

train_set = pd.read_csv(train_set_url)
test_set = pd.read_csv(test_set_url)
```
