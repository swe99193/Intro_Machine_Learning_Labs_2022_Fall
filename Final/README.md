## Environment
in Colab environment

install additional packages:
```
pip install category_encoders
```

## Dataset
configure paths to data, saved models
```
PATH_TRAIN = os.path.join("dataset", "train.csv")
PATH_TEST = os.path.join("dataset", "test.csv")
PATH_SAMPLE = os.path.join("dataset", "sample_submission.csv")
PATH_MODEL = 'models.sav'
```

## train models
1. `Run All ` 0811521_Final_train.ipynb

## Reproduce submission (in Colab):
1. Download models: [Link to model](https://drive.google.com/file/d/1-SZTLqbPNoo6cPAZ44faAMUZYiQiXak3/view?usp=sharing)
2. `Run All` 0811521_Final_inference.ipynb
