# AURORA-MINDS

This repo contains the Machine Learning and Federated Learning Simulations for the project AURORA-MINDS.

AURORA MINDS was funded through TRUSTCHAIN, an EU-Project (GA No 101093274) fostering a human-centred, trustworthy and sustainable internet.

## Requirements
The project is dependent on classic data science packages:
- pandas
- matplotlib
- seaborn
- scikit-learn
- numpy
- scipy
- torch
- jupyter notebook
- tenseal
You can install them with pip or/and conda.

Example:
```cmd
conda install pytorch torchvision torchaudio pytorch-cuda=11.8 -c pytorch -c nvidia
conda install scikit-learn -c conda-forge
conda install -c conda-forge matplotlib
conda install pandas
conda install seaborn -c conda-forge
pip install notebook tenseal
```

## Client Selection
- [X] Random Sampler
- [X] Std Sampler
- [X] Quantity Sampler
- [X] Intelli Sampler

## Aggregation Algorithms 
- [X] SimpleAvg
- [X] FedMedian
- [X] FedAvg
- [X] FedNova
- [X] FedAdagrad
- [X] FedYogi
- [X] FedAdam
- [X] FedAvgM


## Evaluation Metrics 
- [X] Presicion@k
- [X] AUC-ROC
- [X] Average Precision
- [X] SIREOS


## Experiment

You can directly reproduce our experiments for all settings using the following commands for each learning setting.
### Centralized
```commandline
python experiment_public/centralized.py
```

### Local
```commandline
python experiment_public/local.py
```

### Federated
```commandline
python experiment_public/federated.py
```
