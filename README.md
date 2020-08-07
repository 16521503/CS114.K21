# Installing Packages
Using `conda`:
```
(venv) $ conda install --file requirements.txt
```

Using `pip`:
```
(venv) $ pip install -r requirements.txt
```

# Dataset information
```
 - Dataset will be save in images folder, which contain 2 folder, train and test folder.
 - For each folder will be devide two folder, motorbike and non-motorbike for train and test.
```

# Train model(step to step)
```
 - Director to dataset defined in constants.py file.
 - Run file train.py to train model and save it in project. 
 - Model will be save as model.sav file.
```

# Test model(step to step)
```
 - Run file test.py to test model.
 - Model was saved when trained in the last step, will be load to run test. Dont need to train model again.
 - Result of test will be print in compiler run time.
```