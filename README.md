# Investigate-Medical-Appointment-NoShows-Dataset
Exploratory Data Analysis (EDA) and data visualization project using python

## Oiverview
In this project, you'll go through the data analysis process and see how everything fits together./ We will analyze a dataset and then communicate your findings about it. We will use the Python libraries NumPy, pandas, and Matplotlib to make your analysis easier.

## Project Overview
This collected data consists of 2 datasets tmdb_5000_movies and tmdb_5000_credits include data about almost 5,000 movie collected from TMDB. The 2 datasets combined contain 24 columns include information about movies such as generes, cast, budget, revenue and date of release.

## Built with
* Python 3.6.6 
* pandas
* NumPy
* Matplotlib
* Seaborn
* csv

## Findings
1. Ages 0-10 and 35-65 have the highest frequency of scheduled appointments, while ages 70-100 have the lowest frequency. But the proportion of patients who miss scheduled appointments is almost the same at all ages, so age is not an important factor in missing scheduled appointments. Also, the number of females who schedule an appointment is much higher than the number of males, but only 20.24% of females and 19.87% of males showed up, hence genedr doesn't affect missing the scheduled appointments.
2. 16.55% of patients who didn't receive SMS attended the appointments, while 27.57% of patients who received SMS showed up, which is 11.02% higher, as a result recieving SMS has an influence on attending scheduled appointments.
3. The percentage of patients with no scholarship who attended the appointments is 19.72% and only 23.67% for patients with scholarship, as a result having scholarship doesn't affect missing the scheduled appointments significantly.
4. Patients with some health conditions such as hypertension, diabetes, handicap, and alcoholism represent a small proportion of patients in dataset, and the percentage of hypertension patients who miss the appointments is 17.3% and 20.9% for patients with no hypertension, as a result health conditons don't play important role in missing the appoinments.
Of the 5 most frequent neighbourhoods in dataset ITARARÉ has the highest percentage of patients who showed up , and JARDIM DA PENHA has the lowest percentage, although, the proportions in different neighbourhoods are nearly the same, hence neighbourhood doesn't affect missing the scheduled appointments significantly.
5. The Percentage of patients show up less than 10% when the appointment is scheduled on the same day, while it is 20-30% when waiting is 1-9 days , but the percentage increases slightly in 10-14 days wait and exceeds 30%. And, the proportion of patients who show up for scheduled appointments is nearly the same every day of the week except Sunday, and also the same in different month intervals, as a result, specific weekdays and month intervals have no influence on missing appointments, while waiting days before appointments is an important factor.

## Limitations
Attributes of the dataset are not sufficient to optimize the exploration and findings of dataset analysis, as stated earlier waiting days before scheduled appointments significantly affect missing the appointments, and there is a possibilty that there are different vital associated elements which may include distance to hospital, in addition, time of 'AppointmentDay' attribute should be inserted besides date to investigate the influence of different intervals through the day.
