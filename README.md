#BIKE SHARING ANALYSIS

##OVERVIEW

This project picks up from the idea of entering a partnership to start a bike sharing business in Des Moines, Iowa, modeled after the Citi Bike sharing program in New York City.  I used Tableau as the primary tool for visualizing my proposal for investors.  Extract data was taken from Citi’s bike sharing dataset and downloaded into Tableau.  After analyzing data for the month of August, worksheets were created, and a story was developed to share.  

##RESULTS

For our bike trip analysis, Pandas was first used to change the "tripduration" column in the original dataset from an integer to a datetime datatype in the new dataset.  Using this updated datatype, visualizations were created to:

•	Show the length of time that bikes are checked out for all riders and genders

•	Show the number of bike trips for all riders and genders for each hour of each day of the week

•	Show the number of bike trips for each type of user and gender for each day of the week.

[link to dashboard] https://public.tableau.com/app/profile/preston.clark8164/viz/Book1_16543392268360/Deliverable2Story?publish=yes

![image](https://user-images.githubusercontent.com/100803302/172064380-526289a9-9e51-40fc-9100-93e0e9d8ce6c.png)


Two key data points that stand out among all the assessed data categories are user type and gender.  Although Citi Bike is available for everyone’s use, it does offer a subscription-based service. Among the total rides taken in the month of August, the following visual reveals that 81% of the rides were taken by individuals with a subscription.

![image](https://user-images.githubusercontent.com/100803302/172064396-6a56f87e-b0d3-45b0-8ec3-89d6ca4bb78c.png)

When we assess the number of rides based on gender, we again see a large disparity.  Our data shows that 65% of the total rides were taken by male riders.  However, this does not suggest the remainder of rides were taken by female riders due to the added gender option of “unknown” as shown below.

![image](https://user-images.githubusercontent.com/100803302/172064409-da579b47-0a29-40bc-8a25-d891be3f98ed.png)

An analysis was made on three additional data points with use of worksheets, a dashboard, and a story for visualizations:  August peak hours, bike repairs, and bike utilization.
August Peak Hours: One-third of all rides taken in August occurred between 4 and 8pm.

![image](https://user-images.githubusercontent.com/100803302/172064419-6cb2e88c-6021-4cd8-aac2-e90ff87fe6ef.png)

Bike Repairs:  An id number is associated with each bike in the system. This allows for the strategic rotation of bikes from those in areas with low usage to those in areas of high usage. The id numbers also help with bike upkeep and safety through the scheduling of preventive maintenance.

![image](https://user-images.githubusercontent.com/100803302/172064474-40e27771-227d-492b-a995-65b7428695e0.png)

Bike Utilization:  Another way of seeing how often a bike is used based on each bike's unique id number.

![image](https://user-images.githubusercontent.com/100803302/172064487-4b4d0131-c4a4-4782-b0e2-36e426fe1102.png)

[link to dashboard] https://public.tableau.com/app/profile/preston.clark8164/viz/Book2_16543439952690/Deliverable3Story?publish=yes

##SUMMARY

Based on the data obtained for the month of August, most rides were taken by individuals with a subscription Citi Bike’s service.  However, there is no data that details the conditions of having a subscription.  For example, are there costs associated with having a subscription?  Are there other disclosures or benefits for subscribers that we are unaware of?

When we assess the gender of riders in August, we are left not knowing if the “unknown” gender identification was because of incomplete information being gathered or if this is an intentional selection by riders.  An answer to this data point should first be determined then consideration can be given for its use in the new venture.

Future analyses might include determination of starting and ending ride locations to better assess needs and limitations. The below two maps display where bike trips started and ended in August. The size and color of the circles reflects the relative number of trips started and ended at these locations. Based on findings, most trips originate where the highest concentration of residential and commercial properties are located.  While bike trip starts were lower in the less densely packed areas, these same areas saw a higher number of ending trips.

![image](https://user-images.githubusercontent.com/100803302/172064518-65a7b89b-8022-4f88-8f3c-5642bfb6ce5e.png)
![image](https://user-images.githubusercontent.com/100803302/172064526-6f29e83e-79ae-4a0b-a263-687d83b01ba1.png)


