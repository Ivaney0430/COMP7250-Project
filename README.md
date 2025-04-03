# COMP7250 Machine Learning Project - A comparison of SGD optimizers

## Overview
This project contains a comprehensive study on various Stochastic Gradient Descent (SGD) optimizers and their performance in different deep learning tasks. The project aims to evaluate and compare the convergence behavior and accuracy of multiple SGD variants.

## Models and Dataset
Deep Learning Task |   Model    | Dataset 
-------------------|------------|--------
Convolutional      | Simple CNN |
Neural Network     | Resnet     |
-------------------|------------|--------
Recurrent Neural Network|LSTM |
  
## SGD Variants 
  - Standard SGD
  - Adam
  - RMSprop
  - NAdam

## Installation
'''
git clone https://github.com/Ivaney0430/COMP7250-Project.git
cd COMP7250-Project
pip install -r requirements.txt
'''

##Result
Deep Learning Task |   Model    | SGD Optimizer | Result (Test Loss) 
-------------------|------------|---------------|------------------
                   | Simple CNN |      SGD      |
                   |            |      Adam     |
                   |            |    RMSprop    |
                   |            |     NAdam     |
  Convolutional    |------------|---------------|------------------
  Neural Network   |            |      SGD      |
                   |  Resnet50  |      Adam     |
                   |            |    RMSprop    |
                   |            |     NAdam     |
-------------------|------------|---------------|------------------
                   |            |      SGD      |
      Recurrent    |    LSTM    |      Adam     |
   Neural Networl  |            |    RMSprop    |
                   |            |     NAdam     |
 
