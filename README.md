# SageMaker Deep Learning

## Project: Moon Data

### Source 

Project 4 from Udacity's [Machine Learning Engineer Nanodegree](https://www.udacity.com/course/machine-learning-engineer-nanodegree--nd009t)

### Description

Building a custom PyTorch neural network in Amazon SageMaker for binary classification that's separated into two classes; the data looks like two moon shapes when it is displayed and is often referred to as moon data.

- Generated and visualized moon data, saved it as a CSV file, and uploaded to S3
- Retrieved SageMaker session, role, and default bucket 
- Defined a custom neural network 
- Created a training script that loads data, parses training & model hyperparameters, instantiates a model, trains the model, and saves it 
- Created a PyTorch Estimator using the training script, then trained it on the moon data 
- Instantiated a PyTorch Model using the Estimator and predict script, used it to evaluate the moon data, then deployed it 
- Evaluated the model to find a recall of 0.861, precision of 0.791, and accuracy of 0.807
