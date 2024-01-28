# Pandas-Challenge
I have completed "Module 4: Pandas-Challenge" using the concepts and knowledge from lectures and activities in UPENN Data Science Bootcamp. For this project, I created a new repository named "Pandas-Challenge." Inside this repository, you can find a Jupyter Notebook Python scripting file named "PyCitySchools_Kiet.ipynb" that runs the analysis, along with a sub-folder named Resources which contains the Data CSV files.

Although I worked on this project alone, I plan to discuss it with our study group. Additionally, I sought assistance from Google ChatGPT to help me find errors in my code and make it more descriptive and easier to understand.

For this task, we utilized Jupyter Notebook to analyze the school data of a school district for exploring the trends in school performance. The tables enabled us to compare key educational metrics among different schools, which helped to highlight variations in performance, budget allocation, and school type.
  
  SUMMARY ANALYSIS: 

- This school district has a total of 15 schools, which can be divided into two types: Charter (8) and District (7). The number of students in each school varies, with some having as few as 427 students and some having as many as 4976 students. All district schools have more than 2000 students, while most of the charter schools are small or medium-sized, except Wilson High School, which has 2204 students.
- Charter schools generally have higher average math and reading scores than district schools. Additionally, the percentage of students passing math, reading, and both subjects overall tends to be higher in charter schools.
<img width="1470" alt="Screenshot 2024-01-27 at 7 13 45 PM" src="https://github.com/hatkiet/Pandas-Challenge/assets/154276115/6094d2a8-79b5-4ceb-8ffd-3f5addd5968b">

- Upon examining the “Math/Reading Scores by grade” data table, it appears that there is a consistent trend of average math/reading scores across grade levels. However, some schools show improvements in specific grades, while others experience spikes or slight declines. Although there may be slight variations, the scores generally remain close to each other.

Data of Math Scores by Grade

<img width="645" alt="Screenshot 2024-01-27 at 7 16 21 PM" src="https://github.com/hatkiet/Pandas-Challenge/assets/154276115/17c6ec40-9337-4772-86fd-3ba58969f514">

Data of Reading Scores by Grade

<img width="644" alt="Screenshot 2024-01-27 at 7 17 21 PM" src="https://github.com/hatkiet/Pandas-Challenge/assets/154276115/547b4689-470f-4fea-abb9-f781c9072a5b">

- The “Scores by School Spending” summary data table provides valuable insights into the relationship between academic outcomes and spending per student. It indicates that schools with lower spending per student, i.e., less than $585 and between $585-630, tend to have higher average scores and greater percentages of students passing both math and reading. The data shows that schools with lower budgets tend to achieve better academic results, indicating an inverse correlation between per-student spending and academic performance.

<img width="1251" alt="Screenshot 2024-01-27 at 7 19 06 PM" src="https://github.com/hatkiet/Pandas-Challenge/assets/154276115/1649a011-5327-474d-b5fb-b4e0cb9ea862">

- Similarly, the “Scores by School Size” summary data table highlights the potential advantages of smaller school sizes in fostering higher average scores and passing rates. It shows that small and medium-sized schools, having less than 1000 and between 1000-2000 students respectively, exhibit higher average scores and passing rates than larger schools. On the other hand, larger schools, with student populations ranging from 2000-5000, show lower average scores and lower percentages of students passing both math and reading.
<img width="1136" alt="Screenshot 2024-01-27 at 7 21 23 PM" src="https://github.com/hatkiet/Pandas-Challenge/assets/154276115/c31844a9-c751-4bc3-a39e-b8668f90edd6">


DRAW 2 CONCLUSIONS OR COMPARISIONS FROM THE CALCULATION

[1] Charter schools dominated the top five positions in terms of passing rates for both math and reading, while District schools dominated the bottom five positions in the same categories. It is worth mentioning that the passing rate of the top five schools, which is around 91%, is almost double that of the bottom five schools, which have a passing rate of approximately 53%.

Highest performing schools
<img width="1476" alt="Screenshot 2024-01-27 at 7 23 35 PM" src="https://github.com/hatkiet/Pandas-Challenge/assets/154276115/c9f2cd9d-d751-4f2f-a481-5f55c5c91fb6">

Bottom performing schools
<img width="1469" alt="Screenshot 2024-01-27 at 7 24 02 PM" src="https://github.com/hatkiet/Pandas-Challenge/assets/154276115/51eb6def-12cd-4193-aff7-2f6f34a37262">

[2] Interestingly, it was observed that larger school sizes and higher school spending did not result in better academic outcomes. Instead, smaller schools with a student population of less than 2000 and a lower spending range (less than $585 and $585-630) yielded much better academic outcomes.










  
