# End-to-End-Chest-Cancer-Classification-using-MLflow-DVC-Y


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

- [MLflow tutorial](https://youtube.com/playlist?list=PLkz_y24mlSJZrqiZ4_cLUiP0CBN5wFmTb&si=zEp_C8zLHt1DzWKK)

##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/ankitkrissna1234/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC-Y.mlflow \
MLFLOW_TRACKING_USERNAME=ankitkrissna1234 \
MLFLOW_TRACKING_PASSWORD=b149c5fd4dd3af24d389774dda91645d38e51783 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/ankitkrissna1234/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC-Y.mlflow

export MLFLOW_TRACKING_USERNAME=ankitkrissna1234

export MLFLOW_TRACKING_PASSWORD=b149c5fd4dd3af24d389774dda91645d38e51783

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
