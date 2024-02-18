### <p align="center"/> SKILL-HARVEST DATA ANALYSIS BOOTCAMP </p>
##### INTRODUCTION
This respository is an archive that contains the learning journals I kept while attending SkillHarvest Academy's data analysis training boot camp. Below are a curated list of the bootcamp contenets:
   
    1. Spreadsheets Fundamentals (Microsoft Excel & Google Sheets) -
    2. GitHub Fundamentals -
    3. PowerQuery - 
    4. Introduction to PowerBi - 
#### 1.0 SPREADSHEETS FUNDAMENTALS
Spreadsheets are powerful tools used for organizing, analyzing, and presenting data in a structured format. They consist of rows and colums, formimg a grid where data can be entered, manipulated, and calculated.

They play a crucial role in various aspects of business, education and personal organization. Hence, understanding their features and capabilities can significantly enhance productivity and decison-making processes.

 - **Major Types:** Microsoft Excel & Google sheet.
 - **Key features:** Organization, Calculations, Dta analysis, Visualization & Collaborations.
 - **Common uses:** Finalcial management, Data tracking, Analysis & Reporting, and Decision making.
 - **Differences:**


           |Feature        |Microsoft Excel                 |Google sheets     |
           |---------------| ------------| ---------| 
           |Ownership      |Requires installation & licenses|Cloud-based accessible online   |
           |Cost|Paid software, licenses required    | Free basic features, paid options  |
           |Functionalities|Advanced data analysis tools |Basic to intermediate capabilities  |
           |Collaboration  |Limited collaboration features|Robust real-time collaboration capabilities|



#### 2.0 GITHUB FUNDAMENTALS
A. Here, we were introduced to Github as a/an:
  - Version control & Collaboration Tool
  - Open Source
  - Learning resources
B. How to create a Github account.
C. How to create a repository.
D. How to develop a Github project readme file.

#### 3.0 POWER QUERY
Here, we used **SkillHarvest_Stationary_Supplies.CSV** to demostrate the use cases of some power query functions. Below is an excerpt from the dataset.

### <p align="center"/> Excerpt From The Datasheet </p>
#### 3.1 POWER QUERY EXERCISE

   1. Show sales rep whose items are Ppen set and binders.
   2. Show sales of binder items and pencil in 2015.
   3. Show sales in Central and East region in 2014.
   4. Show sales in August and September 2014.
   5. Show sales of items that start with Pen, include their region, sales rep and year.
   6. Show sales of items that end with 'SK', include their region, sales rep and year.      
 
### <p align="center"/> TASK ONE SOLUTION </P>
PowerQuery
=QUERY (A1:H44, "SELECT B, C WHERE C= 'Pen Set' OR C='Binder'", 1)


### <p align="center"/> TASK TWO SOLUTION </P>
PowerQuery
=QUERY (A1:H44, SELECT C, H WHERE (C='Binder' OR C='Pencil') AND F='2015'",1)

