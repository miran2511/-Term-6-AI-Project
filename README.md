# 50.021 Artificial Intelligence Project 

## Project Description 

This project aims to create a model that can predict the optimal CFOP (Cross, First 2 layers, Orientation, and Permutation) move for any given state of a 3x3x3 Rubik’s Cube. 

The dataset used for this project can be found via this link: https://www.kaggle.com/datasets/antbob/rubiks-cube-cfop-solutions/data  

## Code Setup 

The setup can be found on ipynb files 'model.ipynb' and 'modelgpu.ipynb' where comments on how to load the dataset, model, training and testing are written. The model can be loaded and saved through pytorch loadstatedict and savestatedict functions. 

## Sub-directories 

- The 'dataset' folder holds the training sequences 
- The 'weights' folder is where the weights of the trained models are saved 