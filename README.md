# Matplotlib-Challenge The Importance of Plotting
## Background
Data visualization plays a vital role in understanding and presenting patterns and trends in data. Python's Matplotlib library provides a powerful set of tools for creating informative and visually appealing plots from datasets. To demonstrate the capabilities of Matplotlib, we can apply it to a real-world dataset. There are many publicly available datasets on the internet that cover a wide range of topics, including demographics, economics, and weather. Using Matplotlib, we can create various types of plots, such as line plots for displaying trends over time, bar charts for comparing values across categories, and scatter plots for visualizing relationships between variables. These plots can be customized to highlight key insights and present data in a compelling way. By using Matplotlib to visualize data, we can uncover valuable insights and communicate them effectively to others.

As a data analyst in a pharmaceutical company specializing in anti-cancer drugs, you have been given access to the complete data from their recent animal study on squamous cell carcinoma (SCC), a common form of skin cancer. The study involved treating 249 mice with SCC tumor growth using various drug regimens, including Pymaceuticals' drug of interest, Capomulin. Tumor development was observed and measured over a 45-day period to compare the effectiveness of Capomulin with other treatment regimens.

Your task is to generate all necessary tables and figures for the technical report of the study, as well as provide a high-level summary of the results to the executive team. This will involve analyzing the data and creating visualizations, such as line plots and scatter plots, to present the findings clearly and accurately. You will also need to perform statistical analyses to determine the significance of the results and identify any potential limitations or confounding factors.

Ultimately, the goal of the study is to identify the most effective treatment regimen for SCC and provide valuable insights into potential treatments for this common form of skin cancer. As a key member of the team, your role is to ensure that the data is presented in a clear, concise, and informative manner that will help guide future research and drug development efforts.

## Instructions
As a data analyst at Pymaceuticals Inc., you have been tasked with analyzing the data from a recent animal study on squamous cell carcinoma (SCC) to determine the effectiveness of various drug regimens, including Pymaceuticals' drug of interest, Capomulin. Your specific tasks include:

- Checking the data for any mouse ID with duplicate time points and removing any associated data.
- Generating a summary statistics table for the tumor volume of each drug regimen.
- Generating a bar plot and a pie plot to show the number of total mice and the distribution of female or male mice in the study.
- Calculating the final tumor volume, quartiles, IQR, and potential outliers for Capomulin, Ramicane, Infubinol, and Ceftamin.
- Generating a box and whisker plot to visualize the final tumor volume for all four treatment regimens and highlighting any potential outliers.
- Generating a line plot to show tumor volume vs. time point for a mouse treated with Capomulin.
- Generating a scatter plot to show the relationship between mouse weight and average tumor volume for the Capomulin treatment regimen.
- Calculating the correlation coefficient and linear regression model for the relationship between mouse weight and average tumor volume for Capomulin and    plotting the regression line on the scatter plot.

After completing these tasks, you should examine the generated figures and tables to make the following observations or inferences:

- Capomulin and Ramicane were the most effective treatment regimens for reducing tumor volume. Infubinol and Ceftamin were less effective.
- There was a roughly equal distribution of male and female mice in the study.
- The weight of the mice was positively correlated with their average tumor volume for the Capomulin treatment regimen.

