# ETL_Proyect_2022

ETL is the process that extracts, transforms, and loads data from multiple sources to a data warehouse or other unified data repository.

##### Data selection:

*	**Topic;** 
    - Indian develop trough the years
        - Population grouth
        - Greouth per capital
    - Indian situation of the pandemic
    
*	**Sources;**

    1. Reserve bank of India: 
        - Population, 
            https://m.rbi.org.in/scripts/PublicationsView.aspx?id=20660
    2. Wikipedia:
        - Economic grouth,
            https://en.wikipedia.org/wiki/List_of_Indian_states_and_union_territories_by_GDP_per_capita
    3. PRS Legislative Research: 
        - https://prsindia.org/covid-19/cases
        
    
*   **Aditional info;**
 
    - World Bank: 
        https://www.worldbank.org/en/country/india/overview#3
        
    - Goverment of india:
        https://www.mygov.in/corona-data/covid19-statewise-status
        
    - The new york Times:
        https://www.nytimes.com/interactive/2021/world/india-covid-cases.html
    
    - Estimation of india,china and the world pupulation growth in real time: 
        https://www.indiastateast.com/Home/Popclockflash
        
    - Covid development:
        Sudalairajkumar (User)
        https://www.kaggle.com/sudalairajkumar/covid19-in-india?select=covid_19_india.csv
   
 
    
##### 1.EXTRACTION:

-	Download data information using 2 differnt methods of scraping;

    * **1st Method** - Web Scraping with Selenium and webdriver_manager:
    
        - 	Reserve bank of India 
        
    *	**2nd Method** - Web Scraping Pandas: 
    
        -	Wikipedia
        - PRS Legislative Research
  

##### Exploratory analysis cleaning data;

-	Cleaning the data using different libraries and python methods:
  * Regex
  * Pandas
  * Python

-	Creation of a Data frame using Pandas library.

* Planification of the links between the tables.
    *	1st Table
        -	Indian States.(PK)
    *	2nd Table
        -	Indian States.(PK)
    * 3rd Table
        -	Indian States.(PK)

##### 2.TRANSFORMATION:

- Fix the different dataframes to be able to merge them.
- Test if the identification values (Indian States) coincide by the megre Pandas method.


##### 3.LOAD:

-	Assign the links between the tables.   
-	Prepare the Tables to upload them to the SQL data base.
-	From jupyter notebook and python, upload the information to the SQL database, in different tables.
- With a SQL method, join the tables to create a database in order to check that the PK are correctly set.


