### End-to-End-Chest-Cancer-Classification-using-MLflow-DVC

#### Workflows

 1. Update config.yaml
 2. Update secrets.yaml [Optional]
 3. Update params.yaml
 4. Update the entity
 5. Update the configuration manager in src config
 6. Update the components
 7. Update the pipeline
 8. Update the main.py
 9. Update the dvc.yaml 

#### Dagshub 

MLFLOW_TRACKING_URI=https://dagshub.com/saggyd95/End-to-End-Chest-Cancer-Classification-using-MLflow-DVC.mlflow \
MLFLOW_TRACKING_USERNAME=saggyd95 \
MLFLOW_TRACKING_PASSWORD=bc08e4727e5255fdd03bbba5cc5cbca38a02e28c \

#### DVC cmd 
dvc init
dvc repro 
dvc dag 