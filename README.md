# Experiment 20: COVID-19 Data Analysis Using Python

## Aim
To study and analyze the COVID-19 dataset using Python programming and libraries such as Pandas, NumPy, and Plotly in order to understand the spread of the pandemic through statistical analysis and graphical visualization. The experiment also aims to learn the use of important Python functions for data cleaning, processing, and visualization.

---

## Theory
COVID-19 data analysis involves collecting, cleaning, processing, and interpreting pandemic-related data to extract meaningful insights. During the COVID-19 outbreak, a huge amount of data was generated daily from different countries and states regarding confirmed cases, recoveries, and deaths. Data analysis helps governments, healthcare organizations, and researchers monitor conditions and make better decisions.

Python is widely used for data analysis because of its simple syntax and powerful libraries such as **Pandas**, **NumPy**, and **Plotly**.

### Libraries and Functions Used

#### Pandas Functions
- **pd.read_csv()** – Used to read the CSV dataset file into a DataFrame.
- **head()** – Displays the first few rows of the dataset.
- **tail()** – Displays the last few rows of the dataset.
- **info()** – Gives column names, data types, and non-null values.
- **describe()** – Provides statistical summary of numerical data.
- **drop()** – Removes unnecessary columns such as serial number or last update.
- **rename()** – Changes column names if required.
- **groupby()** – Groups data according to country or state.
- **sum()** – Adds values such as confirmed or recovered cases.
- **sort_values()** – Sorts data in ascending or descending order.
- **reset_index()** – Resets index after grouping.
- **max()** – Finds highest number of cases.
- **nunique()** – Counts number of unique countries or states.
- **astype()** – Converts data type into integer or string.
- **to_datetime()** – Converts date column into datetime format.

#### NumPy Functions
- **np.mean()** – Finds average values.
- **np.max()** – Finds maximum value.
- **np.min()** – Finds minimum value.

#### Plotly Functions
- **px.choropleth()** – Creates world map visualization for confirmed or recovered cases.
- **px.bar()** – Creates bar graph for top affected countries.
- **show()** – Displays the graph.

### Important Calculation
One of the most useful calculations in this experiment is:

**Active Cases = Confirmed Cases - Recovered Cases - Death Cases**

This shows the number of currently infected patients.

### Applications
- Identifying most affected countries and states.
- Monitoring recovery rate and death rate.
- Understanding pandemic trends visually.
- Supporting healthcare planning and government decisions.

---

## Conclusion
Thus, the COVID-19 dataset was successfully analyzed using Python programming. Various functions of Pandas, NumPy, and Plotly were used for reading, cleaning, grouping, sorting, calculating, and visualizing the data. Important values such as confirmed cases, recovered cases, deaths, and active cases were obtained. Country-wise and India state-wise comparisons were performed successfully. Hence, the experiment proves that Python is a powerful tool for real-world data analysis and visualization.



