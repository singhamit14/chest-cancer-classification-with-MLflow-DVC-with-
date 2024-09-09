# chest-cancer-classification-with-MLflow-DVC-with-


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml


## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

pip install dagshub


Run this to export as env variables (for Linux-Terminal):

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/singhamit14/chest-cancer-classification-with-MLflow-and-DVC.mlflow

export MLFLOW_TRACKING_USERNAME=singhamit14

export MLFLOW_TRACKING_PASSWORD=ccee19ec5b720c18f601ef4373a3b56c2 # change password

```

Run this to export as env variables (for Windowa-cmd):

```bash

setx MLFLOW_TRACKING_URI "https://dagshub.com/singhamit14/chest-cancer-classification-with-MLflow-and-DVC.mlflow"

setx MLFLOW_TRACKING_USERNAME "singhamit14"

setx MLFLOW_TRACKING_PASSWORD "ccee19ec5b720c18f601ef4373a3b56c2a56" # change password

```

Run this to export as env variables (for Windowa-Powersell):

```bash

$env:MLFLOW_TRACKING_URI="https://dagshub.com/singhamit14/chest-cancer-classification-with-MLflow-and-DVC.mlflow"

$env:MLFLOW_TRACKING_USERNAME="singhamit14"

$env:MLFLOW_TRACKING_PASSWORD="ccee19ec5b720c18f601ef4373a3b56c2a5" # change password

```

### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag


## About MLflow & DVC

MLflow

 - Its Production Grade
 - Trace all of your expriements
 - Logging & taging your model


DVC 

 - Its very lite weight for POC only
 - lite weight expriements tracker
 - It can perform Orchestration (Creating Pipelines)