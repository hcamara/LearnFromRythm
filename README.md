# How it works

## Getting started
LearnFromRythm project consists of learning from rhythm.  <br/> CNN is used for classification problem, 
tempo feature and average of beats <br/>  are used to detect similarity between two or more songs. 

### How to generate datasets
To create a new model, you must generate training datasets. <br/> 
To generate data for tests, use the following command:

```
python datasets_generator.py
```
This command has two characteristics, first it generates data for training <br/> and 
second, it also generates data for tests

### How to create model
To create a template and evaluate it, you must use the following command:

```
python create_model.py
```

### How to make prediction
Make the prediction is very easy, you can use the next<br/> 
command to predict musical genre based on your previously created model

```
python predict.py
```
REST API version is also available,just use  the following command : 

```
python rest_api.py
```
