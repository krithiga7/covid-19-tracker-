# covid-19-tracker-
OBJECTIVE: 
           Covid 19 tracker is an website used for tracking and analysing the cases and vaccinated people in india

Users of the System: 
1.ADMIN
2.CUSTOMER

FUNCTIONAL REQUIREMENTS:           
1. Additional information on covid 19 IS given in read more.
2.Each side navigation icon has its specific contents.
3.Vaccinated and non-vaccinated are also mentioned with the percentage(%).
4.Vaccine: 1st  and 2nd dose are vaccinated by 54.9% of the people in india currently
5.Affected people of covid 19 are differentiated by active ,confirmed , deceased, recovered.
6.Total number of people vaccinated doses are also administrated
7.The tabular column referred here is mentioned the number of people affected by covid 19 are differentiated by state wise  and differentiated  by active,conformed, deceased,recovered.
8.Indian map mentioned here indicates the states with coloured effects mention the covid affected and delivers contents of states.
9.The site shows the increase and decrease in the economic changes during covid period.
 
 
OUTPUT/ POST CONDITION: 
Covid  19 tracker with real time data and easy to access website

NON-FUNCTIONAL REQUIREMENTS:
1.Security 
2.Secured website  
3.Covid 19 tracker website may not access any private and sensitive data

PERFORMANCE:
1.Peak Load Performance (durng covid period)
2.Admin application<2sec
3.Non peak load performance
4.admin application<2sec

AVAILABILITY:
       99.99 % Availability 

STANDARD FEATURES:
       1.Scalability 
       2.Maintainability 
       3.Usability 
       4.Availability 
       5.Failover 

LOGGING AND AUDITING:
 The system should support logging(app/web/DB) & auditing at all levels. 

CLOUD:
 The Solution should be made Cloud-ready and should have a minimum impact when moving away to Cloud infrastructure. 
 
Browser Compatible 
All latest browsers. 
TECHNOLOGY STACK:
1.HTML
2.CSS
3.Java Script
WEBSITE ASSUMPTIONS: 
1.The website is first loaded.
2.The real time data with  case conformed  data is displayed .
3.Navigation pane is on left top corner containing the other information are displayed. 
4.Pictorial representation is dsplayed at the bottom of website .
5 queries box is inserted at the bottom right corner of the website.

VALIDATIONS: 
1.   Website doesn't require any validation

PROJECT TASKS: 
API Endpoints 
USER:
Action Url Method Response.
1. get in website.
2. Signup/signup POST true/false.
3. insert date and time.
ADMIN:
Action URL Method Response.
1.get all data/admin GET array of data.
2.add records/admin/add record POST record added.
3.record edit/admin/record edit/{id}GET all given data of particular id.
FRONTEND:  
PUBLIC: 

1.   Dashboard / Home: Design a home page component named (Name the component  HomePage for react app. Once the component is created in react app, name the jsx file as same as component name i.e HomePage.jsx file) that has the navigation bar and lists all the available products as grid elements with appropriate filter options. 

 Ids: 
userNavigation bar \

BACKEND: 
Class and Method description.

MODEL LAYERS:
1.User Model:This class store the user type and date information.
a.Attributes:
             1.user name: string
             2.date:int
 
CONTROL LAYER:
2.Singnup Controller:This class control the user signup
a.Methods:
1. SaveUser(UserModel user):This method helps to store users in the database and return true or false based on the database transactions.  






                   

 
 
