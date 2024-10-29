
# District Performance Overview

1. Calculated the total number of unique schools, total number of students, total budget, average math score, and average reading score and stored all values separately.

2. Calculate the students who passed math and reading using the formulas and calculate the percentage of students who passed both math and reading. 

3. Create a new dataframe  "district_summary" to summarize the district's key metrics. 

# School Performance Overview

1. Select all the school types based on the school name. Calculate the total student count per school, total school budget per school, per capita spending per school, and average test score for both math and reading. 

2. Calculate the students who passed math and reading and the percentage of students who passed both math and reading in each school.

3. Create a new data frame  "per_school_summary" to store the calculations.

4. Display the top 5 performing schools and the lowest performing schools.

5. Calculate the math and reading scores for 9th,10th,11th and 12th. find the average for the 4 grades and create a separate data frame to store these values.

6. Create bins based on the school's pending(per student budget). change the data type of school_spending_df["Per Student Budget"] to float to perform the calculation. Cut the "Per student budget" based on the bins and labels.

7. calculate the average spending based on the spending range and create a data frame "spending_summary" to store this data.

8. Similarly calculate the average math and reading score based on school size. calculate the passing rate in math, reading, and overall passing rate based on school size and store it in a new data frame "size_summary"

9. Finally calculate the scores based on the school type and store them in a new data frame "type_summary".

# Key Insights on School Spending, Size, and Performance

1. when the budget of the school spending is lower the overall percentage of the students is increased. As the spending increases the overall percentage decreases.

2. when the school size is larger (2000-5000) the overall passing percentage is very low compared to the low and medium school size.

3.  The passing percentage in math, reading, and overall percentage is comparatively higher in "Charter" schools. 
 
