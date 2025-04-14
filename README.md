# COMP7250 Machine Learning Project
## A comparison of SGD optimizers

### Overview
This project contains a comprehensive study on various Stochastic Gradient Descent (SGD) optimizers and their performance in different deep learning tasks. The project aims to evaluate and compare the convergence behavior and accuracy of multiple SGD variants.

### Models and Dataset
| **Deep Learning Task**          | **Models**                         | **Datasets**            |
|----------------------------------|------------------------------------------|---------------------------------|
| Image Classification             | Convolutional Neural Networks (CNNs)    | CIFAR-10    |
| Image Segmentation               | Mask R-CNN                       | COCO  |
| Sentiment Analysis               | Recurrent Neural Networks (RNNs)  | IMDB |
  
### SGD Variants 
  - Standard SGD
  - Adam
  - RMSprop
  - NAdam

### Installation
```
git clone https://github.com/Ivaney0430/COMP7250-Project.git
cd COMP7250-Project
pip install -r requirements.txt
```

### Result
| **Deep Learning Task**          | **Models**                         | **Result**            |
|----------------------------------|------------------------------------------|---------------------------------|
| Image Classification             | Convolutional Neural Networks (CNNs)    | (SGD)(Adam)(RMSprop)(NAdam)   |
| Image Segmentation               | Mask R-CNN                       | (SGD)(Adam)(RMSprop)(NAdam)  |
| Sentiment Analysis               | Recurrent Neural Networks (RNNs)  | (SGD)(Adam)(RMSprop)(NAdam) |


