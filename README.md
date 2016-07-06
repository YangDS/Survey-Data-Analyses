# Survey-Data-Analyses
This project demos predictive modeling with Python

1. Survey analysis & predictive modeling project

For this project, there are two different types of data on a sample of ~1000 members:

(1) Survey answers from members

(2) Static data and measured variables for the members

The following files have data for this project:

(1) Survey_data_ver20.csv

(2) Observed_data_ver20.csv
 
The survey data file includes survey response to 42 questions, with each answer coded as 3 (high interest in or use of the feature) to 1 (neutral) to 0 (dislike or nonuse of feature).

Members who skipped the question have blank values, and some members gave text responses of "other" or "don't know".

For members who completed the survey who have id > 90000000, we also have additional measurements, including:

• Static1 – a feature of each member (numeric coded categorical feature)

• Duration – the number of time periods for the cumulative observations

• F1, F2 – observed variables that may predict M1 and status

• M1 – the observed variable we wish to predict

• Status – a second prediction variable (4 possible values)

Please consider the following questions and describe if these data give good answers to these questions:

1. What survey questions group together based on the answers received? (Feel free to define different clusters based on degree of similarity)

2. Do these clusters define cohorts of members with similar values of status, duration M1, F1, F2?

3. Do any questions or group of questions separately predict the values of status, duration M1, F1, F2?

4. Do the observed data (static1, F1, F2) predict the values of M1 and status?
