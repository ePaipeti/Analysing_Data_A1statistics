# Analysing_Data_A1statistics

## In this assignment we cover a range of statistical procedures in the jupyter notebook using python and librarys associated with statistical testing.

Main topics/keywords: correlation, contigency matrix, normal distribution, testing hypothesis, homogenity, parametric, non-parametric 
(Spearman, Pearson, chi-square-test Shapiro-Wilk test, Levene's test, t=tests)


## Datasets for the Assignment

- MillerHadenData.csv:

  | Header     | Data type | Meaning                                          |
  |------------|-----------|--------------------------------------------------|
  | Participant| integer   | participants                                     | 
  | Abil       | integer   | Reading Ability                                  |
  | IQ         | integer   | intelligence                                     |
  | Home       | integer   | Number of minutes spent reading at home per week |
  | TV         | integer   | Number of minutes spent watching TV per week     |

- evaluators.csv:

 | Header     | Data type | Meaning                                            |
 |------------|-----------|----------------------------------------------------|
 | eval_id    | integer   | identification number for each evaluator           |
 | condition  | object/str| by which contidion did they evaluate (read/listen) |
 | age        | float     | the age of each evaluator                          |
 |sex         | float     | the sex of evaluators in binary (man=1.0, woman=2.0|

- ratings.csv:

| Header     | Data type | Meaning                                            |
|------------|-----------|----------------------------------------------------|
| eval_id    | integer   | identification number for each evaluator           |
| Category   | object/str| categories of ratings                              |
| Rating     | float     | the ratings of the evaluators                      |

## Notebook
The jupyter notebook provided documentation and interpretation and can be helpful to any one who wants to perform similar tasks by using python.

## Sources
- "Statistical Analysis with The General Linear Model" by Miller and Haden (2013), Chapter 11.
-  Schroeder, J. and Epley, N. (2015). The sound of intellect: Speech reveals a thoughtful mind, increasing a job candidate's appeal. Psychological Science, 26, 277--891.
