# Pymaceuticals Python Visualizations

## Background

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. Generated all of the tables and figures needed for the technical report of the study. Wrote a top-level summary of the study results.

### Initial Preparation

* Displayed the number of unique mice IDs in the data, then check for any mouse ID with duplicate time points. 

* Create a new DataFrame where the dpulicated data was removed. 


### Summary Statistics

* Createed two summary statistics tables:

    * For the first table, use the `groupby` method to generate the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen. This should result in five unique series objects. Combine these objects into a single summary statistics table.
    *
    * For the second table, use the `agg` method to produce the same summary statistics table using a single line of code.

### Bar and Pie Charts

* Generated a bar plot showing the total number of timepoints for all mice tested for each drug regimen throughout the course of the study.
    
![image](https://user-images.githubusercontent.com/90559756/163409110-3df6b3e3-cf4f-4343-a79e-7e66c1a77f71.png)
    
* Generated a pie plot showing the distribution of female or male mice in the study.
   
![image](https://user-images.githubusercontent.com/90559756/163409206-790694cf-73c5-4f3a-9669-03cb6ec126a3.png)

### Quartiles, Outliers and Boxplots

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

      
* Generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

![image](https://user-images.githubusercontent.com/90559756/163409424-d432601e-40b2-4d80-b03a-8bc8946e7a13.png)


### Line and Scatter Plots

* Selected a mouse that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

![image](https://user-images.githubusercontent.com/90559756/163409572-f15055ba-e3da-48f4-81bd-23fe84b8535c.png)

* Generated a scatter plot of tumor volume versus mouse weight for the Capomulin treatment regimen.

![image](https://user-images.githubusercontent.com/90559756/163409680-73db3f53-51c9-4b0a-bddf-0c1e1d0938f6.png)


### Correlation and Regression

* Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.

![image](https://user-images.githubusercontent.com/90559756/163409967-e2892530-6739-4d8a-aba9-18f7917a1964.png)


### Final Analysis

* Wrote five observations inferred from the data, which are included at the top of the notebook.

