**#School_District_Analysis**

**Overview** 

Maria, the chief data scientist for a school district is tasked with preparing all stardandized tests' data for analysis, reporting and presentation to provide insights about performance trends and patterns. These insights are used to inform discussions and strategic decisions at the school and district level. We have been helping Maria analyze data  on student funding and standardized math and reading test scores to show trends in school performance while adhering to FERPA. This analysis will help the school board make decisions regarding budgets and priorities.

After the initial analysis was complete, the school board notified that the `students_complete.csv` file showed evidence of academic dishonesty, specifically, reading and math grades for Thomas High School ninth grades appeared to have been altered. They want to replace  the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, then repeat the analysis to describe how these changes affected the overall analysis.

**##Results**
- How is the district summary affected. After changing the Thomas High School's math and reading scores we can see a slight decrease in the following metrics:

(Before changes)

![image](https://user-images.githubusercontent.com/104289098/171316685-188c262c-f9fc-4e7a-9401-0569490b87c7.png) (Fig. 1)

(After changes)

![image](https://user-images.githubusercontent.com/104289098/171316929-fc2f12fd-caa1-47cd-a8f5-bfe5173b2ee1.png) (Fig. 2)


 *Average Math Score: from 79 to 78.9
 
 *% Passing Math: from 75% to 74.8%
 
 *% Passing Reading: from 86% to 85.7%

 *% Overall Passing: 65% to 64.9%
 
 *The only metric that stayed the same was *Average Reading Score* score with 81.9


- How is the school summary affected.
When we look at the school summary we can see that only the metrics for Thomas High School changed as the data for each of the other schools was not altered.

- How does replacing the ninth grader's math and reading scores affect Thomas High School's performance relative to the other schoools?
 Even though some of the scores for Thomas High School decreased, it did not change its position relative to the other schools, maintaining its position as the second top school.

- How does replacing the ninth-grade scores affect the following: 
- 
  - Math and reading scores by grade. It only affects the scores for Thomas High School which now display *nan* for the 9th grade, the remainder of the scores are the      same.
  
  - Scores by school spending.There are no changes on the scores based on school spending.
  
  - Scores by school size. There are no changes on the scores based on school size.
  
  - Scores by school type. There are no changes on the scores based school type.
  

**##Summary**
The following summarizes some of the  changes in the uploaded school district analysis after math and reading scores for the ninth grade at THS have been replaced with NaNs.

1. Math scores by grade. Math scores stayed the same for 10th, 11th and 12th grades at THS.

2. Reading scores by grade. Reading scores stayed the same for 10th, 11th and 12th grades at THS.

3. District summary as mentioned previously.

4. Scores for Thomas High School changed as following:

   - Average Math Score: from 83.4 to 83.3
   - Average Reading Score: from 84.84 to 83.89
   - % Passing Math: from 93.27% to 93.18%
   - % Passing Reading: from 97.30% to 97.01%
   - % Overall Passing: from 90.94 to 90.63%

![image](https://user-images.githubusercontent.com/104289098/171767820-00307f5c-6f18-41ea-9543-ae2243ca5ce5.png)

![image](https://user-images.githubusercontent.com/104289098/171767939-d0ea233b-ab34-46a2-ae7e-74197900cea4.png) (Before replacement and adjustment)

![image](https://user-images.githubusercontent.com/104289098/171767882-eab710e5-d66c-4b63-85c7-1a68f1bc9fff.png) (After replacement and adjustment)


It is worth noting that without adjusting the scores for THS after the math and reading scores were replaced with *NaNs*, % Passing Math, % Passing Reading and % Overall Passing would have dropped significantly and THS would not have been in the top five schools.

(After replacement with NaNs before adjustment)
![image](https://user-images.githubusercontent.com/104289098/171768188-907f7546-4787-4370-a1cd-baa4955a1c01.png)

![image](https://user-images.githubusercontent.com/104289098/171768220-d9f63add-dce9-4e70-a627-cd85d3d5e1a8.png)


