# PROJECT_M3
Ironhack Data Analytics Module 3 Project 

*MACHINE LEARNING*

## Workflow
#### Feature Engineering
    Using the Diamonds data for the machine learning model to predict the price of the diamonds depending on their characteristics.

    First clean de Diamonds data set in  order to fix the missed values that could develop a problem in the model.

    Try to find and Clean outliers. 

    Change the categorical variables to numbers: 
        -1ΒΊ using label encoder
        -2ΒΊ using one hot enconding 
        -3ΒΊ Do it manually depending on the diamonds characteristics. (This is the best one for the model selected)
    
    Take log in certain Variables in order to normalize these. 
#### Training
    Find the best model, checking the different possibilities (linear-regression, Random_forest, Catboosting)
### Best model π€
    CatBoosting(n_iterations=1000) using grid to select the best option in hyperparameters
    
### Analysis
    Drop city and index to reduce noise and useless variables.
    The label encoder is not the best, better to do it manually in order to put weight in the labels and improve the models. 

    The number of iterations is maybe determinant, its possible to add one million and boost the prediction.
### Configuration π»
pandas 
numpy 
matplotlib
train_test_split
linear_model
ElasticNet
Ridge
RandomForestRegressor
Catboosting
    

### Folder structure πΎ
    βββ PROJECT_M1
        βββTRAIN_notebook(529,64)- MODEL 1
        βββTRAIN_notebook(532)- MODEL 2
        βββ Link.txt
        βββ README.md
        βββ .ipynb_checkpoints
        βββ .DS_Store

    
### Contact info
    j.dediego.abad@gmail.com