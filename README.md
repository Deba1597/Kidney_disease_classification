# Kidney_disease_classification


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
10. update app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/Deba1597/Kidney_disease_classification
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -p cnncls python=3.8 -y
```

```bash
conda activate cnncls
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```

## MLflow

- [Documentation](https://mlflow.org/docs/latest/index.html)


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/Deba1597/Kidney_disease_classification.mlflow \
MLFLOW_TRACKING_USERNAME=Deba1597 \
MLFLOW_TRACKING_PASSWORD=98df3678b523b2747c0a2e7aae9d66aaf0dcd9d7

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/Deba1597/Kidney_disease_classification.mlflow \
export MLFLOW_TRACKING_USERNAME=Deba1597 \
export MLFLOW_TRACKING_PASSWORD=98df3678b523b2747c0a2e7aae9d66aaf0dcd9d7 \
```