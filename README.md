# VISMAI-Drug-Discovery-app

Extended Virtual screening tool - VISMAI
Repository link- https://github.com/MinorMist/VISMAI-Drug-Discovery-app.git

Handled by Achyut M Sharma and Deepak Menon

github ID - [Achyut](https://github.com/minormist) [Deepak](https://github.com/Deepkmenon) 

## Steps to run the application---

1. Download and unzip the file
2. Create a venv if necessary
3. Check for dependencies or install from requirements.txt
4. Navigate to VISMAI-Drug-Discovery-app-main/ADMET and open cmd in the path
5. Run the command 'python manage.py runserver' ro run the application
-----------------------------------------------

# Leveraging Graph Neural Networks for Drug Likeness Prediction

# gcnn-sageconv.ipynb

This notebook implements a Graph Convolutional Neural Network (GCNN) using the SAGEConv layer, which aggregates information from neighboring nodes to compute node features. It starts with importing necessary libraries like PyTorch and PyTorch Geometric, followed by data loading and preprocessing steps to transform input data into graph structures. The model is defined using SAGEConv, and then trained in a loop, with parameters updated through backpropagation. The notebook concludes with evaluating the model on a test set, generating predictions, and displaying final results.

# gcnn-graphconv.ipynb

This notebook also focuses on implementing a GCNN, but with the GraphConv layer. It begins by importing essential libraries for model building and data handling, then proceeds to load and preprocess the data into graph format. The model is constructed using the GraphConv layer, which performs convolution operations on graph data. The training loop involves forward passes, loss calculation, and parameter updates. The model's performance is evaluated on a test set, and the notebook ends with predictions and result visualizations.

# GCN_Custom_Modified.ipynb

This notebook presents a customized implementation of a Graph Convolutional Network (GCN), potentially enhanced with additional layers and custom functions. It starts by importing necessary libraries, followed by loading and preprocessing the dataset into a graph format. The custom GCN model is defined and trained, with evaluation metrics like confusion matrices and classification reports generated to assess performance. The notebook includes specific modifications tailored for tasks like drug-likeness prediction, offering detailed insights into classification performance.
