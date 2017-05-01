# University-of-Chicago-UrbanLabs-Data-Challenge
Data Challenge- Data Scientist position


## UChicago Urban Labs

Cities fuel remarkable economic, social, educational and cultural progress.  At the same time, cities amplify and concentrate dire social problems. The University of Chicago Urban Labs works to address challenges across five key dimensions of urban life: crime, education, health, poverty, and energy & environment. They partner with civic and community leaders to identify, test, and help scale the programs and policies with the greatest potential to improve human lives.

“There is still a great amount of work needed to solve the problems that cities face. Urban Labs uses science, data, and evidence-based programs to inform and develop urban policy for the biggest impact possible.” - Nutter


## Background

In January 2012, the Cook County State’s Attorney’s Office established a program intended to reduce re-arrest among people on bail awaiting trial. The program ran through October 2013. The SA’s Office asked you to evaluate the effectiveness of the program and provided the data described below. The person who created the program left, so we know little about how people were assigned to the program, but we do know assignment was done independently at each arrest. This means that it’s possible that someone arrested multiple times could have been referred to the program on some occasions but not on others.

## Data
There are three data sets: case.csv, demo.csv, and prior_arrests.csv. Case.csv is the main dataset showing dates of arrest and disposition (trial or court appearance) during the time the intervention program ran, as well as an indicator of whether the arrestee was referred to the intervention program for that arrest. Demo.csv contains some demographic information about the arrestee, and prior_arrests.csv contains information on individuals’ arrest histories from 2008-2011.

### Part 1: Data Management

a. The main outcome of interest is whether the defendant was arrested again prior to his/her disposition (trial or court appearance) date. Create a variable called ‘re_arrest’ that equals one if the defendant was arrested prior to trial and zero otherwise. E.g., imagine person 1 was arrested three times.

b. Create a variable called prior_arrests that equals the number of arrests prior to the current arrest. Assume that all of the individual’s arrests prior to the study period are contained in prior.csv. For example, if person z has five arrests in prior.csv and two in case.csv, her first arrest in case.csv should have prior_arrests = 5 and the second should have prior_arrests = 6. If someone is not included in prior_arrests.csv, assume they had zero arrests at the start of the study period.

c. Create an ‘age’ variable that equals the defendant’s age at the time of each arrest.


### Part 2: Statistical Analysis

Help the SA’s Office determine if the program should be continued/expanded by estimating the program’s effect on re-arrests prior to disposition. To draw conclusions about this program’s effect, answer the following questions.

a. Describe the study population based on the data available to you.

b. Are the treatment and control groups balanced, or are differences (race, gender, age, and prior
arrests) in the composition of the two groups?

c. Did participating in the program reduce the likelihood of re-arrest before disposition? Explain
your answer and your methodology.
