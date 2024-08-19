
# General Notes on Clustering 
While Regression and Classification fall under Supervised Learning, Clustering falls under Unsupervised Learning. 

## Introduction
This repo contains 10 different types of clustering models (i.e. K means,  agglomerative, mean shift, etc) and a demonstration of how they work along with hands-on projects. 

## Dataset
- This dataset is called Mall_Customers. It contains customer ID, gender, age, annual income and spending score. The ask is to categorize customers, for targeted marketing. 

Annual income (y axis) and spending score(x-axis) are most relevant variables that can help create clusters. In clustering, we don't use y (unlike in supervised). Iloc will help select relevant rows and columns. 

Prior to creating model for K-means, number of clusters is evaluated via elbow method via matplotlib library. 

## Model Creation/Learning
- Data Collection
- Data Preprocessing
- Input Split (as this is clustering there is not input/output split and no test/train split)
- Create model 
- Test the fit 
- Save the best model 

## Model deployment
1 - Creating the model (in jupyter notebook)
2 - Saving the model (using pickle, save the finalized model and perform pickle dump which will result in a .sav file) 
3 - Deploying the model (create new deployment notebook to call on and open the saved model) 

## Evaluation Metric Results
	- Obtained 5 clusters of customers that categorize them on the basis of their spending score and annual income to help with targeted marketing 

![image](https://github.com/user-attachments/assets/5ce63905-6b93-4557-8d24-5b0f910a4b01)
