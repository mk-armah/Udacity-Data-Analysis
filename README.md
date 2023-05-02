# Udacity-Data-Analysis
ALX | Data Analysis Program - Hands on Unguided Projects 

# Introduction
## Dataset Description
This dataset consists of samples from patients who booked an appointment with a medical center. It is focused on the question of whether or not patients show up for their appointment. The characteristics of the patients are included in each row.

‘ScheduledDay’ provides information on the day the patient set up their appointment. ‘Neighborhood’ indicates the location of the hospital. ‘Scholarship’ indicates whether or not the patient is enrolled in Brasilian welfare program Bolsa Família.

## Question(s) for Analysis
<ul>
  <li>What is the Percentage of Patients who show up for Appointments vs Patients who do not ? </li>
  <li>On which Day is it likely for Patient's to miss their Appointments </li>
  <li>Does the month the within which the Appointment was booked have any Significant Impact on whether or not Patients will show up for their Appointments ? </li>
  <li>Does the Patient's Age determine whether or not he/she will show up for appointments ? </li>
  <li>How does the Patient's Gender associate with Attending Appointments ? </li>
</ul>
## Findings
Attention should be given to the SMS Alerts sent to Patients after Appointments are booked. It suprising to say that patients who receive SMS alerts are most likely to not show up for their appointment.

This factor should be throughly explored to discover why this happens.

Greater Emphasis should be placed on the 1st,7th,8th and 30th day of the every month, since patient's most likely fail to show-up for their Appointments on these dates. Proper Analysis should be made to determine factors affecting such dates, e.g Events and Occasions etc, holidays etc.

A limitation to this analysis is with regards to the sample distribution of the Dependent Variable (NoShow Column). The NoShow column is highly imbalanced and as such may affect predictive analysis/modeling.
