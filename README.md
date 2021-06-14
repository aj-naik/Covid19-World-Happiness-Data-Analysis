# Covid19-World-Happiness-Data-Analysis
Analysis of Covid 19 in Early 2020 and its effect on happiness, infection rate, etc of general populace in countries. One of my first intro to data science and analysis projects. Followed the tutorial on Coursera for this, made some modifications of own and and gained more knowledge and insight on dealing with dataframes, joining two datasets, visualistion aspect of data analysis and drawing statistical and visual inferences from the data.

# Note:
The Covid dataset is very old. It covers early 2020. For updated data packages like 'Covid' and 'Covid19py' are great and can fetch latest covid data.

# Project Details:
The aim of the project is to:
- Plot and visualise covid cases in different countries over each day.
- Deriving the maximum infection rate and comparing infection rates across countries.
- Using maximum infection rate to generate plots comparing and analysing factors strongly affecting max infection rate like:
1. GDP
2. Social Support
3. Life Expectency
4. Freedom to make choices.
- Creating log of Maximum infection rate and plotting it with above factors to get clearer insight.

# Preprocessing & Feature Engineering:
- Created a 'Maxium Infection Rate' column in covid data set by calculating the first derivative of summation of number of covid cases in a country
- Joining 'World-Happiness-Report' dataset with 'Covid19_Confirmed_dataset' for analysis.

# Inference:
While the dataset is not exhaustive for a more deatiled conclusion we still can get a rough inference. We find that:
- Countries with better Social Support, Higher life expectency and more freedom to make life choices initally had a low maximum infection rate than countries which do not have a better score on these factors.
- This can be attributed to fact that countries with better GDP tend to have a score better on Social Support, Higher life expectency and more freedom to make life choices factors which contribute in more prosperous population (overall and monetarily) with easy and better access to medical healthcare and a good and strong enough social community which is essential to decrease the rate of infection. Also the people of these countries mostly have money to wait out the restrictions at home over short term thereby reducing the chance of infecting more people thereby driving down the infection rate
