Project Goal

## introduction
In this project, I am an employee of College Board and I am tasked with using the provided data and some outside research to make recommendations about where money is best spent to improve SAT participation rates in the state of Florida. The precursor to the recommendation is that the new format for the SAT was released in March 2016.



## Conclusion
The main takeaways are that funding per student and the enactment of a state policy which would make it compulsory to take the ACT or SAT are both paramount in increasing low participation. Though making the tests compulsory in the state would be a more effective measure. Thus, college board could suggest or even lobby congress to implement these 2 measures in Florida as the state is not faring well in participation rate for both tests. In fact, the rates have been declining.

On the state budget side of things, perhaps it would make sense to enact a policy like that of Vermont's Act 60, which would allow wealth to be evenly distributed across the state and thus allowing more underprivileged or underfunded students to take the exam either by giving them subsidies or making it free of charge.



## Data Dictionary

| Feature                                    | Type  | Dataset | Description                                   |
|--------------------------------------------|-------|---------|-----------------------------------------------|
| 2017_act_participation                     | Float | act     | participation rate of act in 2017             |
| 2017_act_english                           | Float | act     | score of act english in 2017                  |
| 2017_act_math                              | Float | act     | score of act math in 2017                     |
| 2017_act_reading                           | Float | act     | score of act reading in 2017                  |
| 2017_act_science                           | Float | act     | score of act science in 2017                  |
| 2017_act_composite                         | Float | act     | composite score of act in 2017                |
| 2017_sat_participation                     | Float | sat     | participation rate of sat in 2017             |
| 2017_sat_eb_read_write                     | Float | sat     | sat reading and writing score in 2017         |
| 2017_sat_math                              | Float | sat     | sat math score in 2017                        |
| 2017_sat_total                             | Float | sat     | sat total score in 2017                       |
| 2018_act_participation                     | Float | act     | participation rate of act in 2018             |
| 2018_act_composite                         | Float | act     | composite score of act in 2018                |
| 2018_act_updated_student_tested_percentage | Float | act     | updated percentage of students tested in 2018 |
| 2018_act_updated_avg_composite             | Float | act     | updated average act composite score in 2018   |
| 2018_act_updated_avg_english               | Float | act     | updated average act english score in 2018     |
| 2018_act_updated_avg_math                  | Float | act     | updated average act math score in 2018        |
| 2018_act_updated_avg_reading               | Float | act     | updated average act reading score in 2018     |
| 2018_act_updated_avg_science               | Float | act     | updated average act science score in 2018     |
| 2018_sat_participation                     | Float | sat     | participation rate of sat in 2018             |
| 2018_sat_eb_read_write                     | Float | sat     | sat reading and writing score in 2018         |
| 2018_sat_math                              | Float | sat     | sat math score in 2018                        |
| 2018_sat_total                             | Float | sat     | sat total score in 2018                       |


## Notebook Contents

- 2017 Data Import & Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations

## Datasets
- [SAT 2017 Scores](./data/sat_2017.csv)
- [SAT 2018 Scores](./data/sat_2018.csv)
- [ACT 2017 Scores](./data/act_2017.csv)
- [ACT 2018 Updated Scores](./data/act_2018_updated.csv)


## Sources
https://www.studypoint.com/ed/sat-and-act-test/
https://www.princetonreview.com/college/sat-changes#:~:text=The%20SAT%20has%20undergone%20its,students%20get%20the%20inside%20scoop
https://blog.prepscholar.com/sat-math-vs-act-math-whats-the-difference
https://blog.prepscholar.com/sat-math-vs-act-math-whats-the-difference#:~:text=In%20terms%20of%20content%2C%20the,math%20concepts%20as%20a%20whole.&text=The%20SAT%20Math%20section%20does,the%20ACT%20Math%20section%20does
https://apps.urban.org/features/education-funding-trends/
https://www.edweek.org/ew/section/multimedia/states-require-students-take-sat-or-act.html
https://publicassets.org/library/publications/reports/20-years-ago-act-60-fundamentally-changed-the-way-vermont-pays-for-public-education/
