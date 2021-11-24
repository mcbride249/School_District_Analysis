**#School_District_Analysis**

**##Project Overview**

The chief data schientist of a school district has tasked us with getting key metrics regarding standardized testing data including student funding and student standardized test scores.

**Goals:**

Calculate the total number of students

Calculate the total number of schools

Calculate the total budget

Calculate the average math score

Calculate the average reading score

Calculate the percentage of students who passed math

Calculate the percentage of students who passed reading

Calculate the overall passing percentage

**##Resources**

Data Source: clean_students_complete.csv, students_complete.csv, schools_complete.csv -Software: Python 3.7.10, Anaconda Navigator, Visual Studio Code, 1.38.1

**##Summary**

Total number of students: 15

Total number of schools: 39,170

Total budget: $24,649,428.00

Average math score: 79%

Average reading score: 81.9%

Percentage of students who passed math: 75%

Percentage of students who passed reading: 86%

Overall passing percentage:65%


**##Module 4 Challenge - Written Analysis**

**##Challenge Overview**

The purpose of this analysis was to use pandas to provide a breakdown of key metrics for the school district as well as individual schools and grades particularly as they relate to school performance. The key metrics that were examined using pandas were the top and bottom schools based on the overall passing rate, the average math and readings scores by grade level for each school,  and school performance based on budget per student, school size, and type of school. Using pandas in this analysis, allowed us to determine the above metrics for a large data set that elsewise would have been too large to produce meaningful results in a timely manner. The production of the above metrics would allow us to return to the school district board and provide them with varying factors and reasons that ultimately led to a higher passing rate. Deliverable 1 of this exercise in particularly saw us replace ninth grade math and reading scores with a null value. Deliverable 2 had us run the through the  school district analysis again, this time without the ninth-grade data to determine how the key metrics would be affected by their absence. 

**##Results**

**•	How is the district summary affected?**

    o	The district summary was not heavily impacted by the removal of the ninth-grade scores. 
    
    o	The average math score decreased from 79.0% to 78.9%.
    
    o	The average reading score remained the same at 81.9%.
    
    o	The passing math percentage decreased from 75% to  74.8%.
    
    o	The passing reading percentage decreased to 86% to 85.7%.
    
    o	The overall passing percentage decreased 65% to 64.9%.
    
    o	The results show that at the district level, the removal of the grade 9 student scores did cause an overall decrease in all categories but did not have a statistically         significant impact. This shows that the ninth grade students were making appositive contribution in terms of their scores being relatively high (or the same as) the             remainder of the grades.  
    
    o	Image 1 (Original District Data) 
    
    o	Image 2 (New District Data) 

**•	How is the school summary affected?**

    o	Similar to the district summary, the removal of the ninth-grade scores did not have a major impact at the school level. However, not all categories dropped; the reading        score actually increased demonstrating that the ninth-grade students may have trouble in this area. This could potentially be expected based on the fact that those of a          younger age may have a harder time with their reading skills, however this is only a postulation, and is not corroborated by the fact that that all other categories              experienced a decrease. 
    
  o	The average math score dropped from 83.41% to 83.35%.

  o	The average reading score rose from 83.84% to 83.89%.

  o	Percent of students passing math dropped from 93.27% to 93.18%. 

  o	Percent of students passing reading dropped from 97.30% to 97.01%.

  o	Percent of overall passing dropped from 90.94% to 90.63%.

  o	Image 3 – Original School Summary Data

  o	Image 4 – New School Summary Data

**•	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

  o	Replacing the ninth grade scores did not actually impact Thomas High School’s ranking. It remained as the second best school in the district.
  
  o	Image 5 (Original Top 5 Schools)
  
  o	Image 6 (New Top 5 Schools)

**•	How does replacing the ninth-grade scores affect the following:**

    o **Math and reading scores by grade**.
  
        o The math and reading scores were removed in the new analysis and replaced with NaN.
  
        o Image 7 (Old Math & Reading Scores)
  
        o Image 8 (New Math & Reading Scores)

  o **Scores by school spending**
        
        o School spending per student remained the same (this spending was not affected by the removal of the ninth graders’ grades), however thee overall passing percentage did           drop from 90.94% to 90.63%
        
        o	Image 3
        
        o	Image 4 

  o **Scores by school size**

        o There was not overall change to the overall passing rate or math and reading scores or percentages beyond a decimal.
       
        o The size of Thomas High school did not change and was not affected by the alteration of the ninth-grade students’ grades. 
        
        o Image 9 (Old School Size Summary)
        
        o Image 10 (New School Size Summary)

  o **Scores by school type.**

        o There was no change to the scores or averages based on the type; alls cores remained the same.

        o Image 11 (Old School Type)

        o Image 12 (New School Type)
        
**•Summary**

    o In summary, the removal of the ninth-grade data did have a number of minor affects on the overall data performance. The average math score decreased from 79.0% to 78.9%,         the average reading score remained the same at 81.9%, the passing math percentage decreased from 75% to  74.8%, the passing reading percentage decreased to 86% to 85.7%,         and the overall passing percentage decreased 65% to 64.9. While these changes may be small and not statistically significant, it does reveal how the ninth- grade students       impacted the overall performance of the school.o
