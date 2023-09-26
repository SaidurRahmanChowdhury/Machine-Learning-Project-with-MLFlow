# Machine-Learning-Project-with-MLFlow


## Workflows

1. Update config.yaml
2. Update schema.yaml
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the app.py


# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/SaidurRahmanChowdhury/Machine-Learning-Project-with-MLFlow
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n venv python=3.9 -y
```

```bash
conda activate venv
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

MLFLOW_TRACKING_URI=https://dagshub.com/SaidurRahmanChowdhury/Machine-Learning-Project-with-MLFlow.mlflow \
MLFLOW_TRACKING_USERNAME=SaidurRahmanChowdhury \
MLFLOW_TRACKING_PASSWORD=4ad393ceeee708d51e6193825afa3adc0bcf0c5c \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/SaidurRahmanChowdhury/Machine-Learning-Project-with-MLFlow.mlflow

export MLFLOW_TRACKING_USERNAME=SaidurRahmanChowdhury 

export MLFLOW_TRACKING_PASSWORD=4ad393ceeee708d51e6193825afa3adc0bcf0c5c

```