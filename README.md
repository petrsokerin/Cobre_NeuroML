# Cobre_NeuroML

Repo for final project of Neuroimaging and Machine Learning for Biomedicine course @ My University '22

## Requirements
- numpy==1.21.2
- pandas==1.5.1
- matplotlib==3.6.1
- seaborn==0.11.2
- sklearn==0.0
- xgboost==1.4.2
- torch==1.12.1
- torchvision==0.13.1
- nilearn==0.9.2
- monai==1.0.0
- tensorly==0.7.0
- networkx==2.5
- tensorboard==2.10.1
- comet_ml==3.31.15

## Idea

The idea of the project is to provide schizophrenia classification algorithm on MRI/fMRI data.

## Repository contents

| File or Folder | Content |
| --- | --- |
| Classical ML part/data AND  DL part/data| the folder contains data of correlation of brain areas. Correlation is build on fMRI data. 
We use [Cobre](http://fcon_1000.projects.nitrc.org/indi/retro/cobre.html) dataset |
| Classical ML part/best_metrics | the folder contains pickles with best params of grid search for different methods |
| Classical ML part/Final_project.ipynb | jupyter notebook contains algorithms implementation, calculation and estimation of results got with classical ML algorithms on correlations between brain areas|
| DL part/MRI.ipynb | jupyter notebook contains algorithms implementation, calculation and estimation of results on MRI data|
| DL part/fMRI.ipynb | jupyter notebook contains algorithms implementation, calculation and estimation of results on fMRI data|
| DL part/Combined_model.ipynb| jupyter notebook contains algorithms implementation, calculation and estimation of results on MRI, fMRI data and connectivities between brain areas|

## Results

The neural network, including three heads: MRI data, fMRI data and brain areas connectivity, - performs the best. Accuracy on the test set 0.933.

## Contacts

| **Name** | **Telegram** |
|----:|:----------:|
| Petr Sokerin | @Petr_Sokerin |
| Lidia Lidiia Rumiantseva | @Avenasativa |
| Nikita Belousov | @nokiroki1 |
