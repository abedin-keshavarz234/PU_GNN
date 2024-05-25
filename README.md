# PU-GNN
A Positive Unlabeled Learning method for Polypharmacy Side-effects Detection based on Graph Neural Networks
PU- GNN
This repository provides a framework of three stages that combine several drug features to predict DDS-associated events, using attributed heterogeneous networks and multiple deep neural networks. 

 PU-GNN involves three main steps: 

 ![abs01](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/4afc98eb-9867-4eda-baa6-af81ddfc49c6)



1-Dimensionality reduction to extract optimal features: By reducing the feature dimensions, we aim to capture the most effective features for model evaluation. 

![9d756819-1f76-4e1e-97d4-68ddb5d89b93](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/d8f1c4b4-ff36-4a66-a57e-d0e43714dd62)

2-Addressing data uncertainty through positive unlabeled (PU) learning: We employ PU learning to identify positive and negative data from unlabeled data, reducing uncertainty and enhancing model accuracy. 


![2](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/fcb0c424-291d-42b8-8345-261cf1b65a8c)

3. Predicting simultaneous side effects of drug pairs using a Graph Neural Network model: Our method predicts polypharmacy between two drugs efficiently using a neural graph network-based model.

![32](https://github.com/abedin-keshavarz234/PU_GNN/assets/76855169/3e1365e0-9f4c-488d-96b7-127acbf0bd0a)

 We implement this model, which enables this model to be trained with GPUs. For additional details, read the published article for this work through this link.

Environments

Python 3.6.12 

Tensorflow 2.1

numpy 1.19

pandas 1.1.3

Usage
 You can access the data from the GitHub link. When using this code, you need to clone this repo and load all the files in the folder into your running environment first. Then, Copy the PU_GNN_ run_DS2.py file and run it in your environment. All the files you want are in the (project folder).
In the google colab environment, you can run the program by saving the project folder in the google drive environment.
Then copy and run the PU_GNN_ run_DS2 file in the google colab environment

