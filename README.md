# Shipment Pricing Prediction

## Problem Statement

With the global supply chain becoming increasingly complex, predicting shipment pricing has become crucial for companies looking to optimize their logistics costs. Shipment prices fluctuate based on various factors such as destination, mode of transport, product type, and quantity. This project aims to predict shipment prices to help businesses plan their logistics economically.

### Project Approach

#### 1. Data Exploration

##### Tools Used: Pandas, Numpy
###### Objective: Understand the structure and content of the dataset.
##### Steps:
- Loaded the dataset.
- Checked for missing values and basic statistics.

#### 2. Data Visualization

##### Tools Used: Matplotlib, Seaborn
##### Objective: Gain insights into the relationships between variables.
##### Steps:
- Plotted heatmaps to visualize missing values.
- Created count plots for categorical features like shipment modes.
- Used histograms and box plots to understand distributions and detect outliers.

#### 3. Feature Engineering

##### Objective: Enhance the dataset with meaningful features.
##### Steps:
- Extracted relevant date and time features.
- Encoded categorical variables such as country, shipment mode, product group, sub-classification, and brand.
- Calculated the total value of shipments.
- Handled missing values by imputing or removing them as necessary.

#### 4. Model Selection

##### Objective: Identify the best machine learning model for prediction.
##### Steps:
- Tested various regression models to establish a baseline accuracy.
- Evaluated models using residual plots.
- Selected the best model based on accuracy and fit.

#### 5. Hyperparameter Tuning

##### Tools Used: GridSearchCV, RandomizedSearchCV
##### Objective: Improve model performance.
##### Steps:
- Tuned hyperparameters of the selected model.
- Cross-validated to avoid overfitting.

#### 6. Model Deployment

##### Objective: Create a user interface for predicting shipment prices.
##### Tools Used: Flask, HTML, CSS
##### Steps:
- Developed a web application using Flask.
- Created forms to input shipment details.
- Displayed predicted prices to the user.

### Running the Project

#### Prerequisites
- Python 3.x
- Flask
- Pandas
- Numpy
- Scikit-Learn
- Matplotlib
- Seaborn

#### Technologies Used
- Python
- Scikit-Learn
- Flask
- HTML, CSS
- Pandas, Numpy

### Contributing

If you find any bugs or have suggestions for improvements, please raise an issue or submit a pull request.

### Contact

Shiny  
Email: shinyshajeev@gmail.com  
LinkedIn: [Shiny's LinkedIn](www.linkedin.com/in/shiny-ml-engineer)

Gobikrishnan  
Email: gobikrishnanm1999@gmail.com  
LinkedIn: [Gobikrishnan's LinkedIn](http://www.linkedin.com/in/gobikrishnanm1999)

Sriram  
Email: sriram.natarajan94@gmail.com  
LinkedIn: [Sriram's LinkedIn](http://www.linkedin.com/in/sriram-natarajan94)
