# Module-5-Challange
MY COPY is the hw assisgnment. 
Project Title: Exploratory Data Analysis (EDA) of Cancer Treatment Study

Background:
In this assignment, I applied my data visualization and analysis skills to a real-world scenario involving cancer treatment research. As a senior data analyst at Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications, I was entrusted with the task of analyzing data from an animal study. The study aimed to assess the effectiveness of various drug regimens in treating squamous cell carcinoma (SCC), a prevalent form of skin cancer.

Project Goals:
The project had several objectives:

Data Preparation: I started by preparing the data, merging two data sources (mouse_metadata and study_results) into a single DataFrame. I ensured data quality by identifying and handling duplicate mouse IDs with duplicate time points, resulting in a clean dataset.

Generate Summary Statistics: I calculated essential summary statistics for each drug regimen, including mean, median, variance, standard deviation, and standard error of the mean (SEM) of tumor volume. These statistics helped provide insights into the treatment outcomes.

Create Visualizations: I created impactful visualizations to convey key findings:

Bar Charts: I generated bar charts to illustrate the total number of observations (Mouse ID/Timepoints) for each drug regimen throughout the study. I used both Pandas and Matplotlib for this purpose.

Pie Charts: I created pie charts to visualize the distribution of female and male mice in the study. These charts provided insights into the gender balance of the subjects.

Quartiles, Outliers, and Box Plot: I calculated the final tumor volume of mice for the most promising treatment regimens (Capomulin, Ramicane, Infubinol, and Ceftamin). I determined quartiles and the interquartile range (IQR) to identify potential outliers. I also created a box plot to visually represent the distribution of final tumor volumes for each treatment regimen.

Line Plot and Scatter Plot: I selected a single mouse treated with Capomulin and created a line plot to visualize tumor volume changes over time. Additionally, I generated a scatter plot to explore the relationship between mouse weight and the average observed tumor volume for the entire Capomulin treatment regimen.

Correlation and Regression Analysis: To understand the correlation between mouse weight and tumor volume, I calculated the correlation coefficient and conducted a linear regression analysis. I plotted the regression model on the scatter plot, providing valuable insights into the relationship between these variables.

Project Outcome:
This assignment allowed me to showcase my expertise in data analysis and visualization using Python and Matplotlib. It demonstrated my ability to prepare and clean data, generate descriptive statistics, and create meaningful visualizations. Additionally, I successfully interpreted the results of statistical analyses and communicated key findings through visual representations.
