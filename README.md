# PYTHON PROJECT:

Providing a dataset of employees working in ABC company. It consists of 458 rows and 9 columns. The company needs the detailed report and explanation of their employees in each team, also need to identify the following: 1.How many are there in each Team and the percentage splitting with respect to the total employees. 2.Segregate the employees w.r.t different positions. 3.Find from which age group most of the employees belong to. 4.Find out under which team and position, spending in terms of salary is high. 5.Find if there is any correlation between age and salary , represent it visually. Before doing the above questions,perform pre processing of the dataset. Also, the column height is having incorrect data, changing the data of that particular column with any random numbers between 150 and 180.

# Exploratory data analysis
EDA is a vital step in the data analysis process that entails visually and statistically analyzing datasets to find patterns, trends, and insights.

The principal goals of exploratory data analysis (EDA) are to detect anomalies in the dataset and develop recommendations for additional investigation, thereby guaranteeing a thorough comprehension of the subtleties of the data.

EDA provides insightful information that helps with hypothesis creation and decision-making by improving knowledge of data distribution, variable correlations, and anomalies. When all is said and done, the efficacy of data-driven projects is enhanced by EDA’s capacity to identify trends and anomalies.

## 1:Data preprocessing:
When referring to data preparation and cleaning, preprocessing is done before raw data is entered into an analytical tool or machine learning model. Missing value handling, feature scaling, categorical variable encoding, and outlier removal are all part of it. To improve the performance and interpretability of the model, it is important to make sure the data is in the right format. Data-driven jobs are more successful overall when preprocessing is used to reduce noise, standardize data, and optimize it for effective analysis.

## Data cleaning:
Data cleaning refers to the process of removing unwanted variables and values from our dataset and getting rid of any irregularities in it.such irregularities can disproportionality skew our data and hence adversely effect the result

## Team analysis:
1:find number of teams(30) were each employee exist,count most number of employee belong which team etc 2:visualised the team distribution using countplot for meaningful and easiest insight

## Position segregation:
1:count number of position have in the dataset,and calculate employee count in each position 2:visualisation of position distribution using countplot for best insight

## Age Group identification:
1:to identify predominant age group among employees 2:visualisation of corresponding distribution

## Salary analysis:
1:by bivaraite analysis,determine the team and position of employees with highest salary spending 2:visualisation salary distribution by using scatterplot

## Correlation between Age and SALARY:
1:Analyse the relationship between employees age and their corresponding salaries 2:diiscovered the correlation through heatmap for clear visualisation

## correlation:
Values close to +1 indicates strong positive correlation, -1 indicates a strong negative correlation and 0 indicates suggests no linear correlation. Darker colors signify strong correlation, while light colors represents weaker correlations. Positive correlation variable move in same directions. As one increases, the other also increases. Negative correlation variable move in opposite directions. An increase in one variable is associated with a decrease in the other.

## conclusion:
In summary, the Python-based exploratory data analysis (EDA) of the wine dataset has yielded important new information about the properties of the dataset. We investigated correlations between varaibles like age and salary, identified outliers, and obtained a knowledge of the distribution of important features using statistical summaries and visualizations. The quantitative and qualitative features of the dataset were analyzed in detail through the use of various plots like scatterplot,countplot . Finding patterns, trends, and possible topics for more research was made easier by this EDA method. Furthermore, the analysis demonstrated the ability to visualize and analyze complicated datasets using Python tools such as Matplotlib, Seaborn, and Pandas,numpy. The results provide a thorough grasp of the dataset and lay the groundwork for more in-depth studies and modeling.
