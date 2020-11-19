# Biodiversity_Endangered_Species
Analyzing if a type of species is more endangered 

Biodiversity is a Capstone Project from Analyze Data with Python course at Courseacademy
All the codes are written in Jupyter Notebooks, and the analyzed data is imported from two separate csv files 
To view the code, please open Biodiversity.ipynb where I uploaded the csv into pandas dataframes.
The first few steps involve importing the necessary modules, importing species.csv into python and optimizing the species dataframe to run analysis.
In this case, this means grouping the data into groups/categories, filling in null values with an argument and adding in the necessary columns (such as 'is_protected' which provides an argument: True/False based on if there is any intervention for a particular species). The dataframe is then pivoted to make it easier to get the necessary information, from which we run Chi Square Hypothesis Test to determine if a species in one category is more likely to be endangered compared to another species. Chi Square is particularly useful in this case as the data is categorical and there are multiple species. 
We do similar manipulations with the observations data which is also stored in a dataframe, and represent the different number of observations of sheep per week at each park using a bar chart. We then finally end with calculating the number of sheeps (finding the required sample size) the scientists need to observe to test the effectiveness of a project at a desired confidence level (90% confidence interval)
