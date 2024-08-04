# Covid-19 deaths-in-USA-analysis
## Reason for Choosing Project:
I have worked in Health insurance Industry for over 7 years and I would like to use my data Analytics skillset to dive more into one of the topics – COVID to see if I can find anything interesting.
## Type of Data: External
## Information about the data: 
This dataset shows health conditions and contributing causes mentioned in conjunction with deaths involving coronavirus disease 2019 (COVID-19) by age group and jurisdiction of occurrence.
## Link to dataset: [LINK](https://catalog.data.gov/dataset/conditions-contributing-to-deaths-involving-coronavirus-disease-2019-covid-19-by-age-group/resource/8b7317ff-1c37-4098-ad60-84d8e22187c1 "Tooltip Text")
## Data Limitations, Solutions and Cleaning notes:
1. The data for children deaths were suppressed in accordance with the NCHS confidentiality standards, imputed values between 1 and 9 were data was missing
2. Removed  rows having “United states” and ‘Puerto Rico” as states in the “State” Column
3. Changed datatypes for better understanding
## Repository Structure
1. Project Management: Contains the project brief which outlines the objective and expectations of the analysis.
2. Data: Separated into two subfolders Original Data and Prepared Data.
3. Scripts: The Jupyter notebooks containing the coding for the analysis.
4. Analysis: The Visualizations folder contains the visualizations used for developing and explaining insights.
5. Sent to Client: Includes the Tableau Public storyboard as a PDF file.
## Key Questions and answers:
### 1. What are the most common conditions contributing to COVID-19 deaths in different age groups?
From the categorical plots, influenza and pneumonia and cardiovascular diseases are most common conditions to COVID-19 deaths across all age groups, specially older age groups affected. Some conditions like ischemic heart disease, diabadets, and renal failure are also high COVID-19 deaths in older age groups.
### 2. Which group have highest death and which conditions contributing to COVID-19 deaths?
The distribution shows older age groups have higher death counts for almost all conditions. Specially, conditions such as diabetes, ischenic heart disease, and cerebrovascular diseases impact older age groups.
### 3. What factor are most predictive of COVID-19 death rates?
Based on analysis, the most predictive factors are Number of Mentions of conditins, Age Group and specific high-risk conditions such as respiratory and cariovasular diseases. These factors represents strong correlations with COVID-19 death rates.
## Hypothesis 2: 
### If condition like influenza and pneumonia, vascular and unspecified dementia, diabetes, ischemic heart disease, or renal failure, then they will have a higher COVID-19 death rate compared to with other conditions. 
