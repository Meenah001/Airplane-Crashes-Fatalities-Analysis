# AIRPLANE CRASHES AND FATALITIES ANALYSIS

----

# INTRODUCTION


 This project aimed at getting actionable insight by integrating and analyzing some important things on the crashes and fatalities of Airplane within the given range of years (1908-2009)
 

----

# PROBLEM STATEMENT


Some questions were been asked in order to derive a meaningful insight on the data. Some of these questions are;

i) When did the first crash happened? With details

ii) How many crashes occurred over the years?

iii) What is the total number of passengers?

iv) What is the total number of fatalities?

v) Total number of survivor(if any)?

vi) In Which month was the highest fatality record?

vii)Total number of operators?

viii) What are the causes of the crashes? Details, and the number of fatalities recorded by each causes

ix) Highest number of crashes by flight type


----

# DATA SOURCING


The data was sourced from kaggle ( Airplane Crashes Since 1908/ Kaggle) where numerous data can be gotten, but I scrapped it from Github using this link https://aka.ms/30DATGitHubRepo

---

# DATA CLEANING/TRANSFORMATION


. Data cleaning was performed per column

. A new column named 'SURVIVOR' was added to the table since it wasn't given in the dataset and it was needed to answer some of the questions. I added this column by subtracting the FATALITIES column from the ABOARD column

. Another column was added which was named 'CRASHES CAUSES', I had to create this column in order to answer those questions related to the causes of the crash. I arrived at this by using 'CONDITIONAL COLUMN' in power query from 'Summary' column

. I also added some new measures to the data

----

# DATA ANALYSIS/VISUALIZATION


Analysis was carried out using some of the visuals in Power BI. Appropriate visuals were been used for each of the analysis

----

# FINDINGS


My findings answered all the questions stated initially in the "PROJECT OBJECTIVE" section and beyond

- The first recorded plane crash in history occurred in 1908, this happened by the U.S Army operator flown by Orville Wright, he nose-dived into the ground from a height of approximately 75 feet killing Lt.Thomas E.Selfridge who was a passenger. One of the two propellers seperated in flight, tearing loose the wires bracing the rudder and causing the loss of control of the aircraft. Orville Wright sufferred broken ribs, pelvis and a leg. Selfridge sufferred a crushed skull and later died.

- The highest number of crashes was 75 which occurred in the year 1972
 
- The total number of Fatalities were 83,433(approximately 83,000)

- The total number of passenger is 117,319(approximately 117,000)

- The aggregate of the crashes that occurred is 2,750
 
- Total number of survivor was 33,886(approximately 34,000)

- Total number of operator is 1,905

- The highest fatalities was recorded in the month of september(8,405 fatalities) 

- Some of the causes of crashes are Fire, Weather, Shot down, Unknown causes, Engine Failure among others. Weather happened to be the most cause of the crashes with 82,384 fatalities

# Other findings whose questions were not stated;

- Douglas DC-3 flight type happened to have the most crashes(237)
 
- Russia had the highest fatalities(4,170) followed by Brazil(2,308)

- It was also seen that philippines had the highest number of survivor
----

# RECOMMENDATION


- The climatic condition (i.e weather) should be studied very well before taking off from the airport to avoid crashes

- Passengers should avoid anything that can cause fire hazard e.g smoking while on board

- Proper maintainance should be done by the operators

----

# IMAGE OF THE DASHBOARD

![Screenshot 2023-05-24 212013](https://github.com/Meenah001/Airplane-Crashes-Fatalities-Analysis/assets/97677904/73d4d5c8-08ec-424b-b433-37aa381fbccb)
