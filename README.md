# pandas challenge

pyCitySchools Analysis

 Downloaded all the resources and starter code. Import the pandas. Open the files school_data and student_data in read mode . Merge both the dataframes in to a single dataframe. Take a look at the merged dataframe.

District Summary

1. Calculate the total number of unique schools, total number of students, total budget, average math score, average reading score and store each values in a seperate variable.

2. Calculate the students who passed math and reading using the given formulas. Also calculate the percentage of students that passed both math and reading. 

3. Create a new dataframe  "district_summary" to summarize the district's key metrics . Format and display the dataframe.

School Summary

1. Select all the school types based on the school name . Calculate the total student count per school, total school budget per school, per capita spending per school, average test score for both math and reading. 

2. Calculate the students who passed math and reading per school using the given formulas. Also calculate the percentage of students that passed both math and reading per school.

3. Create a new dataframe  "per_school_summary" and concatenate all the calculated dataframe . Format and display the new dataframe.

4. Display the top 5 performing schools using sort_values('% Overall Passing', ascending=False) and also display the lowest performing schools by modifying the same function(ascending=True).

5. Calculate the math and reading scores for 9th,10th,11th and 12th. find the average for the 4 section and create a seperate dataframe to store these values.

6. Create bins based on the school pending(per student budget). cahange the data type of school_spending_df["Per Student Budget"] to float to perform the calculation. Cut the "Per student budget" based on the bins and labels.

7. calculate the average spending based on the spending range and create a dataframe "spending_summary" to dtore this data.

8. Similarly calculate the average math and reading score based on school size. calculate the passing rate in math, reading and overall passing rate based on school size and store in a new dataframe "size_summary"

9. Finally calculate the scores based on the school type and store it in a new dataframe "type_summary".

Conclusion

1. when the budget of the school spending is lower the overall percentage of the students is increased. As the spending increases the overall percentage decreases.

2. when the school size is larger (2000-5000) the overall passing percentage is very low compared to the low and medium school size.

3.  The passing percentage in math, reading and overall percentage is comparitively higher in "Charter" schools. 
 
