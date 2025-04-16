# Emergency Room Visit Report

[Emergency Room Visit Report on Tableau Public](https://public.tableau.com/app/profile/justinluzong/viz/EmergencyRoomVisitReport_17443380889530/ERExperience)

## Overview
This report provides an overview of patient visits to a hospital emergency room. The goal of this report is to improve the overall ER patient experience at this hospital by optimizing wait times and catering to the needs of notable demographics.  
This report is comprised of the following dashboards:
- Emergency Room Experience Report - focuses on patient satisfaction ratings and wait times
- Emergency Room Demographics Report - focuses on patient count, gender, age group, race/ethnicity, and department referrals
- Data Source - displays dataset used in this project

## Dataset
This project uses Mark Bradbourne's [Real World Fake Data "Hospital ER" dataset](https://data.world/markbradbourne/rwfd-real-world-fake-data/workspace/file?filename=Hospital+ER.csv)

These are my findings from my initial look through the dataset:
- The fictional Patient IDs in this dataset appear to be formatted like Social Security Numbers, which is not how they would typically be formatted.
- The range of values for the Patient Satisfaction Score column is 0 to 10 instead of a more likely to be expected 1 to 10. A majority of the records have NULL values for this column. 
- It is unclear what the purpose of the Patient Admin Flag column is, so it has not been utilized in the project.

## Questions
1. How many patients were seen in the last 12 months (of this dataset: Nov 2019 to Oct 2020)?
2. What month had the highest average patient satisfaction score? The lowest average patient satisfaction score?
3. What age group has the highest number of patients?
4. What race or ethnicity has the highest number of patients?
5. What month had the shortest average wait time? The longest average wait time?
6. What days and times have the top 3 longest patient wait times? The top 3 shortest patient wait times?
7. What are the top 3 department referrals?

## Answers
1. Total patients from Nov 2019 to Oct 2020: 5831 patients
2. Highest average patient satisfaction score: March 2020 (5.33 out of 10);  
   Lowest: April 2020 (4.63 out of 10)
3. Largest age group: 19 - 65 Years, across every month
4. Largest race or ethnicity: White (2571 patients)
5. Shortest average wait time: October 2020 (34.1 mins);  
   Longest: February 2020 (36.7 mins)
6. Longest wait times: Mon 11 PM (40.69 min), Wed 3 AM (39.74 min), Fri 10 PM (39.34 min);  
   Shortest: Wed 1 AM (29.65 min), Sat 9 PM (30.09 min), Sat 4 PM (30.52 min)  
   Overall Range: 11.04 min
7. Top referrals: General Practice (1840 patients), Orthopedics (995 patients), Physiotherapy (276 patients)
