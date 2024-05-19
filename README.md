Employee Data Analysis 
-----------------------

Project is based on dataset of Employees of ABC company consisting of 458 rows and 9 columns.Dataset contains names, teams, numbers, positions, ages, heights, weights, colleges, and salaries columns.the goal of project is preprocessing the dataset, analyzing the data, and  finding graphically

Data Preprocessing:
------------------

Importing Libraries and Dataset:
Examine the information about the dataset such as data type, number of rows and columns, etc.using info().and read and analyse the data

Description of the data :
use describe() function which gives the count, mean, standard deviation, minimum, and quartiles for each numerical column. The dataset’s central tendencies and spread are briefly summarized.

Finding Missing Values:
Checks for missing values in each column of the DataFrame ‘df’ and returns the null values for each column

Data Correction:
Corrected the 'Height' column by replacing its values with random numbers between 150 and 180 to ensure data consistency.

Data insight
--------------

Team distribution:
The distribution of employees across each team New Orleans Pelicans: 19 employees Memphis Grizzlies: 18 employees Utah Jazz: 16 employees New York Knicks: 16 employees Milwaukee Bucks: 16 employees Brooklyn Nets: 15 employees..

The percentage split relative:
It shows New Orleans Pelicans-4.148472 have high percentage and Orlando Magic and Minnesota Timberwolves have low percentage.

Position Distribution:
 Employees are distributed as five positions and numbers of employees are SG-102,PF-100,PG-92,SF-85 and C-79.

Age grouping:
Employees age starting from 19 to 40 and most employees are 20 to 30 age group.

salary expenditure:
Team Cleveland Cavaliers have with Highest Salary Expenditure and C Position with Highest Salary Expenditure.

correlation:
The correlation analysis between age and salary yields a coefficient of 0.214. This positive correlation suggests a weak but discernible relationship between age and salary of employees.

Conclusion:
-----------

The Dataset of ABC company data is Preprocessing, Analysis, and Visualized by using different methods.Preprocessing steps ensured data integrity, while subsequent analyses unveiled compelling patterns and correlations.The employees various attributes analysed and visualize the data frequency by using different graphs.


