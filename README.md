#AIRPLANE CRASHES AND FATALITIES ANALYSIS

----

#INTRODUCTION


 This project aimed at getting actionable insight by integrating and analyzing some important things on the crashes and fatalities of Airplane within the given range of years (1908-2009)
 

----

#PROBLEM STATEMENT


Some questions were been asked in order to derive a meaningful insight on the data. Some of these questions are;

i) When did the first crash happened? With details

ii) How many crashes occurred over the years?

iii) What is the total number of passengers?

iv) What is the total number of fatalities?

v) Total number of survivor(if any)?

vi) Countries that had the highest number of fatalities

vii)Total number of operators?

viii) What are the causes of the crashes? Details


----

#DATA SOURCING


The data was sourced from kaggle ( Airplane Crashes Since 1908/ Kaggle) where numerous data can be gotten, but I scrapped it from Github using this link https://aka.ms/30DATGitHubRepo

---

#DATA CLEANING/TRANSFORMATION


. Data cleaning was performed per column
. A new column named 'SURVIVOR' was added to the table since it wasn't given in the dataset and it was needed to answer some of the questions. I added this column by subtracting the FATALITIES column from the ABOARD column
. Another column was added which was named 'CRASHES CAUSES', I had to create this column in order to answer those questions related to the causes of the crash. I arrived at this by using 'CONDITIONAL COLUMN' in power query from 'Summary' column
. I also added some new measures to the data

----

#DATA ANALYSIS/VISUALIZATION


Analysis was carried out using some of the visuals in Power BI. Appropriate visuals were been used for each of the analysis

----

#FINDINGS


My findings answered all the questions stated initially in the "PROJECT OBJECTIVE" section and beyond
- The first recorded plane crash in history occurred in 1908, this happened by the U.S Army operator flown by Orville Wright, he nose-dived into the ground from a height of approximately 75 feet killing Lt.Thomas E.Selfridge who was a passenger. One of the two propellers seperated in flight, tearing loose the wires bracing the rudder and causing the loss of control of the aircraft. Orville Wright sufferred broken ribs, pelvis and a leg. Selfridge sufferred a crushed skull and later died.
- The highest number of crashes is 87 which occurred in the year 1970
- The total number of Fatalities were 105,479(approximately 105000)
- The total number of passenger is 144551(approximately 145000)
- The aggregate of the crashes that occurred is 5,268
- Total number of survivor is 39000
- Total number of operator is 2470
- Some of the causes of crashes are Fire, Weather, Shot down, Unknown causes, Engine Failure among others. Weather happened to be the most cause of the crashes with 5152 fatalities
- Russia, Brazil and Ukraine had the highest fatalities of 6317, 2919 and 2826 respectively

Other findings whose questions were not stated;
- Aeroflot operator happened to have the most crashes(179) followed by Military U.S. Airforce operator(176)
- December recorded the highest fatalities across the years with 10459 fatalities
- Highest death or fatalities by route was seen in the Tenerife-Las Palmas route which recorded up to 583 fatalities

----

#RECOMMENDATION


- The climatic condition (i.e weather) should be studied very well before taking off from the airport to avoid crashes
- Passengers should avoid anything that can cause fire hazard e.g smoking while on board
- Proper maintainance should be done by the operators before onboarding

----

#IMAGE OF THE ANALYSIS


![Airplane crashes and fatalities Intro page](https://user-images.githubusercontent.com/97677904/179812919-e04d1f81-f6eb-465b-af1d-5a7c9525daa7.jpg)
![Aiplane crashes and fatalities Analysis](https://user-images.githubusercontent.com/97677904/179812975-8253c62c-519e-4d01-819b-57d3fb4c2bd9.jpg)
![Aiplane crashes and fatalities Dashboard](https://user-images.githubusercontent.com/97677904/179813008-d8d7f60f-8a3f-4178-b829-029ed03b49f1.jpg)

