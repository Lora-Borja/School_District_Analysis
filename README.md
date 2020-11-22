# School_District_Analysis

## Project Overview
This project required the analysis of high school test scores data in order to provide insights and performance trends which are used to establish discussions and strategic decisions at the school board. Using the Pandas library and Jupyter Notebook, I was able to preform tha analysis to come up with a high level snpashot of the school district's key metrics for each school. The following overview of the key metrics were presented in a table format:

* District Summary
![District_Summary_InitialAnalysis]()


* School Summary
![School_Summary_InitialAnalysis]()


*The top 5 performing school based on overall passing rate
![Top5Schools_InitialAnalysis]()


*Bottom 5 performing school based on overall passing rate
![Top5Schools_ReAnalysis]()


* The average math and reading scores received by students in each grade level for each school
![MathScores_ByGrade_InitialAnalysis]()

![ReadingScores_ByGrade_InitialAnalysis]()


* The school performance based on the budget per student
![Spending_Summary_InitialAnalysis]()

![SchoolSize_Summary_InitialAnalysis]()

![SchoolType_Summary_InitialAnalysis]()


* The trends based on school size
![Election_Results_Snapshot](https://github.com/Lora-Borja/Election_Analysis/blob/main/analysis/Election_Results_Snapshot.PNG)

* The trends based on the type of school
![Election_Results_Snapshot](https://github.com/Lora-Borja/Election_Analysis/blob/main/analysis/Election_Results_Snapshot.PNG)

After the initial analysis was complete, the challenge was to perform a re-analysis due to evidence of academic dishonesty within the reading and math scores of Thomas High School's ninth grade students. The process of repeating the analysis required a comparison with the inital results in order to determine whether the changes affected the overall analysis. The observations from the comparison are stated in the re-analysis results below.

## Re-Analysis Results

* How is the district summary affected?
Disregarding the data from Thomas High School's ninth grade students showed no impact in the average math and reading scores in the district summary analysis. A total of 461 ninth grade students was subtracted out of the total student count. The new student count minus Thomas High School's ninth grade students is 38,709 (down from initally 39,170), which was used to calculate the percentage of students passing math, passing reading and overall passing. Below is a snpashot of the district summary after the re-analysis.

![District_Summary_ReAnalysis]()


* How is the school summary affected?
Simillar to the observation in the district summary, there was also no impact in the average math and reading scores in the school summary analysis for Thomas High School. As you can see in the snapshot below, the percent of Thomas High School students passing math is now at 93.185690% versus initially at 93.272171%. This shows that the variance is very minimal (in a decimal place). This is the same observation when you look at the comparison in the percentage of students passing reading, as well as the overall passing percentage versus the initial results.

![School_Summary_ReAnalysis]()


* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
 Again due to very minimal impact of the exclusion of the ninth grade data, Thomas High School is still ranked the 2nd top performing school based on the overall passing rate (refer to the below snpashot of the re-analysis).

![Top5Schools_ReAnalysis]()


* How does the Math and reading scores by grade affected?
The re-analysis shows "nan" in the ninth grade results for Thomas High School for both math and reading scores.

![MathScores_ByGrade_ReAnalysis]()

![ReadingScores_ByGrade_ReAnalysis]()


* How does the Scores by school spending, by school size, and by school type affected?
As previously mentioned, there is only very minimal (in a decimal place) variance shown in the average math and reading scores once the ninth grade data has been excluded from Thomas High School. Therefore, the same very minimal to no impact seen towards the math and reading scores in the below summaries by school spend, by school size, and by school type. 

![Spending_Summary_ReAnalysis]()

![SchoolSize_Summary_ReAnalysis]()

![SchoolType_Summary_ReAnalysis]()


## Overall Summary
After replacing the ninth grade data at Thomas High School with "nans", the process of the re-analysis dd not really show any major changes to the overall results. The exclusion of about 461 ninth grade students' data was not a huge enough factor that impacted the initial analysis results. There were only minimal (in a decimal place) variances seen in the average math and reading scores which is also relfeced the same pattern in the students passing math, reading, and overall percentages. The academic dishonesty reported did warrant a re-analysis to be performed. However, it can be concluded that all the summaries in the analysis are still valid to use for insight and decision making by the school board.
