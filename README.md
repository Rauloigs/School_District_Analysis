# School_District_Analysis 

## Overview of the school district analysis
We´ve delivered am school district analysis presenting the following metrics with the help of Maria:

1. Top 5 and bottom 5 performing schools, based on the overall passing rate
2. The average math score received by students in each grade level at each school
3. The average reading score received by students in each grade level at each school
4. School performance based on the budget per student
5. School performance based on the school size 
6. School performance based on the type of school

Now the district board has told Maria they perceived academic dishonesty by reviewing the delivered analysis. They would like us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact so they can prove that academic dishonesty appears specifically in 9th graders from the THS. 

**The purpose** is to do all of this above and repeat the analysis we´ve already done to test if there was academic dishonesty in the mentioned group of the THS. 

## Results:
So, lets go through the rersults: 

- The fist change after taking out 9th graders and just leaving 10th to 12th graders in the analysis we can observe a clear change in the *means percentage* of reading, math and overall. the increase was approximately of 30 pp. You can observe the THS performance in the following tables (District Summmary) at the bottom line of each table: 

*First district summary with no taking out 9th graders:*

<img width="990" alt="Old" src="https://user-images.githubusercontent.com/84519822/150655393-43be49cc-91c9-4092-a81c-958b04ca41ba.png">

*Second district: Just 10th - 12 graders:*

<img width="998" alt="New" src="https://user-images.githubusercontent.com/84519822/150655409-3928d41b-0c07-4825-9976-cb2c23a286fa.png">

- Another remarkable change was the top performances DataFrame when just 9th to 12th graders were taken into account. In the following table we can spot that the THS was the second top performer according to **% Overall Passing**

<img width="1000" alt="Top_Performances" src="https://user-images.githubusercontent.com/84519822/150655494-0951e862-6979-4ea2-a499-ee5aa4e3bbfa.png">

- Other results (while completing the rest of the analysis) had no important changes. Probably because the sample we took out ***9th graders from the THS*** is not big enough to alter the whole sample.  

## Summary:
To conclude this analysis we are reviewing four important changes to the school district analysis.

First of all *(1)* there was an important change in the average percentage of students passing math and reading. The difference was perceived uo to 30pp. In consequence of the fisrst remarkable change *(2)* the overall passing percentage also increased dramtically in the same proportion as both subjects individually. Following this chain of changes inside the THS analysis *(3)* the THS climbed places in the different analysis, and *(4)* Analysis like the School Type changed a bit but nost considarbly to attribute to it a different conclusion. 

In my personal opinion I would support the fact that there was academic dishonesty in the THS. 
