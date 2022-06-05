BIKE SHARING ANALYSIS

OVERVIEW
This project picks up from the idea of entering a partnership to start a bike sharing business in Des Moines, Iowa, modeled after the Citi Bike sharing program in New York City.  I used Tableau as the primary tool for visualizing my proposal for investors.  Extract data was taken from Citi’s bike sharing dataset and downloaded into Tableau.  After analyzing data for the month of August, worksheets were created, and a story was developed to share.  

RESULTS
For our bike trip analysis, Pandas was first used to change the "tripduration" column in the original dataset from an integer to a datetime datatype in the new dataset.  Using this updated datatype, visualizations were created to:
•	Show the length of time that bikes are checked out for all riders and genders
•	Show the number of bike trips for all riders and genders for each hour of each day of the week
•	Show the number of bike trips for each type of user and gender for each day of the week.

[link to dashboard] https://public.tableau.com/app/profile/preston.clark8164/viz/Book1_16543392268360/Deliverable2Story?publish=yes





Two data points that stand out among all the assessed data categories are user type and gender.  Although Citi Bike is available for everyone’s use, it does offer a subscription-based service. Among the total rides taken in the month of August, the following visual reveals that 81% of the rides were taken by individuals with a subscription.



When we assess the number of rides based on gender, we again see a large disparity.  Our data shows that 65% of the total rides were taken by male riders.  However, this does not suggest the remainder of rides were taken by female riders due to the added gender option of “unknown” as shown below.


An analysis was made on three additional data points with use of worksheets, a dashboard, and a story for visualizations:  August peak hours, bike repairs, and bike utilization.
August Peak Hours: One-third of all rides taken in August occurred between 4 and 8pm.


Bike Repairs:  An id number is associated with each bike in the system. This allows for the strategic rotation of bikes from those in areas with low usage to those in areas of high usage. The id numbers also help with bike upkeep and safety through the scheduling of preventive maintenance.

Bike Utilization:  Another way of seeing how often a bike is used based on each bike's id number.

[link to dashboard] https://public.tableau.com/app/profile/preston.clark8164/viz/Book2_16543439952690/Deliverable3Story?publish=yes


SUMMARY

Based on the data obtained for the month of August, most rides were taken by individuals with a subscription Citi Bike’s service.  However, there is no data that details the conditions of having a subscription.  For example, are there costs associated with having a subscription?  Are there other disclosures or benefits for subscribers that we are unaware of?
When we assess the gender of riders in August, we are left not knowing if the “unknown” gender identification was because of incomplete information being gathered or if this is an intentional selection by riders.  An answer to this data point should first be determined then consideration can be given for its use in the new venture.
Future analyses might include determination of starting and ending ride locations to better assess needs and limitations. The below two maps display where bike trips started and ended in August. The size and color of the circles reflects the relative number of trips started and ended at these locations. Based on findings, most trips originate where the highest concentration of residential and commercial properties are located.  While bike trip starts were lower in the less densely packed areas, these same areas saw a higher number of ending trips.

