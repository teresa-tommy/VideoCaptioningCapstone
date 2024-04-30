# Automatic Video Captioning 

## Overview

The video captioning task for machine learning models entails the generation of textual descriptions for a given video. 
Some simpler models have been executed as experiments, with and without adversarial examples, to better understand the pros and cons of existing video captioning models.

Here, notebooks to run the CNN-LSTM and evaluation metrics are included. The LLaVA model was tested directly through its published UI. 

## Notebooks

### Notebook 1: Metrics.ipynb

Description:
- Metrics jupyter notebook shows calculations of metrics for BLEU, ROUGE-L, and METEOR scores for all of the experiments (CNN, CNN-Adversarial, LLaVA, LLaVA-Adversarial).
- Data folder is referenced

### Notebook 2: Notebook_Name_2.ipynb

Description:
- Enter stuff for running CNN here pls !

## Data

The `data` folder contains relevant resulting captions used in the notebooks. We based our data on the MSVD testing dataset. There is the base training data, results from training the CNN-LSTM("greedy") and 
LLaVA models with and without adversarial examples. 


## Usage

- Can run jupyter notebooks with data provided here

## Team

- Arian Alam, Teresa Thomas, Patrick Warner, Pranav Prabhu
