# Statistical Analysis and Visualization of Anxiety Levels Found in Statistics and Math Classes (Python/ R)
Data from: [a survey conducted at Dalhousie University that asked students their demographics and various questions to gauge their anxiety in different areas.](https://osf.io/nzhq6/files/osfstorage)
***
## Question 1: Does statistics anxiety differ by faculty (arts, science, other, and program level (undergrad vs grad)?
Through the use of a two way ANOVA test, I found that the variation of test anxiety in statistics classes could be explained with program type (undergraduate, graduate). 
Program type for level of test anxiety had a large F statistic (19.839) as well as a very low p-value (1.07e-05) indicating strong evidence against the null hypothesis (there is no significant difference between the means of the undergraduate/graduate)

We can attribute undergraduate students having a higher mean test anxiety to the likelihood of graduate students being better students and thus feeling less anxious for tests.

Faculty did not have as high of an F statistic (4.467) but had a p-value low enough to be statistically significant (0.012)

## Question 2: Can signs of self-efficacy, anxiety sensitivity, and self-critical perfectionism be used to predict anxiety in Statistics?
Using a linear regression model to predict test anxiety and willingness via results from the survey did not prove to create an accurate model with both having R-squared values of less than 0.3. 
If we wanted more accurate predictions, a different model should be used (such as decision trees and RandomForest).

Update: By utilizing Random Forest to predict anxiety found within math classes, R2 doubled in value, creating a more accurate model.

## Question 3: How does test anxiety differ by faculty and program type?
![image](https://github.com/echu-vb/student_anxiety/blob/f29bfb2b91a7f1966c1f9fbc0e94ee3e2f51f21e/graph1.png)
![image](https://github.com/echu-vb/student_anxiety/blob/c2fc9996c3a21baa2de6a59d5ee476458f8f3e99/graph2.png)
Like what I mentioned before, undergraduate students are shown to have a higher test anxiety for statistics classes and out of the three major types, art majors showed the highest test anxiety while the rest had a similar level of anxiety. We can atribute this to art majors feeling less prepared for a class that is outside of their major curriculum.
