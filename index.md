
Welcome to my main Data Science webpage. Below you can explore my project work: 

## Featured Project: SES Predictors of Exam Performance

This project analyzes how socioeconomic status influences exam outcomes using a large student dataset.
The analysis includes data cleaning, multiple regression models, an SES index, and interactive visualizations hosted on GitHub Pages.

<p style="margin-top:10px;">
  <a href="https://ahlvinr.github.io/student-ses-exam-performance/" 
     style="background:#159957; padding:10px 18px; color:white; border-radius:6px; text-decoration:none; font-size:16px;">
     View SES Exam Performance Project →
  </a>
</p>

### **Data Sources and Project Ideas**

Dataset 1: Student Success: Factors & Insights
- Source: Kaggle (Anas Sarfraz) <https://www.kaggle.com/datasets/anassarfraz13/student-success-factors-and-insights?resource=download>
- Description: This dataset contains data on 6,590 students and a variety of factors that may affect academic performance, including study habits, attendance, prior scores, sleep hours, parental involvement, internet access, and more.
- Analysis ideas: I could look at which features correlate most strongly with final exam scores (or performance outcome), such as variables like hours studied, attendance rate, sleep hours, parental involvement. I could do so by building visualizations like a boxplot to show exam scores separated by categories of factors, or using something like a heatmap to show correlations between variables.

Dataset 2: Higher Education Predictors of Student Retention 
- Source: Kaggle <https://www.kaggle.com/datasets/thedevastator/higher-education-predictors-of-student-retention>
- Description: This dataset uses student-level data from a higher-education institution, and includes demographic, socioeconomic, and academic history among other factors, with the goal of predicting student retention (dropout vs. continued enrolment)
- Analysis ideas: I could explore which variables (such as prior academic history, parental education, socioeconomic status) correlate most strongly with whether students drop out or stay. I could also use a bar chart to visualize the top 10 features that affect dropping out vs staying in the school. 

Dataset 3: Students Performance Dataset 
- Source: Kaggle (Rabie El Kharoua) <https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset>
- Description: This dataset collects high school students scores in multiple subjects (such as math, reading, writing) along with demographic and socio-educational variables like gender, parental education level, lunch type, test preparation course status, and more. 
- Analysis ideas: One idea I had with this dataset would be to compare their average test scores by variables like gender, parental level of education, or whether the student completed a test preperation course. Then, I could create boxplots of their respective test (math, reading, writing) scores, broken down by these categories. Specifically, with this dataset I’m interested in how access to resources (like lunch type or test prep courses) could be associated with performance differences. 

Dataset 4: Students Health & Academic Performance
- Source: Kaggle <https://www.kaggle.com/datasets/innocentmfa/students-health-and-academic-performance>
- Description: This dataset looks at individual students’ health-related variables and their academic performance outcomes. It includes variables such as age, gender, mobile phone use (and other health/lifestyle variables), and other factors that may be linked to academic achievement. 
- Analysis ideas: With this dataset, I think it would be interesting to explore how health related factors (like reported symptoms, phone use, or sleep) could correlate with academic performance scores. This could be visualized with something like a bar plot comparing grade distributions between different amounts of “healthy” groups, or something more formal like a regression model to predict academic performance from health/lifestyle variables. 

Dataset 5: Student Performance Factors
- Source: Kaggle (Lai Nguyen) <https://www.kaggle.com/datasets/lainguyn123/student-performance-factors>
- Description: This dataset includes over 6,000 students and contains a wide range of variables that influence academic performance. It contains demopraphic characteristics (gender, age, family size), parental background (education, occupation), lifestyle and resource factors (study time, internet access, tutor availability), emotional/mental health variables, and each students final exam scores. 
- Analysis ideas: With this dataset, I would want to look at what are key predictors of academic performance, using something like correlations to see which variables show the strongest relationships with exam score. I could then visualize these correlations using scatterplots, heatmaps, or ranked bar charts. 


### **Where's Schueller? Vizualization Analysis:**

Below is an interactive Plotly visualization from my geolocation analysis, showing Professor Schueller's movement across each season. 

<iframe src="schueller_map.html" width="100%" height="600" style="border:none;">
  <p>Your browser does not support iframes.</p>
</iframe>

For my Above and Beyond component, I added an additional visualization showing Professor Schueller's travel distance by day of the week, separated by season. 

<iframe src="schueller_weekday_seasons.html" width="100%" height="600" style="border:none;">
  <p>Your browser does not support iframes.</p>
</iframe>

This site will eventually host my final data analysis project and interactive visualizations.
