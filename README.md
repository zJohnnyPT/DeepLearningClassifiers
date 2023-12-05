# Aprendizagem Computacional II - Project (UrbanSound Classification with Deep Learning)

## Objective
The goal of this project is to develop deep learning classifiers for urban sound data using the urbansound8k dataset. The task involves creating models capable of classifying sound excerpts into one of the ten predefined classes.

## Dataset: URBANSOUND8K
The urbansound8k dataset consists of 8732 labeled sound excerpts, each lasting less than or equal to 4 seconds. The classes include air conditioner, car horn, children playing, dog bark, drilling, engine idling, gun shot, jackhammer, siren, and street music. Detailed dataset information and download instructions can be found at https://urbansounddataset.weebly.com/urbansound8k.html and in the following associated paper http://www.justinsalamon.com/uploads/4/3/9/4/4394963/salamon_urbansound_acmmm14.pdf.

## Implementation
To complete this project, we were required to implement two out of the three provided classifiers:

- Multilayer Perceptron (MLP)
- Convolutional Neural Network (CNN)
- Recurrent Neural Network (RNN)

In our project we decided to explore the Multilayer Perceptron (MLP) and the Convolutional Neural Network (CNN), so in order to do this we considered the following steps: 
- Data Analysys
  - data_analysis.ipynb
- Data Pre-processing and Feature Extraction
  - data_preprocessing.ipynb
- Model Architecture Definition and Training
  - cnn_implementation.ipynb
  - mlp_implementation.ipynb
- Performance Evaluation
  - During the evaluation phase, we conducted a thorough analysis of the classifiers' performance using the following evaluation metrics:
    - Confusion Matrices
    - Accuracy and loss functions
    - Accuracy per class
  
## Libraries
Libraries that need download - 
