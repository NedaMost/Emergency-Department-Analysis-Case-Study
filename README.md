# Emergency-Department-Analysis-Case-Study
Emergency Department Analysis – Case Study
Context
The manager of the Emergency Department (ED) at Hospital A has approached you with questions about patients coming into hospital for mental health (MH) related issues.  Specifically, she is concerned about the number of patients visiting Hospital A (which does not have the resources to deal with MH patients) and end up being transferred to Hospital B.  Additionally, there are concerns that many of these patients may not need to visit the hospital at all. She is hoping that you can use your expertise to help address these concerns.
In the attached Excel file, you will find the ED administrative data for mental health patients back to September 2019.  Each line represents a patient visit to ED along with relevant patient characteristics and major events occurred during the visit.
 
Questions
Basic Analytics
1.	What is the average number of MH visits per day to Hospital A?  
2.	How many unique patients arrived at Hospital A in total, and by each acuity level?  
3.	List top three most common presenting complaints in Hospital A, and their respective number of visits.
4.	Length of Stay in Emergency Department (from arrival time to time leaving ED)
a.	What is the average length of stay in Emergency Department of Hospital A patients, in hours and minutes?  
b.	What is the median length of stay of these patients, in hours and minutes?  
c.	How would you explain the difference between the median length of stay and the average length of stay?  
d.	What is the range of variability of the length of stay?  

5.	Patient volume by day of the week:
a.	Which day(s) of the week see the highest patient volume in Hospital A?  
b.	What might your answer from 5a tell you?  
6.	How many unique Hospital A patients went to Hospital B after their initial Hospital A visits within 24 hours?  Please describe the approach you used to obtain the answer (Hint: You may have multiple records for the same person.  You will need to determine how to find one unique record for that individual).
7.	Assuming you have a dataset, [Hospital A + B],  where data for hospital A & B are appended together in one, complete the following questions:
a.	Write SQL code (or another coding language, if you don’t know SQL) to obtain the total number of unique patients who arrived between 8 AM and 4 PM.  
b.	How would you show only the data for “Hospital A”?  
c.	How would you filter all arrivals that occurred between September 1, 2021 and October 15, 2021 (inclusive), and those occurred between February 1, 2022 and March 31, 2022 inclusive?  
d.	If you had another table, [Doctor on Duty], that shares the same “VisitID” values as in [Hospital A + B], and provides additional information such as “DoctorName”, explain how you would join these two tables to obtain the # of patients seen by each doctor.  
# Analysis Recommendations
1.	Based on your analysis above, what recommendations could you provide to the manager to address her concerns?  
2.	Can you make any recommendations regarding the practice of sending patients to another hospital?  
3.	Are there any other questions not asked in Basic Analytics section but you think the manager might be interested in, based on her stated concerns?  
