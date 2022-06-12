# Capstone Car Dealership Analysis


![carsin](./img/carsin.jpg)

## BUSINESS UNDERSTANDING
Used Car Lot TM is a newly established local business in India. The General Manager has requested some information about relative purchases of second hand vehichle in the regions. With fuiel prices increasing and transport being a dominant necessity, some buisness questions were presented for review. 1.Does fuel type affect the car price? 2. What are some other factors that share a connection to sales? 3. Elaborate on electric cars and do they make an impact on a sales or buisness perspective? 4. What areas in India sold the highest number of cars? 

From this analysis we intend on building a multiple linear regression model to predict what brand names will make the list.

The used car lot intends on using this information to ensure their business' prosperity and objectives are met. 

The information obtained will also be used to educate their staff and sales team and helping the business thrive. 

## DATA PREPARATION
Exploratory Statistical analysis used:  
•	Missing data 
•	Null values
•	Duplicates
•	Creating data frame 
•	Creation of Dummy Variables
•	Categorical Variables
•	Conversion of datatypes 
•	Complex lists and dictionaries
•	Statistical values to determine high correlation and significance
•	Multicollinearity of Independent variables
•	Reviewed for Normality of dataset
## MODELLING
The data science process used to build this model is the CRISPM process, visual diagram below. 
![CRISPDM](./img/CRISPDM.jpg)
Modelling analysis used: 
•	Mean Standard Error – MSE
    Mean Absolute Error - MAE
•	Polynomial Regression using an r2 score from log transformation – (fit/overfit)
•	Kernel Density Estimates were not utilised, rather I plotted a histogram to display distributions
•	Partitioned dataset to validate model using train-test splits rather than k-fold cross validation.
•	Log Transformation - see R2 score via test 0.95
•	Cross Validation utilised
 
Types of Graphical representations include: 
•	Scatter Plots
•	Histograms 
•	Heat Map
## CAPSTONE PROECT KEY DELIVERABLES
##TWO major features sharing Strong Relationships with the Used Cars Dataset 
1. 
2. 
##THREE Important Statistics
1. Adjusted Rsquared value 95.1%
2. F statistic: 1.033807218416428 P-value: 0.20199670346246976
3. Cross Validation  Scores: 
    Train error: 1.2389217848929732
    Test error: 1.2327474340985183
## Final Evaluation 
Points to review: 
•	-The data reflects homoscedasticity and the residuals should follow a normal distribution
•	-From this analysis we can infer thatmanual cars sell for less than automatic vehicles
    -The Ordinary Least Squares is a good model for prediction and inference at 95.1% adjusted Rsquared value.
    -Transmission and Owner type depict negative correlation to Price. 
    -Automatic transmissions tend to be more expensive and manuals sell for less according to this model. 
    -The year, mileage, power and number of seats have shown a positive assosiation with sale price. 
    
##DEPLOYMENT: 
-When deploying this model - ensure that the next phase has been managed appropriately. 
-All values have been processed and there is no need to run additional data or more tests to validate or confirm findings. 
-Relay the findings directly to Used Car Lot TM for review, clarification, and discussion. 


## MULTIPLE LINEAR REGRESSION INSTRUCTIONS
1.	Import the required libraries and read the dataset
2.	Data cleansing discovery methods
3.	Exploratory Data Analysis (EDA) 
o	Data Visualization
4.	Check for normality
o	Density plots
o	Q-Q plots
5.	Multiple linear regression model
o	Train test split
o	Train the model
o	Fit the model
o	Model predictions
o	Plot the results
6.	Residual analysis
o	Remove autocorrelation with varying lag values if present
o	Check for the normality of the variables
o	Train and fit the model
o	Make further predictions and plot the results
7.	Symbolic regression model
o	Create a model
o	Train the model
o	Fit the model
o	Make predictions and plot the result

## FOR MORE INFORMATION
Please review our full analysis in the Jupyter Notebook[Jupyter Notebook] (./Capstone.ipynb) or our [Capstone](./presentation.pdf).
For more information contact **Carla Kirby, ra_carlajoy@yahoo.com**

