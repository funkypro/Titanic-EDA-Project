# Titanic-EDA-Project
If we were an insurance company in 1912, how would we determine the risk profile of a passenger? We need to find the correlation between a passenger's attributes (Class, Age, Sex) and their survival outcome.

# Titanic Survivalist: EDA & Data Cleaning
This project explores the Titanic dataset to identify key survival factors using Python.

## Key Insights
* **Outlier Detection:** Used Seaborn Box Plots to identify high-fare outliers in 1st Class.
* **Smart Imputation:** Handled 177 missing Age values by imputing the median age based on Passenger Class (Pclass).

## Tech Stack
* **Tools:** @Google Colab, @GitHub
* **Libraries:** Pandas, Seaborn, Matplotlib
## Deep Dive: Survival Probabilities
I analyzed the intersection of Gender and Class to refine the risk profile.
* **Observation:** Gender was a stronger predictor than wealth. 
* **Data Evidence:** 1st Class females had a ~96% survival rate, while 3rd Class males had only ~13%.
* **Conclusion:** For the insurance problem, 'Sex' must be weighted higher than 'Fare' in the final model.
