Exploratory Data Analysis (EDA) - Medical Appointment No Shows

Dataset Description
This project analyzes the "Medical Appointment No Shows" dataset, which contains information about medical appointments and whether patients attended or missed them.

- Dataset Source: https://www.kaggle.com/datasets/joniarroba/noshowappointments
- Number of Rows (Before Cleaning): 110,526
- Number of Rows (After Cleaning): 106,987
- Number of Columns: 15


Features Description
The dataset includes the following features:

-Gender: Patient gender
- Age: Patient age
- Hypertension: Whether the patient has hypertension
- Diabetes: Whether the patient has diabetes
- Alcoholism: Whether the patient has alcoholism
- SMS_received: Whether the patient received SMS reminders
- ScheduledDay: The day the appointment was scheduled
- AppointmentDay**: The actual appointment day
- No-show: Whether the patient showed up or not



Data Cleaning
Several data cleaning steps were performed:

- Removed unrealistic age values (Age > 100)
- Removed duplicate rows
- Converted date columns into datetime format
- Created a new feature **WaitingDays**
- Removed negative waiting days (invalid records)
- Converted "No-show" into numerical values (0 and 1)

Cleaning Results:
- Rows removed: 3,539
- Dataset became cleaner and more consistent

---

Data Visualization
The following visualizations were created:

1. Age Distribution
2. Show vs No-show
3. Gender vs No-show
4. SMS Received vs No-show
5. Age vs No-show (Boxplot)
6. Correlation Matrix (Heatmap)
7. Diabetes vs No-show
8. Age Density Distribution


---

🔍 Key Insights
- Most patients attend their appointments, but a noticeable percentage miss them.
- SMS reminders slightly reduce no-show rates.
- Younger patients tend to miss appointments more often.
- Patients with medical conditions are more likely to attend.
- No strong correlation exists between most variables.

---

🧠 Conclusion
The data cleaning process improved the dataset quality by removing invalid and duplicate records. The analysis revealed patterns in patient behavior and highlighted factors that influence appointment attendance.


