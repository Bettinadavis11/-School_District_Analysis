# School District Analysis

## Overview of the School District Analysis
This School District Analysis was created to aid Maria and the school board in upholding state-testing standards, as evidence of academic dishonesty is shown.
The school board is not fully aware of the extend of the academic dishonesty and have asked us to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.

## Results

### How is the district summary affected?<br>
The district summary had a slight decrease in all metrics. However, it was minimal and did not decrease the “Overall Passing %” by much (0.03%).
<br>
### How is the school summary affected?<br>
While replacing the math and reading scores for Thomas High School, we noticed that the “Average Reading Score” increased by a 0.05%, while all other metrics had a minimal decrease.
<br>
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
It did not affect by much the “Overall Passing Scores” compared to the other schools.<br>
<br>
### How does replacing the ninth-grade scores affect the following:<br>

* ### District Summary:<br>
There was a slight change in the district summary, since the Average Math score went down by 0.1.<br>
![District Summary](https://user-images.githubusercontent.com/86321353/138509050-db9a66b6-c8a1-45e1-bbc6-664353aa01cd.png)

* ### School Summary:<br>
Updating the 9th graders scores to NaN shown a significant decrease in passing percentages. Once the 9th graders scores were removed, the passing grades were almost the same; However, there was a slight increase on the Reading Averages.<br>
![School Summary](https://user-images.githubusercontent.com/86321353/138510640-4b1c5bdc-3e41-4732-a895-5630093e0ae7.png)

* ### School Performance:<br>
There were no significant changes as Thomas High school remained on the 2nd place.
![School Performance](https://user-images.githubusercontent.com/86321353/138509743-e64c2df8-851a-4f0f-acdb-cff06071114a.png)

* ### Math and Reading scores by grade:<br>
It did not affect the overall performance. However, the data from the nineth graders was removed.
#### Original Scores
![Original scores](https://user-images.githubusercontent.com/86321353/138509323-1fc23662-a17d-460d-bdd9-051927c362cb.png)
#### Updated scores
![updated scores](https://user-images.githubusercontent.com/86321353/138509618-aa24542e-8124-4687-8308-da7c0917cf9d.png)

* ### Scores by school spending:<br>
Only the average reading score increased. However, all other metrics decreased.
![Updated scores by spending](https://user-images.githubusercontent.com/86321353/138510000-8617cf88-1a9e-4d45-ae31-a10918d99289.png)

* ### Scores by school size:<br>
Only the scores for the mediums size schools were affected as shown on the picture below.
![updates scores by school size](https://user-images.githubusercontent.com/86321353/138510126-e534a4fe-9d10-4066-98d7-7256fd13584a.png)

* ### Scores by school type:<br>
The only type of school that was affected was the Charter schools, as Thomas High School is a Charter school.
![scores by school type](https://user-images.githubusercontent.com/86321353/138510313-0ef127fe-a36a-4c50-9a1c-70cb097ed2c0.png)

## Summary
* After replacing the scores for only the Thomas High School’s ninth graders, is evident that there was not much of a difference, as it did not alter the overall passing percentage or other metrics.<br>
* Even after omitting the data, Thomas High School remained 2nd in the district.
* Since we had to omit the 9th graders data, the scores used to perform our analysis was only from the 10th to 12th graders.
