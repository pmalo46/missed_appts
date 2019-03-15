# missed_appts
Exploratory Data Analysis of Missed appointments in Brazil dataset

This dataset presents us with information on over 110,000 medical appointments in Brazil. Brazil has a big problem with missed appointments, with around 1 in 5 people failing to show up.

We are provided with an array of factors such as ID numbers, patient Age, Gender, ScheduledDay (day appointment was scheduled), AppointmentDay, Neighbourhood (where the appointment was to take place), We then have binary columns for factors such as whether the patient is on scholarship, whether they suffer from Alcoholism, Diabetes, or Hypertention, or whether they have any Handicaps. Finally, there is data on whether or not the patient received a reminder SMS, and whether or not they missed their appointment.

Some of the questions I explored with this data set are:

Does age play a factor in predicting whether the patient will show up?
Are men or women more likely to not show?
Does location matter?
Do the SMS reminders actually work?

### Conclusions

This dataset gives us many factors to consider as we look for correlations with missed appointments. It appears that the most relevant factors may be Age, the location the appointment was scheduled for, and whether an SMS reminder was received.

We saw that there were a higer ditribution of young people in the group that missed their appointments than in the group that showed up.

We looked at the Gender breakdown for each group, and saw that they looked nearly identical, so there is likely no correlation there.

Ironically, the No-shows had a much higher rate of receiveing SMS reminders than the group that showed. The data can't tell us why this is, so a more qualitative study would need to be done to determine whether this is coincidental, or if there was something with the SMS process that needs to be refined.

The location can also play a role. As we saw in the example, some locations have a much higher percentage of missed appointments that the overall dataset.

It is important to note that these are merely correlations, and that it can not be assumed that someone will miss an appointment if they are 30 years old, booked for the SANTOS DUMONT location, and recieved an SMS reminder. The data can only show us trends, and further investigation is always needed when trying to determine whether a factor may be truly relevant.
