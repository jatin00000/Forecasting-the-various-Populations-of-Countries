# **Forecasting-the-various-Populations-of-Countries**
**Data Science Project** <br/>
&emsp; &emsp; _Extracted Population data from United Nation website. Data set contains information about various type of population of various countries of World from 1950 to 2019, with many null values. Using various algorithms (Decision Tree, Random Forest, SVM etc.) to see which one best fits the data most accurately. Explored the data, and provided insights and forecasts about population for various countries._<br/> <br/> <br/>
My Team Members~<br/>
&emsp;- Abhay Panwar<br/>
&emsp;- Chetan Kumar<br/>
&emsp;- Gaikwad Chandan Mahadeo<br/>
&emsp;- Devansh Mishra<br/>
&emsp;- Mallempadi Yashaswini<br/>
<br/>
<br/>
It has 6 tasks~<br/>
  &emsp; _a. Data collection <br/>
  &emsp; b. Data Preprocessing and Cleaning <br/>
  &emsp; c. Data Visualization<br/>
  &emsp; d. Data Statistics(Summary of statistics)<br/>
  &emsp; e. Hypothesis Statement<br/>
  &emsp; f. Prediction Task(Using Machine Learning Model)_<br/>
<br/>
<br/>

**Data Collection**
<br/>
The data is extracted from https://population.un.org/wpp/Download/Standard/CSV/ <br/>
Information about usage of various Classifiers is taken from http://www.Datacamp.org <br/>
- - - -

[**Data Preprocessing and Cleaning**](https://github.com/jatin00000/Forecasting-the-various-Populations-of-Countries/blob/main/Source_code/Data_Preprocessing.ipynb) <br/>

- Taking only medium variant of Population in consideration<br/>
- Removing column varID, variant and MidPeriod<br/>
- We used built-in train_test_split in 70/30 split as it provide good accuracy.<br/>
- - - -

**Data Visualization** <br/>
- Plotted scatter Plot of all 4 attributes for 10 different countries<br/>
- Also calculated R^2 for each case using Plotly<br/>
- To select one attribute out of four attributes for hypothetical testing<br/> 
  - Male Population<br/> 
  - Female Population<br/> 
  - Total Population<br/>
  - Population Density<br/>
- - - -

**Data Statistics** <br/>
- Select one attribute from four to make a model for Prediction by making observations from graphs plotted during visualization.<br/>
- Through statistics, find out the names of countries Possible whose total population will be in the range 5000 to 15000 in 2011.<br/>
- - - -

**Hypothesis Statement**
<br/>
From statistics, we have created a hypothetical statement. Try to prove it by creating a model.<br/>
- - - -

**Prediction Task(Using Machine Learning Model)**
<br/>
- Compared accuracy of various classifiers and selected one for making model.
- Experimentally, Our model proves our Hypothetical statement which is based on using “Total Population” as an attribute to make our model Wrong.<br/>
- Created a model using various algorithm<br/>
  - Decision Tree Classification<br/>
  - Random Forest Classification<br/>
  - Support Vector Machines(SVM)
  - Logistic Regression<br/>

- - - -
**My Experience and Learnings**<br/>
Coded in python language and Google Collab.<br/>
Learned usage of various python modules Numpy, Pandas, Plotly, csv and sklearn.<br/>
- - - -
**Problems faced**<br/>
- Many Classifiers needed both numbers as input and output. So using Attribute “Location” possess a problem.<br/> **Solution**:<br/> Instead attribute “LocID” is used along with other numeric type attributes.<br/>
- Void or NULL values created problem during Pre-processing.<br/> **Solution**:<br/> dropna() method of Pandas Python which removed null values.<br/>
- - - -

