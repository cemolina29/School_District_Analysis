# School_District_Analysis

## Overview

The main analysis focuses on the performance of math and reading scores that were calculated in different ways in preparation for a board meeting. The school district asked for an analysis for each school campus and by the district level.  However, after the school board reviewed the information, it was determined that Thomas High School's 9th grade class was suspect of academic dishonesty; specifically, reading and math grades. Now, the school board asked to remove the data for that school while keeping the rest of the data intact to describe how these changes affected the overall analysis.

### Results

- How is the district summary affected?

As shown in the below images the change was not significant.

Oginal Analysis:

![District summary Original](https://user-images.githubusercontent.com/108438270/188521052-ffc58724-5717-4dbe-a734-d43ac7a4065b.png)

Modified Analysis:

![District summary modified](https://user-images.githubusercontent.com/108438270/188521058-4d47027f-22d2-4f2e-9113-d8b98815ec83.png)

- How is the school summary affected?

In the original analysis, Thomas High School started with a 91% overall passing rate. After calculating the total number of 10th - 12th grade students as the new denominator, the rest of the testing data was adjusted accordingly.
Removing the 9th grade students from the data set had a big impact by dropping from 91% to 65% for the overall passing rate.

Oginal Analysis:

<img width="607" alt="School Summary Original" src="https://user-images.githubusercontent.com/108438270/188522143-f4b2e315-4810-4168-a67f-838f30cdea58.png">

Modified Analysis:

![School Summary Modified](https://user-images.githubusercontent.com/108438270/188522148-68c695e9-b071-4f47-a072-479615ba9876.png)

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

In the original analysis, Thomas High School ranked 2nd in the district raising red flags with the school board. After adjusting the 9th grade data, Thomas High School ranked in the exact middle of 15 campuses at 8th from the bottom.


- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade

    In the original analysis, Thomas High School had the average for the 9th grade tests. Now the scores have been replaced with null values (NaN).
    
    <img width="199" alt="NaN Math" src="https://user-images.githubusercontent.com/108438270/188524439-2cda8b3a-4cb8-40dd-b915-63ad95536066.png">


    <img width="202" alt="NaN Reading" src="https://user-images.githubusercontent.com/108438270/188524453-e9aa9a3b-5843-462d-9989-f678d29c81dc.png">


  - Scores by school spending
   
    Thomas High School falls in the $630-$644/student spending range. 
      
   - Scores by school size
 
      Thomas High School is defined as a medium sized school. There was very little impact by campus size due to changing the 9th grade scores.
      
      
   - Scores by school type
    
      There was very little impact by school type by changing the 9th grade scores.
      

Oginal Analysis:

<img width="535" alt="Type Original" src="https://user-images.githubusercontent.com/108438270/188525741-a2d493a1-1cc4-4950-a4c9-e1cec00327ae.png">

Modified Analysis:

<img width="446" alt="Type modified" src="https://user-images.githubusercontent.com/108438270/188525750-f10a694d-f664-43e7-a4b2-2fc37793ad69.png">


### Summary

The major changes will be seen at the lower views of the disaggregated data with minor impact to the larger data views.

1. The overall passing rate for Thomas High School changed significantly from 91% to 65%.

2. Data will now show as "NaN" in reports for the 9th grade students at Thomas High School

3. The Overall passing rate for math and reading averages and passing percentages all saw shifts.

4. Thomas High School's place in the list dropped from 2nd to 8th in the district of 15 campuses.

