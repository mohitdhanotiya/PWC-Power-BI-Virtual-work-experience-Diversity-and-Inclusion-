# PWC Power BI Virtual work experience - Diversity and Inclusion

## Table of Content
- Problem Statement
- Importing Data
- Data Preparation
- Data Modelling
- DAX
- Data Visualization

### Problem Statement
The purpose of this analysis is to:
- Define proper KPIs in hiring, promotion, performance and turnover
- Create a visualisation for the HR manager that reflects all relevant Key Performance indicators(KPIs) and metrics in the dataset.

### Importing Data
The Dataset was provided by PWC Switzerland.

### Data Preparation
Dataset was loaded into Power BI , Data was tranformed and loaded in Power Query editor.
- Validation of each coloumn Data Type's
- Removing Unnecessary Row's and Column's

### Data Modelling
After the dataset was cleaned and transformed, The Data is ready for Modelling.

### DAX
- % of FeMale employees = CALCULATE(COUNT('Pharma Group AG'[Employee ID]),FILTER('Pharma Group AG','Pharma Group AG'[Gender]="Female"))/COUNT('Pharma Group AG'[Employee ID])
- % of Male employees = CALCULATE(COUNT('Pharma Group AG'[Employee ID]),FILTER('Pharma Group AG','Pharma Group AG'[Gender]="Male"))/COUNT('Pharma Group AG'[Employee ID])
  
### Data Visualization
- 100% Stacked bar chart to show Hiring by Job level based on gender
- Pie chart to show employees distribution(gender based)
- Pie chart to show employees distribution(Time type)
- Stacked bar chart to show performance rating
- 100 % stacked column chart to show employees distribution by Job level and age group
- Bar chart to show employees promotion in FY20 and FY21
- 100% Stacked bar chart to show Gender wise performance rating
