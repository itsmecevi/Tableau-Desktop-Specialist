# Tableau-Desktop-Specialist



## The Power of data visualization 

* [Hans Rosling](https://www.youtube.com/watch?v=jbkSRLYSojo)
* [Gapminder](https://www.gapminder.org/)

### What is data visualization?

* Data visualization is the graphical representation of information and data.
* By using visual elements like charts, graphs, and maps, data **visualization tools** provide an accessible way to see and understand trends, outliers, and patterns in data.
* The best data visualization blogs, site, and news to follow

    * 1 -[Storytelling with Data](http://www.storytellingwithdata.com/)
    * 2 -[Information is Beautiful](https://informationisbeautiful.net/)
    * 3 -[Flowing Data](https://flowingdata.com/)
    * 4 -[Visualising Data](https://www.visualisingdata.com/)
    * 5 -[Junk Charts](https://junkcharts.typepad.com/junk_charts/)
    * 6 -[The Pudding](https://pudding.cool/)
    * 7 -[The Atlas](https://theatlas.com/)
    * 8 -[Graphic Detail](https://www.economist.com/graphic-detail/)
    * 9 -[US Census](https://www.census.gov/dataviz/) and [FEMA](https://www.fema.gov/data-visualization)
    * 10 -[Tableau Blog](https://www.tableau.com/about/blog)
    * 11 -[FiveThirtyEight](https://fivethirtyeight.com/)
    * 12 -[Viz.WTF ](https://viz.wtf/)
    * 13 -[r/DataIsUgly](https://www.reddit.com/r/dataisugly/)


### Why data visualization matters?

![WDVM](https://user-images.githubusercontent.com/27078712/72880236-11d3b380-3d31-11ea-82a2-7be5c6087ea2.PNG)

* Data Visualization Goals : 

     * Data Exploration — find the unknown
     * Data Analysis — check hypotheses
     * Presentation — communicate and disseminate
 
 * The Five-Step Model :
 
     * Target
     * Data Wrangling
     * Design
     * Implement
     * Evaluate
  
![5stepdesign](https://user-images.githubusercontent.com/27078712/72888440-266b7800-3d40-11ea-8668-db66477a76fb.png)

     
 * Issues :
 
     * Domain situation 
     * Data/task abstraction 
     * Visual encoding/interaction
     * Algorithm
     
 * SOLUTION for the ISSUES :
 
     * Observational Studies (“Think Aloud”)
     * Expert Interviews (aka Design Critiques)
     * Focus Groups
     
 * Rules of Thumb : **Edward Tufte Rules**

## Business Intelligence 101 

* Business Intelligence <-> Visualization ? TRUE or FALS
* Business Intelligence Vs. Analytics ?
* BI Process :

![biprocess](https://user-images.githubusercontent.com/27078712/72890846-6a14b080-3d45-11ea-9b54-aafa268acd14.jpg)

* Hands on [~~Tableau~~] Business Intelligence : [CLICK HERE](https://docs.google.com/presentation/d/1a1-lRjjwSYBv4IUw5aLWeRr7x9JESrR8qkHR-Ug1u_4/edit?usp=sharing)



## Introduction to Tableau

* Tableau vs Excel : Googling!

* Tableau products :

     * Tableau Prep.
     * Tableau Desktop
     * Tableau Public
     * Tableau Online
     * Tableau Server
     * Tableau Reader
     
* Tableau SWOT analysis : [CLICK HERE](https://prezi.com/8p5tcxkfryb1/tableau-software-swot-analysis/)
* Tableau GUI (Graphical User Interface) : Demo Tableau GUI



## Connecting to data

* Live connection :
     * When you have a fast database
     * When you need up-to-the minute data (real-time)
* Extract connection (in memory) :
     * When your database is too slow for interactive analytics
     * When you need to take load off a transactional database (size of the data)
     * When you need to be offline (without internet connections)
* Connecting to Excel file : [Data: Global Superstore](https://github.com/itsmecevi/global-superstore/blob/master/Global%20Superstore.xlsx)
* Connecting to CSV file : [Data: Insurance Portfolio ](https://support.spatialkey.com/spatialkey-sample-csv-data/)
* Connecting to Google Sheets : [Data Google Sheets](https://docs.google.com/spreadsheets/d/1wtyaUAeN2ztSfAo8SK0FtZ0n85K0YBPo_ZcH6Hy54Nw/edit#gid=0)
* Connecting to PDFs : [Data: Amazon Stock Prices](https://public.tableau.com/s/sites/default/files/media/amzn_stock.pdf)
* **50+ different data sources**


## Preparing data

* Data connections :

     * Left Join
     * Right Join
     * Inner Join
     * Full Outer Join
     * Union (vertical connection)
     * Blend (horizontal connection)
     
* Tableau data types : 6 different data types
     * Number
     * String
     * Date
     * Geographics
     * Boolean (TRUE FALSE)
     * Data & Time

* The Data Interpreter : [Data: CO2 emissions ](https://data.worldbank.org/indicator/EN.ATM.CO2E.PC)
* Pivoting your Data : [Data: CO2 emissions ](https://data.worldbank.org/indicator/EN.ATM.CO2E.PC)
* Splitting your Data: [Data: CO2 emissions ](https://data.worldbank.org/indicator/EN.ATM.CO2E.PC)
* Manage data properties : [Data: CO2 emissions ](https://data.worldbank.org/indicator/EN.ATM.CO2E.PC)

     * Rename a data field: 
     * Assign an alias to a data value 
     * Assign a geographic role to a data field   
     * Change data type for a data field (number, date, string, boolean, etc.) 
     
 ## Understanding Tableau Concepts 
 
 * Dimensions and measures
 * Discrete and continuous fields : 
 
     * Blue color: discret, qualitative data (string, geographics, date, date & time, boolean). If added qualitative data, then they are        separate the graphs.
     * Green color: continuous, quantitative data, number, aggregation (sum, avg, etc).-> If added quantitative data, then they aren’t          separate the graphs.
  * Aggregation
  
 
 ## Exploring data
 
     
 * Organize data : [Data: Global Superstore](https://github.com/itsmecevi/global-superstore/blob/master/Global%20Superstore.xlsx)
 
     * Create a visual group
     * Create a group using labels
     * Create a set
     * Organize dimensions into a hierarchy
 
 * Worksheet Interface (GUI)
 
 
 * Managing Metadata :
 
     * How to Hide Unhide fields
     * How to Rename fields
     * How to create and delete different hierarchies
     * How to create and remove different folders
     
 * Create basic charts : [Data: Global Superstore](https://github.com/itsmecevi/global-superstore/blob/master/Global%20Superstore.xlsx)
 
     * Bar chart
     * Line chart
     * Scatterplot
     * Word Maps
     * Line Charts
     * Buble Charts
     * Tree Maps
     * Funnel Charts
     * Waterfall Charts
     * A map using geographic data (Longitude and Latitude)
     * Combined axis chart
     * Dual axis chart
     * Stacked bar chart
     * A chart to show specific values (crosstab, highlight table)
     * **Tableau Supports 24 Different Charts**
 
 
 ## Analyzing data
 
 * Apply filters : [Data: Global Superstore](https://github.com/itsmecevi/global-superstore/blob/master/Global%20Superstore.xlsx)
 
     * Filters Shelf
     * Date Filters
     * Interactive Filters
     * Adv Interactive Filters
     * Ways To Filter : 
     
          * Filter Shelf
          * Interactive Filter by show filters
          * Headers with keep only option
          * Legends
          
     * Add a filter to the view
     * Add a context filter
     * Add a date filter
     * Format Filters
     
  * Apply analytics to a worksheet :
  
     * Add a manual or a computed sort
     * Add a reference line or trend line
     * Use a table calculation
     * Use bins and histograms
     * Create a calculated field (e.g. string, date,
       simple arithmetic)
     * Add a parameter
     
  
  
  

