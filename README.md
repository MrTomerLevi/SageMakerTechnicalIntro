# Amazon SageMaker Technical Intro
This repo contains SageMaker essentials for training and deploying a model.

In the `.ipynb` notebook we walk through the process of creating a model from 0->100.<br/>
The notebook composed of the following steps:
* Loanding `csv` data (`fifa_dataset.csv`)
* Basic feature engineering 
* Creation of SKLearn regressor using a dedicated script (`script.py`)
* Training job using SageMaker `Estimator` (`SKLearn`)
* Tuning job using SageMaker `HyperparameterTuner` 
* Deploying the model into a live inference endpoint
* Applying auto-sacling to the model using an auto-scaling policy
* Clean up
