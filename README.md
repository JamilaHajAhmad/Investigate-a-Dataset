
# Investigating Medical Appointment No Shows Dataset Project🔍📄💡

![alt text](image.png)

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Objective](#objective)
- [Methodology](#methodology)
- [Key Findings](#key-findings)



## Project Overview
This project investigates the **Medical Appointment No Shows** dataset to uncover insights, trends, and patterns that can inform decision-making in [related field or context, e.g., healthcare, finance, etc.]. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization. The source of the dataset is [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments).

## Dataset Description
The dataset used in this project consists of **110.527** medical appointments with its **14** associated variables (characteristics). It includes the following key columns:<br>
<table>
    <thead>
        <tr>
            <th>Column</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>PatientId</td>
            <td>Unique identifier for each patient</td>
        </tr>
        <tr>
            <td>AppointmentID</td>
            <td>Unique identifier for each appointment</td>
        </tr>
        <tr>
            <td>Gender</td>
            <td>Male or Female</td>
        </tr>
        <tr>
            <td>ScheduledDay</td>
            <td>The day of the actual appointment, when they have to visit the doctor.</td>
        </tr>
        <tr>
            <td>AppointmentDay</td>
            <td>The day someone called or registered the appointment, this is before appointment of course.</td>
        </tr>
        <tr>
            <td>Age</td>
            <td>How old is the patient.</td>
        </tr>
        <tr>
            <td>Neighborhood</td>
            <td>Where the appointment takes place.</td>
        </tr>
        <tr>
            <td>Scholarship</td>
            <td>True if the patient was enrolled in Brasilian welfare program called Scholarship, False otherwise.</td>
        </tr>
        <tr>
            <td>Hypertension</td>
            <td>True if the patient has hypertension, False otherwise.</td>
        <tr>
        <tr>
            <td>Diabetes</td>
            <td>True if the patient has diabetes, False otherwise.</td>
        </tr>
        <tr>
            <td>Alcoholism</td>
            <td>True if the patient is an alcoholic, False otherwise.</td>
        </tr>
        <tr>
            <td>Handcap</td>
            <td>True if the patient has a handcap, False otherwise.</td>
        </tr>
        <tr>
            <td>SMS_received</td>
            <td>1 or more messages sent to the patient.</td>
        </tr>
        <tr>
            <td>No-show</td>
            <td>True if the patient did not show up to their appointment, False otherwise.</td>
        </tr>
</table>

## Objective
The primary goal of this investigation is to figure out the factors that most contribute to not showing up to a medical appointment.

## Methodology
1. **Data Collection**: Took the dataset CSV file from Kaggle platform.
2. **Data Cleaning**: Renaming columns, optimizing the datatype of columns for effective memory consumption,<br>
removing some unnecessary columns, ...
3. **Exploratory Data Analysis**: visualizations and summary statistics
4. **Conclusion**: Addressing the key findings and limitations

## Key Findings
1. The dataset contains approximately 20.2% no-shows.<br>
2. The average age of patients who did not show up to their appointments is slightly younger than the average age of patients who did show up.<br>
3. Females are more likely to not show up to their appointments than males.<br>
4. Receiving messages affects the no-show status.<br>
5. The neighborhood with the highest percentage of no-shows is 'JARDIM CAMBURI ', with approximately 6.6% of no-shows.<br>
6. The second highest percentage of no-shows is 'MARIA ORTIZL', with approximately 5.5% of no-shows.<br>
7. The third highest percentage of no-shows is 'ITARARÉ', with approximately 4% of no-shows.<br>
8. The dataset is clean and optimized for memory allocation, with most columns converted to boolean and the datatype of 'age' optimized to 'int8'.<br>
9. The dataset can be used to answer the questions posed earlier, and the relationships between different variables and no-show status can be visualized using plots.
