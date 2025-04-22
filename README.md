# Emergency Room Visit Report

## Project Overview
Maplewood Community Hospital, established in 1978, is regional medical facility serving the town of Maplewood and its surrounding rural communities.

While founded on and driven by community-first values, in recent years sudden regional population growth has led Maplewood Community Hospital to struggle in keeping up with rising patient demands. This project analyzes the hospital's Emergency Room patient data, with the goal of improving the overall ER patient experience.

Insights and recommendations are provided for the following key areas:
- **Patient Demographics:** Identification of notable groups among genders, age groups, races/ethnicities, and department referrals
- **Patient Satisfaction Scores:** Evaluation of score patterns, both overall and among various patient demographics
- **Patient Wait Times:** Assessment of wait times and their potential impact on satisfaction scores


## Data Structure Overview
Maplewood Community Hospital's Emergency Room patient data consists of one table as seen below. The data extracted for this project spans from April 2019 to October 2020, with a total row count of 9,216 records.  

<img src=https://github.com/user-attachments/assets/93c4ab3c-1812-426e-b808-a50fb159008c width="250">


## Executive Summary
Maplewood Community Hospital's analysis of 9k emergency room patient records from 2019-2020 shows an average patient satisfaction score of 4.99 out of 10. It should be noted that only 27% of patients left a satisfaction score, so greater effort should be placed toward ensuring more patients are leaving scores and other meaningful feedback. Emergency room patients are waiting an average of 35.3 minutes before being seen. The average wait time has been decreasing over the past several months, with an **all time low of 34.1 minutes most recently in October 2020. 

The largest patient demographics are 0-18 Years (22.9% of all patients) and 19-35 Years (21.5%) among age groups and White **(27.9%) and African American (21.1%) among racial groups. Across patient demographics the following groups have lower than average satisfaction scores: gender nonconforming patients (3.2 out of 10), patients 66 years old or older (4.7), patients with two or more races (4.8), and patients referred to the Renal department (4.6). Overall wait time and satisfaction concerns can be addressed through additional staffing, reallocating staff to shifts needing more personnel, and additional training to better accommodate unsatisfied demographics, as well as the greater patient population overall.


## Insights Deep Dive
### Patient Satisfaction Scores
- 72% of all patients in the dataset did not leave a satisfaction score.
- The overall average score is fairly low at 4.99 out of 10.
- The highest monthly average score was in March 2020 (5.33). The lowest monthly average was in April 2020 (4.63). 
- The largest increase in average satisfaction score is from February to March 2020 at 0.61 points. This is immediately followed by the largest drop in satisfaction score at 0.7 points, between March and April 2020.
- The dataset ends on an upward trend, with October 2020 having an average score of 5.31, which is up 0.4 points from the previous month.
to do: add more detailed graph, also remove vertical 0 line on score distribution
<img src=https://github.com/user-attachments/assets/193ac502-8a68-4c9a-b7c3-3663496605e2 height="100">


### Patient Wait Times
- The days and times with the longest average wait times (39 min or more) are Mon 11 PM (40.69), Wed 3 AM (39.74), Fri 10 PM (39.34), Sun 7 AM (39.18), and Wed 8 AM (39.02).
- The days and times with the shortest wait times (under 31 min) are Wed 1 AM (29.65), Sat 9 PM (30.09), and Sat 4 PM (30.52).
- Wednesday morning has two time slots with the longest average wait times as well as the time slot with the overall shortest average wait time. Saturday evening has two time slots with the shortest average wait times.
- The overall average wait time is 35.3 minutes. Monthly average wait times have been on a steady decline since May 2020, with a total decrease of 1.7 minutes through October 2020.
- The longest average wait time over a specific month was in February 2020 (36.7 mins). The shortest wait time was in October 2020 (34.1 mins).
- Average satisfaction scores more often increase when wait times increase, instead of when wait times decrease. This is true for 12 of 18 months in the dataset, though the variation in average wait time between months is very small, with the highest change being a 2.1 minute decrease between August and September 2019.
to do: add more detailed graph
<img src=https://github.com/user-attachments/assets/215f2ffd-3e54-4bf2-a484-2e1cb845505b height="100">


### Patient Gender
- Male and female patient counts are roughly equal (4705 male and 4487 female). There are a very small amount of patients that are gender nonconforming (24 total).
- Gender nonconforming patients have a much lower average satisfaction score at 3.2, compared to 5.03 for male and 4.96 for female patients.

### Patient Age Groups
- The largest age group is 0-18 Years at 2110 patients (22.9%). The second largest is 19-35 Years at 1985 patients (21.5%).
- The 66+ Year age group has the lowest overall average satisfaction score at 4.72, with a large amount of 1 scores. Average wait times for this group have been trending upward since July 2020 with a total increase of 4.5 minutes.
- The 0-18 Year age group, the largest patient age group, has the second lowest overall average at 4.97.
- The 36-50 Year age group has the highest overall average at 5.19 with a large number of 9 and 10 scores.

### Patient Race/Ethnicity
- The largest race/ethnicity is White at 2571 patients (27.9%). The second largest is African American at 1951 patients (21.1%).
- The Two or More Races patient group had the lowest average score at 4.83, with a large amount of 0 and 1 scores.
- White patients, the largest patient race/ethnicity group, have the second lowest average at 4.94 with a notable amount of 4 and 7 scores. Between September and October 2020 there was a sharp increase of 2.02 points. This is an all time high and corresponds with the average wait time among this demographic decreasing by 4 minutes to an all time low of 31.9 minutes.
- Pacific Islanders had the highest average score at 5.33, with a majority of scores ranging from 6 to 9.
<img src=https://github.com/user-attachments/assets/a079700a-57d3-4620-8165-c1e769a2e6d9 height="250">


### Department Referrals
- The largest amount of department referrals go to General Practice at 1840 patients (20.0%). The second largest amount are for Orthopedics at 995 patients (10.8%).
- Patients referred to the Renal department had the lowest average satisfaction score at 4.57. The Renal department accounts for the smallest amount of referrals (86 total).
- Patients referred to the Gastroenterology department had the highest average score at 5.8. This department accounts for the second smallest amount of referrals (178 total).
to do: add graph, remove vertical lines

## Recommendations
### Emphasizing Satisfaction Scores
- **Increase Survey Response Rate:** Encourage patients to submit a satisfaction score, either in person at the end of their appointment or through the digital correspondence channels the hospital offers (email, text, mobile app notifications, etc.)
- **Reach Out to Low Scorers:** Continue communication with patients who submit a low satisfaction score, to collect more detailed information about what negatively influenced their experience.
- **More Detailed Satisfaction Survey:** Instead of having patients submit only a score, develop a more detailed survey for patients to take. This will allow the hospital to better identify its strengths and weaknesses.

### Catering to Unsatisfied Demographics
- **Staff Training:** Implement higher quality customer service and cultural sensitivity training programs for hospital ER staff. 

### Reevaluate Staff Coverage
- **Staff Rescheduling:** Optimize wait times by reallocating staff from shifts with the lowest average wait times to those with the highest average wait times. A portion of the staff scheduled on Saturday evenings could be moved to a shift on another day.
- **Increased Staffing:** Additional staffing could also be a solution to decrease wait times overall.


## Technical Details
Technical analysis for this project involved:
- **Tableau Public:** For data transformation and exploratory data analysis (EDA) via interactive dashboards.

[Visualization on Tableau Public](https://public.tableau.com/app/profile/justinluzong/viz/EmergencyRoomVisitReport_17443380889530/ERExperience)


## Caveats and Assumptions
This project uses Mark Bradbourne's [Real World Fake Data "Hospital ER" dataset](https://data.world/markbradbourne/rwfd-real-world-fake-data/workspace/file?filename=Hospital+ER.csv)
- **Patient ID:** The IDs in this dataset appear to be formatted like Social Security Numbers, which is not how they would usually be formatted.
- **Patient Gender:** The values are 1-2 character abbreviations. The 'NC' value is assumed to stand for 'Nonconforming'.
- **Patient Age:** Ages have been broken down into the following groups: 0-18, 19-35, 36-50, 51-65, and 66+ Years
- **Patient Satisfaction Score:** The range of values for this column is 0 to 10 instead of a more typical range of 1 to 10.
- **Patient Wait Times:** Values for this column are assumed to be in minutes.
- **Patient Admin Flag:** It is unclear what the purpose of this column is, so it was not utilized in this project.
