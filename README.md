# School_District_Analysis
CBC Module 4


# Chllenge: Replace Thomas High School 9th graders' math and reading scores with NaN
How is the district summary affected?
  - The "Average Math Score" fell from 79.0 to 78.9
  - The "Average Reading Score" remained 81.9
  - The "% Passing Math" fell from 75% to 74%
  - The "% Passing Reading" fell from 86% to 85%
  - The "% Overall Passing" fell from 65% to 64%

How is the school summary affected?
  - The "Average Math Score" fell from 83.41 to 83.35
  - The "Average Reading Score" rose from 83.84 to 83.89
  - The "% Passing Math" fell from 93.3% to 66.9%
  - The "% Passing Reading" fell from 97.3% to 69.6%
  - The "% Overall Passing" fell from 90.9% to 65.0%
  
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
  - Thomas High School went from the 2nd best preforming school in the district (% overall passing) to the 7th.
  
How does replacing the ninth-grade scores affect the following?
  Math and Reading Scores by Grade?
    - Values are replaced with 'nan' for Thomas High School 9th graders.
  
  Scores by School Spending?
    - Thomas High school has a per studend budget of $638, as a result, the the "% Passing Math", "% Passing Reading", and "% Overall Passing" all fell for         the $630-$644 per student budget group
        - % Passing Math fell from 73% to 67%
        - % Passing Reading fell from 84% to 77%
        - % Overall Passing fell from 63% to 56%
      
  Scores by School Size?
    - Thomas High School has 1,635 students, as a result, the passing % for the Medium schools fell.
        - % Passing Math fell from 94% to 88%
        - % Passing Reading fell from 97% to 91%
        - % Overall Passing fell from 91% to 85%
  
  Scores by School Type?
    - Thomas High Scool is a Charter school, as a result, the passing % for charter schools fell.
        - % Passing Math fell from 94% to 90%
        - % Passing Reading fell from 97% to 93%
        - % Overall Passing fell from 90% to 87%
