# INVESTIGATE-A-DATASET-ALX-T-NANODEGREE
> Dataset: No-show appointments
Description: This dataset collects information from 100k medical appointments in Brazil and is focused on
the question of whether or not patients show up for their appointment. A number of characteristics about
the patient are included in each row.

>Columns Description
PatientId : The patient's ID(Identification Number)
AppointmentID : Appointment ID(Identification Nunber) this field should be unique for each
appointment
Gender : Patient's gender (Male/Female)
ScheduledDay : The day of the actuall appointment, when they have to visit the doctor.
AppointmentDay : The day someone called or registered the appointment, this is before appointment
of course.
Age : How old is the patient
Neighborhood : Where the appointment takes place(Health Center Location)
Scholarship : Shows whether or not the patient is enrolled in Brasilian welfare program Bolsa
Família.(1 if true, 0 if False)
Hipertension : Tells if the patient is experiencing Hypertension.(1 if true, 0 if False)
Diabetes :Tells if the patient is experiencing Diabetes.(1 if true, 0 if False)
Alcoholism :Tells if thepatient is experiencing Alcoholism.(1 if true, 0 if False)
Handcap : Tells if the patient is with special needs.(Ranking from 0-4 to show the level of special
needs)
SMS_received : Tells if the patient has received a reminder text message and the number of
messages received(1 if true, 0 if False)
Show-up : ‘No’ if the patient showed up to their appointment, and ‘Yes’ if they did not show up.

> We will be investigating the dataset to uncover the following:
1. What factors are important for us to know in order to predict if a patient will show up for their
scheduled appointment?
2. How do the Factors vary with Each Other?

> Research Areas
1. Target Variable(Absent) : studying the trends in the absent study overall proportions to help in
the analysis with other variables
2. Univariate Analysis : Studying each variable to uncover patterns and how they relate with the
target variable. How does Age , Gender , Neighbourhood and Scholarship influence a patient
from attending the Hospital appointment.
3. Multivariate Analysis : Studyying how the variables relate with one another and how they can
help in predicting the target variable. How do the variables affect each other(Correlation) and affects
the target variable.

> LIMITATIONS
1. Time was set to 00:00:00 for all cases, analysis was only carried in days. Cases of Having an appointment
and schedule on the same day could not be used for the analysis
2. The data was not totally consistent, some unusual forms of data and irregularities were found which
could have affected the analysis because it was dropped.
3. Most of the columns are categorical, hence the use of Bar charts and Pie charts, Only Age was
quantitative and could be visualised with appropraite means.
4. The Neighbourhood Data should have included the gographical coordinates for better analysis as to
how a location can affect the choice of the patient
