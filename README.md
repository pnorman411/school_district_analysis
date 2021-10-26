# School District Analysis

## Overview of the Analysis

For this project I am assisting a Chief Data Scientist who is responsible for analysis, reporting, and presentation of school and district level statistics for a district comprising of 15 high schools.  We were tasked with showcasing trends regarding student funding and standardized test scores and presenting them to the school board and superintendent to aid in strategic decision making.  

Upon initial presentation of the results, it was discovered that some of the ninth grade reading and math test scores were altered for one of the high schools.  I was asked to replace the scores with NaN (Not a Number) for the ninth grade for that particular high school and rerun the analysis.  

## Results

### District Summary

The overall district statistics changed minimally:
    
    * The passing math % changed from 75 to 74.8

    * The passing reading % changed from 85.8 to 85.7

    * The overall passing % for both subjects changed from 65.2 to 64.9
    
    
![district_summary](https://user-images.githubusercontent.com/90982811/138800452-b7bda7ae-c585-418a-bd9d-37b6a87ef239.png)

### School Summary

After removing the ninth grade scores, the Thomas High School scores changed as follows:
    
    * The passing math % changed from 93.27 to 93.19

    * The passing reading % changed from 97.31 to 97.02

    * The overall passing % for both subjects changed from 90.95 to 90.63
    
#### School Summary Dataframe    
![school_summary](https://user-images.githubusercontent.com/90982811/138800490-8e8ac568-fb79-4a76-a043-a06fac0df27f.png)

### Thomas High School's Performance

After removing the ninth graders' math and reading scores, Thomas High School's performance relative to the other schools in the district was as follows:
    
    * Thomas High School's ranking in reading changed from first to third place

    * Thomas High School's ranking in math remained in seventh place

    * Thomas High School's overall ranking for the combined passing rate of reading and math remained in second place

### Replacing the Ninth Grade Scores

Replacing the ninth grade scores with NaN had the following affect:

    * No change in the math and reading scores by grade other than changing the 9th grade score to "nan."  

    * The passing percentages for the spending range of $630-$644 per student changed from:
        * 73.48 to 73.46 for math
        * 84.39 to 84.32 for reading
        * 62.86 to 62.78 for the overall passing rate
    
    * The passing percentages for the medium (1000-2000) school size changed from:
        * 93.60 to 93.58 for math
        * 96.79 to 96.73 for reading
        * 90.62 to 90.56 for the overall passing rate
    
    * The passing percentages for Charter schools changed from:
        * 93.62 to 93.61 for math
        * 96.59 to 96.55 for reading
        * 90.43 to 90.39 for the overall passing rate

#### Average Math Score by Grade
![average_math_by_grade](https://user-images.githubusercontent.com/90982811/138800603-56f7dece-af32-41eb-a85b-cb30c6388f44.png)

#### Average Reading Score by Grade
![average_reading_by_grade](https://user-images.githubusercontent.com/90982811/138800619-c0106f65-ad60-4e35-96ee-57684c835320.png)

## Summary of Changes to the School District Analysis

After removal of the ninth grade scores for both math and reading, although minimally, all scores decreased so it could be concluded that the academic dishonesty inflated the scores for Thomas High School for the ninth grade and the school as a whole.  The most notable change to the school district analysis after removing the ninth grade math and reading scores was that the overall percentage of Thomas High School students with passing reading scores ranked the school as third in the district instead of first in the district.

The overall percentage for Thomas High School students for passing both math and reading changed from 90.95 to 90.63 after the removal of the ninth grade test scores.

The overall percentage for district students for passing both math and reading changed from 65.2 to 64.9 after removal of the ninth grade test scores.

When grouping the scores by the spending per student, school size, and by type of school, the grouping by spending per student was most affected.  The overall percentage of passing scores in both math and reading for students in schools within the $630-$644 spending range changed from 62.86 to 62.78.

Although it may appear that the percentages were minimally affected, especially when looking at whole numbers, it is evident that the ninth grade scores for one school were high enough to not only affect Thomas High School's scores but the overall statistics of the school district of 15 high schools.

#### Top Five Schools by Overall Passing Rate
![top_schools_by_passing_rate](https://user-images.githubusercontent.com/90982811/138800709-0c5aba1f-cc39-4e9e-a38d-9004da1aa764.png)



