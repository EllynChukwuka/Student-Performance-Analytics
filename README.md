# Student-Performance-Analytics
Technical Report: Student Performance Analytics

1. Outline
This report analyzes student performance data to identify academic trends, monitor student engagement, and recommend data-driven interventions.
 It includes:
Project Background


Story of Data


Data Preprocessing


Exploratory Analysis


Analytical Insights


Dashboards & Visuals


Observations & Recommendations


Final Summary


2. Introduction
Objective of the Project:
1. Identify factors influencing student performance (e.g., demographics, attendance, study habits).
2. Predict academic
3 . Discover performance gaps across gender, socioeconomic status, or schools.
4. Monitor effectiveness of interventions (e.g., tutoring, extracurricular activities).
5 . Classify students by performance level to provide targeted support.

Problem Being Addressed:
 Understanding which variables (gender, parental education, lunch type, test preparation) are significantly affecting student scores across subjects (Math, Reading, Writing).
Key Datasets and Methodologies:
The dataset includes student demographics and scores


Excel Pivot Tables and charts are used for aggregation


Slicers are used for interactive analysis by gender, test preparation, etc.


3. Story of Data
The data contains students, capturing both academic results and background context that could influence those outcomes. 
Each student record includes:
Academic performance: Past exam scores, final exam score
Behavioral factors: Study hours, attendance rate
Socioeconomic/contextual attributes: Parental education level, internet access, extracurricular activity
Outcome: Whether the student passed or failed

Why this matters:
 By examining these features, schools and institutions can uncover patterns in performance, for instance, whether access to the internet or extracurricular participation positively correlates with success. The data invites deep questions: Are students with PhD-educated parents more likely to pass? Does internet access at home give students a performance edge?
This makes it a valuable tool for crafting data-driven interventions to support at-risk students.


Data Source:
 institutional academic data stored in Excel
Data Collection Process:
 Collected via student records during assessments,  school information systems and standardized testing reports
Data Structure:
 Each row represents an individual student with the following fields:
Gender


Race/Ethnicity


Parental Level of Education


Lunch Type


Test Preparation Course


Math Score


Reading Score


Writing Score


Important Features and Their Significance:
Test Preparation Course: Indicator of academic support received


Parental Education: Possible influence on student motivation


Subject scores: Direct performance metrics


Data Limitations or Biases:
Cultural or socioeconomic context not fully represented
Self-reported or standardized test data may have biases
No time-series tracking per student
Missing data or null values 
Imbalanced classes – e.g., more students with passing grades than failing ones.
Time dimension missing 
Outliers – unusually high/low scores may skew analysis.



4. Data Splitting and Preprocessing
Data Cleaning:
Verified completeness: No missing values detected
Removed duplucate data


Ensured consistent formatting of categorical variables (e.g., lunch types)



Handling Missing Values:
Not required – dataset was already clean


Data Transformations:
Calculated Average Score = (Math + Reading + Writing)/3


Grouped parental education levels into broader categories (where needed)


Data Splitting:
Independent Variables: Gender, Race, Lunch, Test Prep, Parental Education


Dependent Variables: Math Score, Reading Score, Writing Score


Industry Context:
 Education – academic performance tracking and student outcome analysis
Stakeholders:
School Administrators


Academic Counselors


Curriculum Planners


Parents & Guardians


Value to the Industry:
 Provides insight into support systems (e.g., test prep), enables data-driven interventions, and supports equitable education strategies.
1. School Administrators-to evaluate student progress and adjust curriculum.
2. Teachers & Academic Counselors – to identify at-risk students for targeted help.
3 . Education Policy Makers – to understand factors influencing performance on a broader scale.
4  . Parents & Guardians – to monitor and support student development.
5.EdTech Companies – to refine tools or platforms supporting academic success.
6.Data Analysts / Researchers – to model and extract insights from educational trends

5. Pre-Analysis
Key Trends Identified:
Students who completed a test preparation course perform better on average across all subjects


Standard lunch students outperform those with free/reduced lunch, suggesting a socioeconomic link


Gender-based variation: Females score higher in Reading and Writing, while males slightly edge out in Math


Potential Correlations:
Parental education correlates with student average scores


Strong linkage between reading and writing scores (literacy cluster)


Initial Insights:
Intervention programs (like test prep) show effectiveness


Socioeconomic support could help narrow performance gaps


6. In-Analysis
Unconfirmed Insights:
Do students from higher parental education backgrounds perform consistently better across all subjects?


Does race/ethnicity significantly impact academic outcomes when controlling for other variables?


Recommendations (Preliminary):
Expand access to test prep programs


Investigate resource support for students on free/reduced lunch


Monitor low-performing segments for early intervention


Excel Tools Used:
PivotTables for gender, parental education, and lunch breakdowns


Bar Charts for score distributions


Slicers to filter by gender, test prep, lunch


Calculated fields (Average Score)


7. Post-Analysis and Insights
Key Findings:
Test Prep Course Effectiveness: Students who completed it scored ~10–15 points higher on average


Lunch Disparity: Students with standard lunch have significantly higher mean scores


Gender Trends: Females lead in Reading/Writing; Math performance is closer


Parental Education: Higher parental education correlates with better student performance


Comparison with Initial Findings:
 Initial assumptions on test prep and socioeconomic indicators were validated with more clarity in dashboard visuals



8. Data Visualizations & Charts
Explanation of Visualizations:
Students' Access to Internet (Area Chart): This bar chart compares internet access between female and male students. It clearly shows that 375 female students have access to the internet, while only 333 male students do. This suggests that female students in this dataset have slightly better access to the internet compared to their male counterparts.


Past Exam Score (Bar Chart): This bar chart illustrates the distribution of past exam scores by gender. It reveals that 29,222 female students and 25,911 male students were included in the past exam score analysis. Without more context (like pass/fail rates for these scores), the primary takeaway is the higher number of female students represented in the past exam score data.


Attendance Rate (Bar Chart): This bar chart displays attendance rates for male and female students. It indicates that the attendance rate for female students is 29,374.05245, while for male students it is 25,926.21473. This suggests that female students, on average, have a higher attendance rate than male students.


Parental Education Level by Internet Access (Pie Chart): This pie chart breaks down parental education levels, likely concerning internet access (though the exact relationship isn't explicitly detailed on the chart itself).


189 students have parents with a Bachelor's degree.
165 students have parents with a High School education.
171 students have parents with a Master's degree.
183 students have parents with a PhD. The key takeaway is the distribution of parental education levels, with Bachelor's and PhD levels being the most represented categories, followed closely by Master's and High School. This provides insight into the educational background of the students' parents in the dataset.
Study Hour (Donut Chart): This donut chart shows the distribution of study hours by gender. It indicates that 9,902 female students and 8,600 male students are represented in this data. Similar to the past exam score, the primary takeaway is the higher number of female students accounted for in the study hour data.
Extracurricular Activities (Bar Chart): This bar chart compares participation in extracurricular activities between genders. It shows that 375 female students participate in extracurricular activities, compared to 333 male students. This suggests that female students are slightly more engaged in extracurricular activities than male students.


Results (Pass/Fail) (Bar Chart): This bar chart presents the results (pass/fail) by gender. It shows that 375 female students passed, and 333 male students passed. This indicates that a higher number of female students achieved a passing result compared to male students.

9. Recommendations and Observations
OBSERVATION
1.Gender & Performance
Female students consistently outperform male students across key metrics: higher exam scores, better attendance, and higher pass rates.

2 Attendance Rate
Females have a higher cumulative attendance rate (29,374 vs. 25,926 for males). This may be contributing to better academic performance.

3.Internet Access:
 More females (375) than males (333) have access to the internet. This likely supports their learning and study efforts outside the classroom.

4 .Study Hours
Female students recorded more study hours in total (9,902 hours vs. 8,600 for males), showing a stronger commitment to academic tasks.

5 Extracurricular Participation
Females are also more engaged in extracurricular activities, which can improve discipline, time management, and cognitive engagement.

6. Past Exam Performance
Female students scored higher in past exams (~29,222 vs. ~25,911), indicating stronger academic background or preparation habits.

7.Parental Education Level
Parental education levels are fairly distributed, but their interaction with internet access could reveal deeper socio-educational patterns.

8. Pass/Fail Rate
A higher number of females passed (375) compared to males (333), reinforcing the trend of stronger female performance.

9. At-Risk Indicators for Males
Male students show multiple risk factors: lower attendance, fewer study hours, less internet access, and lower academic results.


RECOMMENDATION
1. Introduce Academic Support Programs for Male Students
Launch tutoring, mentoring, and motivation programs specifically tailored to male students to close the performance gap.

2. Promote Internet Access Equity
Work with school IT departments or community programs to improve internet access for male students who are lagging behind.

3. Monitor and Improve Attendance
Introduce an alert system for low attendance, focusing especially on male students. Encourage parental involvement through SMS/email updates.

4. Encourage Extracurricular Participation
Provide inclusive activities that might engage more male students, linking participation with academic rewards (e.g., bonus points, certificates).

5. Monitor Female Success
Sustain female performance through advanced opportunities (e.g., leadership programs, scholarships) while ensuring inclusivity.

6 . Implement the At-Risk Student Detection Model
Use a simple predictive model or rule-based system (low attendance + no internet + low past scores) to flag students needing urgent academic intervention.

7. Parental Education Awareness Programs
Engage parents through workshops or newsletters on how their educational background can influence student outcomes and how to support learning at home.

8. Study Habits Development
Offer workshops on time management and study techniques, particularly for male students, to bridge the study hours gap.

9. Data-Driven Tracking
Regularly track attendance, internet access, and extracurricular participation to refine interventions.

Actionable Insights:
Scale Test Prep Programs: Target students in lower-performing demographics


Parental Engagement: Offer programs encouraging parental involvement, especially for those without a college education


Lunch Program Support: Address performance gaps linked to lunch type via academic tutoring or nutrition initiatives


Optimizations or Business Decisions:
Academic institutions should use this model to monitor at-risk groups


Incorporate similar dashboards into school systems for early performance alerts


Unexpected Outcomes:
Some students with low parental education but who completed test prep still performed above average – prep can mitigate education gaps


10. Conclusion
Key Learnings:
Test prep is a strong equalizer in academic performance


Socioeconomic indicators (like lunch) play a major role in achievement


Literacy skills (reading/writing) are highly correlated and essential for overall academic strength


Limitations:
No longitudinal data or repeated tests to track individual progress


Demographic data is categorical and may oversimplify socioeconomic diversity


Future Research:
Introduce time-based metrics to track growth


Include teacher quality, classroom size, or curriculum variables


Consider psychological factors like motivation or learning styles


11. References & Appendices
References:
Student Performance Dataset (Excel Workbook)


Excel Functions: AVERAGE, COUNTIFS, PivotTable tools


Appendices:
Dashboard with slicers


Raw data sheet
Score summary tables


Data prep and formula sheets

<img width="928" alt="students  performance" src="https://github.com/user-attachments/assets/d777a7cd-d9aa-4603-8ed8-90f42e126d37" />










