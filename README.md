
# Module 3 Challenge: School_District_Analysis

## Overview of The Analysis
There is an evidence of academic dishonesty in the data reported for one of the schools. To uphold the state testing standards, school board has requested that the grades for a specific class to be removed from any analysis.

### Purpose
Goal of this project is to redo the School distric analysis after replacing the Thomas High School ninth grade math and reading scores wiht NaNs.
## Results
* **How is the district summary affected?**
Out of 39,170 students in the district, only 461 student had their data removed from the analysis. This is statistically insignificant and as it can be seen below, the stats changed by less than 1% compared to the original analysis.

![Updated_district_Analysis](/Resources/updated_district_summary.png)

* **How is the school summary affected?**
In the school summary, none of the schools are affected except Thomas High Scholl.
![Updated_school_Analysis](/Resources/updated_school_summary.png)

* **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
Thomas High School,THS, has a total of 1635 students. Since 461 data points are missing, the THS stats are much lower than reality since all the calculation assumed all the data is available. So compared to other schools, THS is underrated.
![THS_summary_including_all_students](/Resources/THS_summary_total_students.png)

Once the correct number of students is used to calculate the stats, THS moves up to the 2nd place in high performing schools. 
![THS_summary_including_correct_students](/Resources/THS_summary_correct_students.png)


* **How does replacing the ninth-grade scores affect the following:**
    * **Math and reading scores by grade**
    None of the school grades are affected. The only difference is the THS 9th grade that has changed to nan.
    ![Updated_school_grade](/Resources/Updated_school_grade.png)
    * **Scores by school spending**
    The changes in the data is statistically insignificant, since only 461 out of 39170 data points are removed from analysis.
    ![Updated_school_spendings](/Resources/Updated_school_spendings.png)

    * **Scores by school size**
    This table is not affected at all. 
     ![Updated_school_size](/Resources/Updated_school_size.png)
    * **Scores by school type**
    This table is not affected at all. 
    ![Updated_school_type](/Resources/Updated_school_type.png)

## School_District_Analysis Summary
After updating the analysis, THS math/reading and overall passing score went up much higher. 
THS is now 2nd to best school. 
All other metrics remain either the same or the changes are statistically insignificant.
