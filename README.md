# Data-and-plotting-using-R

Assignment 1
You are given 4 datasets of different forms of child malnutrition (Overweight, Underweight, 
Stunted and Wasted) and a Data Country Parameters dataset.
Note-
• Values may differ according to assumptions taken by you. Make sure to mention your 
reasons behind taking each assumption.
• Make sure to add plot titles and texts wherever required.
1. Perform the following steps to get the required table (15 points)
a) Join all 4 forms of malnutrition tables using joins on Country and Year in R
b) For each country, take the mean value for all the forms of malnutrition
c) Import the Data country parameters dataset and using joins, add WHO Region and 
Income group from the sheet 8 of the dataset.
Your starting 15 rows of the result should look like:
2. Using the datasets provided, plot the graphs as shown below with titles and labels. (15 
points)
3. Using the datasets, fill in the correlation values between different forms of malnutrition
in the table. (15 points)
Overweight Stunted Underweight Wasted
Overweight
Stunted
Underweight
Wasted
What does positive, negative and zero values of correlation between 2 variables imply?
4. Using the datasets, plot the following Violin and Box plots. (20 points)
Write 2 or more points about the inferences you get from these plots.
The directory of farmers market across the US is given in the file named “fm.csv”.
Answer the following questions from the dataset. 
5. Write a code to compute the number of farmers markets by state and arrange them in 
descending order of number of farmers market. (10)
6. Write a code to compute the number of farmers market by cities in Massachusetts and 
display top five cities. (10)
7. Generate the following table using pivot function. First column should contain the states. 
Second column should have Payment System. For Payment System consider the columns, 
“Credit”, “WIC”, “WICcash”, and “SNAP” from the original farmers market data. Third 
column should have the number of farmers market offering the payment services. (15)
States Payment System #Farmers Market
New York Credit 10
New York WIC 20
New York WICcash 30
New York SNAP 40
The above table is only for explaining the problem. Students need to generate
the entire long form table.
Submission Format
1. Submit .RMD file via Canvas
2. The file should be named as follows, firstname_homework1.R
3. The code should follow tidyverse style guide
(https://style.tidyverse.org/index.html)
4. The tidyverse style guide has style standards for naming obj
