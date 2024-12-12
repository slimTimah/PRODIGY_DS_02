### PRODIGY_DS_02

#### Introduction
This analysis explores the Titanic dataset which contains information of the passengers and crew members on the ill-fated ship. The analysis describes different ticket-class company that ranges round upper, middle, lower, highest ticket fare and lowest ticket fare.

### Project Title
Titanic Analysis 

### Aims and Objectives
- Highlight significant sales trends
- Spot patterns affecting sales projection
- Provide strategic suggestions for future sales
- Improve saes outcome over time

- ### Data Source
- The data used was downloaded from kaggle

- ### Tools used
- Microsoft Excel, Power Bi, Python

### Data Cleaning/Preparation
- Th passengerId represents each passenger as a unique identifier and no duplication of the passengerId
- A column which contains variables of ticket class was removed an then replace with a refrecing column
- Null values were removed
- From the embarket column, the city provided were represented with a code and the codes were replaced with the city name as given in the metadata
- Column Cabin was removed 

### Exploratory Data Analysis
- Total number of female and male passengers seperately
- Total number of survived female passengers that embarked from Southampton
- Total number of male passengers that did not survive the titanic within lower ticket class or Upper
- Total number of each passengers in ticket classcategory
- Passengers with highest siblings and spouse     

### Data Analysis
This is an example code used in this project

```
Python
UpperClass = 0

for upper in titanicData['TicketClass']:
    if upper == 'Upper':
        UpperClass+=1

print (UpperClass)
```
#### Conclusion
##### The result shows the following:
- Tesco store in South London recorder the highest sales while Tesco store in North London recorded the lowest sales
- The day with the lowest sales is Monday while the day with highest sales is Sunday
