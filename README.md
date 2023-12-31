# Neural Network Classifier

This folder contains the code for the implementation of **Neural Network**. It contains the following folder and files:

- **NeuralNetworkFigures:** Contains all the figures generated by the code during training, testing and evaluation. It includes figures like *feature importance, hyper parameter tuning, Baseline optimal model performance * etc. that were generated during the data exploration, training and testing the classifier with different parameters. 

- **data:** Contains the datasets. It has several folders and files:
    - **fa/lda/mNorm/original/pca/tsne/zNorm:** These folders contain the main dataset divided into X_train, X_test, y_train, and y_test. These secondary files were created in the midterm after applying different data representation techniques. Secondary datasets are:
        - fa: Factor analysis applied on main dataset (10 features)
        - lda: Linear Discriminant Analysis applied on main dataset (2 features)
        - mNorm: Min-Max normalization applied on main dataset
        - original: Main dataset
        - pca: Principal component analysis applied on main dataset (10 features)
        - tsne: t-SNE applied on main dataset
        - zNorm: z-Normalization applied on main dataset

- **Neural-Network-Baseline-JI.ipynb:**  It has necessary comments to run the baseline NN model for room estimation problem.
- **Neural-Network-Feature-Importance-JI.ipynb:** It has code to find the feature importance by SHAP model.
- **Neural-Network-Param-Tune-JI.ipynb:** It has code to run the code for optimal parameter tuning. 
- **Neural-Network-Tuned-JI.ipynb:** This has code of the optimal model for room occupancy estimation.

- **How to setup the environment:**
Steps 
1: Install conda. Follow the instruction of the link below.
 https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html
2: Open shell or conda shell and create conda environment . Use the following command "conda env create -f environment.yml" . The project directory includes the environment.yml file. It contains all necessary libraries to run the code in conda environment. 
3: Navigate to the project directory. 
5: then run the shell command to open the jupyter notebook by this command " jupyter notebook --NotebookApp.iopub_data_rate_limit=1.0e10" 

**Thank you**