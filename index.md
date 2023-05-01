
[Link to Analysis Repo](https://github.com/djtenpas/finalprojectanalysis)

[Link to Analysis Jupyter Notebook](https://nbviewer.org/github/djtenpas/finalprojectanalysis/blob/main/516project/Published%20Analysis%20Notebook.ipynb)


# Project Description

Because I started attending ISU in January, I have not collected enough data to use my own project data. This data comes from my advisor, Dr. Kaoru Ikuma, but it does not come from a research group that I am involved in. The data used in this project is water quality data sampled from a variety of locations along the Des Moines and Racoon River.

## Project Goals

One of the main problems my advisor described to me when she gave me this data was that the research group is struggling to figure out what data they have and what they can do with it. Therefore my goals for this project are:

* Wrangling the data and creating helpful visuals so that the gruop can understand **how much** data they have and **where** their data is located.
* Demonstrate concepts learned in this class to show what kind of analyses could be done

## Research Questions

In order to demonstrate multiple concept sin this class, I am exploring 2 research questions with this project:

1. Can I get a machine learning model to differentiate between upstream and downstream data of a point of interest? (Possible points could include Saylorville Dam, Red Rock Dam, and the Des Moines Metro Area)
2. Can I use a machine learning model to predict the dissolved oxygen content in the water at a sampling location?

## Class Concepts

The 5 class concepts I am applying to this project are:

1. Data Wrangling
2. API Calls
3. Unsupervised Machine Learning
4. Supervised Machine Learning
5. Data Imputation

***

# Project Workflow

![ProjectWorkflow](/516project/assets/img/ProjectWorkflow.png)

***

# Project Outputs

Here are a couple examples of the visualizations generated to help the group understand what data they have, how much of it they have, and where it is.

**Stacked Bar Plot**

![Stacked Bar Plot](/516project/assets/img/stackedbar0.png)

**Array of Bar Plots**

![Array of Bar Plots](/516project/assets/img/subbar0.png)

Here is a confidence matrix for the unsupervised machine learning model, KMeansClustering. As you can see, it was not very good at distinguishing between the two, but I think that is good! It is good to know manmade things along the river have not altered it to such a state that this model can differentiate between upstream and downstream data.

**KMeans Confidence Matrix**

![KMeans Confidence Matrix](/516project/assets/img/KMeansConfMatrixv.2.png)

Here are some plots of the supervised machine learning models vs. the actual measurements. As you can see, the model does a decent job at detecting when DO is going to change. All models here had an accuracy of ~90%.

**Random Forest Model Predictions vs. Actual Measurements**

![Random Forest vs. Actual](/516project/assets/img/RFvsActualPlot.png)

**Gradient Boosted Machine Learning Model Predictions vs. Actual Measurements**

![Boosted Model vs. Actual](/516project/assets/img/BoostedvsActualPlot.png)

**Random Forest Machine Learning Model Trained on Imputed Data Performance**

![Imputed Model vs. Actual](/516project/assets/img/ImputedModelvsActualPlot.png)

