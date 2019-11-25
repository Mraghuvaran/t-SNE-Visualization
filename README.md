# t-SNE-Visualization 


Knowledge on t-SNE sourced from  the following web-page... 

https://distill.pub/2016/misread-tsne/ 

Important points before deep diving into this Repo about t-SNE: 

**1.** Those hyperparameters really matter (perplexity). 

*The perplexity value has a complex effect on the resulting pictures. The original paper says, “The performance of SNE is fairly robust to changes in the perplexity, and typical values are between 5 and 50.”*

**2** Cluster sizes in a t-SNE plot mean nothing. 

**3** Distances between clusters might not mean anything.

**4** Random noise doesn’t always look random.

**5.** You can see some shapes, sometimes. 

**6.** For topology, you may need more than one plot.

In this repo you'll come across visualizing t-SNE components in diffent approaches. 

## Order to use files 

1. Forestfires.csv ## Dateset used 
2. Approach-1.ipynb 

# Approaach -1 

In this, by barely doung basic preprocessing of the target column we are making two components from all the feature's. 

Steps: 
- We'll be importing the required paackages. 
- Converting the features into appropriate data types. 
- Binning the target column into categories. 
- Plotting the scatter plot in the 2-D SPACE.
- Gradient descent in the t-SNE & visualization. 

# Approaach -2

In this, by preprocessing the data like feature-scaling & One-hot encoding. 

Steps: 
- We'll be importing the required packages. 
- Converting the features into appropriate data types. 
- Plotting the distribution plots for the categorical. 
- Feature scaling of numerical features & One-hot encoding of categorical features. 
- Creating clusters without the target feature. 
- Creating t-SNE components in 1-D, 2-D, 3-D using plotly package. 

# Approaach -3 

Combination of both. 
In this, we are doing both the feature scaling & one-hot encoding the data by considering the target column. 



