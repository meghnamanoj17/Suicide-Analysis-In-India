# Suicide-Analysis-In-India
### CSE3306- Essentials of Data Analytics Project 

---

### Implementation:
1. Data Pre-processing
The Suicides in India dataset was imported from Kaggle and loaded. It contains several parameters like state, year, gender, age types which include suicide causes, by means adopted, professional profile, social status etc that could be reasons for committing suicide. We checked if the dataset contained missing/null values. Since the dataset was already clean, we further went to the exploratory data analysis part.

2. Exploratory Analysis
We need to observe and analyze the data to see what we are working with. The goal is to learn more about the data, the different types of data, outliers, and how to handle them. We used the seaborn and matplotlib libraries to visualize the plots and statistics.

3. Analyzing Vulnerability 
Using the data we explored, it was quite evident that a certain group of people are more prone to committing suicide than the rest. We did end up coming to this question about, what would be the best way to analyse how vulnerable a person is to committing suicide and we decided to go with naive bayes. 
Using pivot tables in MS Excel we were able to extract all important features that our result depended upon. Then when the required information was collected, we calculated the probability of all the records in the csv file. We then load all these values into a python notebook where we have information about other patients, using their information we calculate the probability of how vulnerable they are. This value can be used to compare various patients to know who will require the most amount of effort and probably should get more attention.
