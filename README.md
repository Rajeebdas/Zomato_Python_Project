# **Zomato Data Analysis Project**

## **Overview**
This project involves analyzing restaurant data from Zomato to gain insights into various aspects such as ratings, online orders, and restaurant types. The analysis is performed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

## **Table of Contents**
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Analysis](#analysis)
- [Visualizations](#visualizations)
 
## **Installation**
To run this project, you need to have Python installed on your machine along with the following libraries:
- Pandas
- NumPy
- Matplotlib
- Seaborn

You can install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn
```
## **Usage**
1.Clone the repository to your local machine:
```bash
https://github.com/Rajeebdas/Zomato_Python_Project.git
```
2.Navigate to the project directory:
```bash
cd Zomato_Python_Project
```
3.Open the Jupyter Notebook:
```bash
jupyter notebook MultipleFiles/Zomato_Python_Project.ipynb
```
3.Run the cells in the notebook to perform the analysis.

## **Data Description**
The dataset used in this project contains the following columns:
- **name**: Name of the restaurant  
- **online_order**: Whether the restaurant accepts online orders (Yes/No)  
- **book_table**: Whether the restaurant allows table booking (Yes/No)  
- **rate**: Rating of the restaurant  
- **votes**: Number of votes received  
- **approx_cost(for two people)**: Approximate cost for two people  
- **listed_in(type)**: Type of restaurant (e.g., Buffet, Dining) 

## **Analysis**
The analysis includes:

- Data cleaning and preprocessing
- Handling missing values
- Converting data types for analysis
- Grouping data by restaurant type and online order status
- Summarizing votes and ratings

## **Visualizations**
The project includes various visualizations to represent the data:

- Count plots for restaurant types
- Histograms for ratings distribution
- Box plots for ratings based on online orders
- Heatmaps to show the relationship between online orders and restaurant types
