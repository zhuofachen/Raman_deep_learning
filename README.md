# Raman_deep_learning
This project focuses on applying machine learning and deep learning techniques to classify graphene Raman spectroscopic data

This work is published on [arXiv](https://arxiv.org/abs/2203.00431)



### Overview
![Table of content](figures/table_of_content.png)


The impact of the environment on graphene's properties such as strain, charge density, and dielectric environment can be evaluated by Raman spectroscopy. Variations, artifacts, and environmental differences pose a challenge in traditional spectral analysis. In this work, we developed a deep learning model to overcome the effects of such variations and classify graphene Raman spectra according to different charge densities and dielectric environments. We demonstrated the spectra classification with 99% accuracy using a convolutional neural net (CNN) model. Our approach has the potential for fast and reliable estimation of graphene doping levels and dielectric environments. The proposed model paves the way for achieving efficient analytical tools to evaluate the properties of graphene. 

### Schematic of collecting data and prediction
![schematic_of_experiment](figures/Figure1_schematic_of_experiment.png)

### Flowchart of this work
 Before feeding into any models, all the raw data is rescaled and the cosmic rays are removed. In the data augmentation step, we applied peak shifting to better capture all
expected variations in the collected spectra. Each model is studied with different noise levels. 5 different machine learning models (SVM, RF, KNN, DT, NB) and 4 different deep learning models (CNN, FullCNN, FC, and MHCNN) are implemented. All the models are trained, tuned, and optimized and the optimal performances are compared. 
![Flowchart](figures/Flowchart_of_experimental_design.png)


### Machine learning prediction
![Machine learning results](figures/Figure2_machine_learning_results.png)




### Deep learning prediction
![Deep learning results](figures/Figure3_Deep_learning_results.png)

Please refer to our paper for more details

### How to use
```
git clone https://github.com/zhuofachen/Raman_deep_learning.git
```
