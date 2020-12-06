Jan 24, 2020
# Introduction
This repository contains codes used to train 2D layered CNNs for performing classification on supernova data (Artifact vs non-artifact).

Tools for use for other datasets:
1. Data visualization
2. Training CNN
3. Viewing model results: learning curves and predictions

# Dataset
The data can be found https://portal.nersc.gov/project/dessn/autoscan/
For further information refer: https://arxiv.org/abs/1504.02936v3


# Important file locations:
## Data files located at 
#### Raw downloaded data at: 
/global/project/projectdirs/dasrepo/vpa/supernova_cnn/data/raw_data
#### Data created after using the preprocessing codes is stored at:
/global/project/projectdirs/dasrepo/vpa/supernova_cnn/data/gathered_data/temp_data
#### Preprocessed data is stored at
/global/project/projectdirs/dasrepo/vpa/supernova_cnn/data/gathered_data
(It needs to be moved manually. This is to ensure that accidental running of the code doesn't overwrite the data.)
#### The results are stored at : 
/global/project/projectdirs/dasrepo/vpa/supernova_cnn/data/results_data/results

## Main computing code at: 
/global/u1/v/vpa/project/jpt_notebooks/Cosmology/Supernova-cnn

## Code for data processing: 
0_pre_processing/

## Main training code
2_main_code_training/
## Analysis code : 
3_analyze_results_jpt_notebooks/


Location | Description |
a | b |
c | d |




