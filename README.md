
# Introduction
This repository contains codes used to run training and inference of 2D layered CNNs for performing classification on supernova data (Artifact vs non-artifact).

# Dataset
The actual data used for training can be obtained using the information in https://portal.nersc.gov/project/dessn/autoscan/

# Repository information
The Table below describes the content of various folders in this repository

| Description | Location |
| --- | ---|
| Setting up the conda environment| conda_env/ | 
| Code to run inference on the stored models| model_inference/ | 
| Code to train new models | train_code/ | 


# Running Inference

To run inference on the best CNN model, use the code in the folder `model_inference/Model_inference.ipynb`
The best CNN model is stored at https://portal.nersc.gov/project/m3363/vayyar_des_cnn/

# Training new models
New models can be trained using the code in the folder `train_code/`. The model architecture is defined in the file `models.py`.

# Conda environment
The best way to run these codes is using conda environment. To build the conda environment use the files in ther folder
`conda_env/`. The file `conda_env/environment.yml` can be used to build the environment. The file `conda_env/additional.txt` contains additional packages that need to be manually installed inside the conda environment.



