# Tableau-Desktop-Specialist

<p>I will display &#1F6E0;</p> Cevi Herdian -> [itsmecevi.github.io](https://itsmecevi.github.io/) 

Slack Instant Messaging -> [Click Here](https://join.slack.com/t/so-hotworkspace/shared_invite/enQtOTUwOTYyMDEwMjQ2LTQ3M2M4Yjk4MzgyOTk0ZmNjMmNlZTM3N2YzYjdmN2U0OTMxZjljNDA5OGFkYzlhYTQ4ZDBhY2IwZmZjNWU3ODc)

Tableau Public -> [Click Here](https://public.tableau.com/en-us/s/)

## 0-What is The MAIN Purpose of the Technology Courses ?

## 1-The Power of Data Visualization 

* [Hans Rosling](https://www.youtube.com/watch?v=jbkSRLYSojo)
* [Gapminder](https://www.gapminder.org/)

### 1a-What is Data Visualization?

<!--* Data visualization is the graphical representation of information and data. -->
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


### 1b-Why data visualization matters?

![WDVM](https://user-images.githubusercontent.com/27078712/72880236-11d3b380-3d31-11ea-82a2-7be5c6087ea2.PNG)

* Data Visualization Goals : 

     * Data Exploration — find the unknown
     * Data Analysis — check hypotheses
     * Presentation — communicate and disseminate (share function->infographic)
 
 * The Five-Step Model :
 
     * Target
     * Data Preparation
     * Design
     * Implement
     * Evaluate
  
![5stepdesign](https://user-images.githubusercontent.com/27078712/72888440-266b7800-3d40-11ea-8668-db66477a76fb.png)

Picture link: https://bit.ly/3byKYeD

     
 * Issues :
 
     * Domain situation 
     * Data
     * Visual encoding (D3, Tableau, Power BI, etc)
     * Algorithm
     
 * SOLUTION for the ISSUES :
 
     * Observational Studies (“Think Aloud”)
     * Expert Interviews (aka Design Critiques)
     * Focus Groups
     * ALL: BENCHMARKING
     
 * [Visual References](https://github.com/itsmecevi/visualreferences/blob/master/VisualReferences-SQLBI.pdf)
     
 * Rules of Thumb : **Edward Tufte Rules**

## 2-Business Intelligence 101 

* What is Business Intelligence ? 
* Business Intelligence Vs. Analytics ?
* Business Intelligence Vs. Database Engineer ?
* Business Intelligence Vs. Big Data ? 
* Business Intelligence Vs. Data Science ?
* Business Intelligence Vs. Data Engineering ?
* Business Intelligence <-> Visualization ? TRUE or FALSE
* Business Intelligence == Visualization ? TRUE or FALSE
* Business Intelligence -> Visualization ? TRUE or FALSE
* Business Intelligence <- Visualization ? TRUE or FALSE
* BI Process : Data sources-> ETL1-> Database-> ETL2-> Datawarehouse-> Analytics-> KPI (Key Performance Indicator)

![biprocess](https://user-images.githubusercontent.com/27078712/72890846-6a14b080-3d45-11ea-9b54-aafa268acd14.jpg)

Picture link: https://bit.ly/2HmzMnz

* Hands on [~~Tableau~~] Business Intelligence : [CLICK HERE](https://docs.google.com/presentation/d/1a1-lRjjwSYBv4IUw5aLWeRr7x9JESrR8qkHR-Ug1u_4/edit?usp=sharing)

## 3-KPI (Key Performance Indicators)

* What is KPI ?
* Each business and department have different tasks and goals-> ?
* There are five main types of KPIs: 
     * Business KPI (Relative Market Share, Revenue Growth Rate, Churn Rate)
     * Financial KPI (Net Profit, Sales Growth, Budget Variance)
     * Sales KPI (Customer Lifetime Value, Lead-to-Sale %, Sales Opportunities)
     * Marketing KPI (Leads, Cost of Customer Acquisition, Lead-to-Customer Ratio)
     * Project Management KPI (Time spent, Return on Investment, Planned Budget vs Actual Budget)
 * https://kpidashboards.com/kpi/department/customer-service/
     * By Industry 
     * By Department 
 * https://www.sisense.com/dashboard-examples/
     * Business Goal 
     * Role-Specific (CEO, CFO, Digital Marketing Manager, etc) 


## 4-Introduction to Tableau

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




## 5-Connecting to data

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



## 6-Preparing data

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
     
     
## 7-Understanding Tableau Concepts 
 
 * Dimensions and measures
 * Discrete and continuous fields : 
 
     * Blue color: discret, qualitative data (string, geographics, date, date & time, boolean). If added qualitative data, then they are        separate the graphs.
     * Green color: continuous, quantitative data, number, aggregation (sum, avg, etc).-> If added quantitative data, then they aren’t          separate the graphs.
  * Aggregation
   



## 8-Exploring data
 
     
 * Organize data : [Data: Global Superstore](https://github.com/itsmecevi/global-superstore/blob/master/Global%20Superstore.xlsx)
 
     * Create a visual group
     * Create a group using labels
     * Create a set
     * Organize dimensions into a hierarchy
 
 * Worksheet Interface (GUI) :
 
 ![gui](https://user-images.githubusercontent.com/27078712/72997332-cb647e80-3e2e-11ea-9f9d-cbc238470c7c.png)
 
 Picture link: https://help.tableau.com/current/pro/desktop/en-us/calculations_calculatedfields_lod_overview.htm

 
 
 * Managing Metadata :
 
     * How to Hide Unhide fields
     * How to Rename fields
     * How to create and delete different hierarchies
     * How to create and remove different folders
     
 * Create basic charts : [Data: Global Superstore](https://github.com/itsmecevi/global-superstore/blob/master/Global%20Superstore.xlsx)
 
     * Bar chart
     * Pie chart
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
 
 
## 9-Analyzing data
 
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

## 10-Tableau Use Case

### 10a-By Industry

### 10b-By Department

### 10c-By Business Goal

### 10d-By Role Specific


 
## 11-Extras 

### Change log update

* 23.01.2020
* 24.01.2020
* 11.02.2020
* 12.02.2020
* 13.02.2020

### References
* [Tableau](tableau.com)
* [Guru99: Tableau](https://www.guru99.com/)
* [Tutorialspoint: Tableau](https://www.tutorialspoint.com/index.htm)
* [Tableau Learning Path: AnalyticsVidhya](https://www.analyticsvidhya.com/myfeed/?utm-source=blog&utm-medium=top-icon%2F)
* [Jumpstart Tableau](https://www.amazon.com/Jumpstart-Tableau-Step-Step-Visualization/dp/1484219333)
* [Pro Tableau](https://www.amazon.com/Pro-Tableau-Step-Step-Guide/dp/1484223519/ref=sr_1_1?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=Pro+tableau&qid=1570446674&s=books&sr=1-1)
* [Rapid Graphs with Tableau](https://www.ebay.com/itm/Rapid-Graphs-with-Tableau-8-The-Original-Guide-for-the-Accidental-An-/273689089070)
* [Tableau Cookbook](https://www.amazon.com/Tableau-10-Business-Intelligence-Cookbook/dp/1786465639/ref=sr_1_2?__mk_de_DE=%C3%85M%C3%85%C5%BD%C3%95%C3%91&keywords=tableau+cookbook&qid=1570460189&s=books&sr=1-2)
* [Tableau Your Data!](https://www.amazon.com/Tableau-Your-Data-Analysis-Software/dp/1118612043)
* [Tableau Dashboard Cookbook](https://www.amazon.com/Tableau-Dashboard-Cookbook-Jen-Stirrup/dp/1782177906)
* [Tableau Visual Guidebook](https://www.tableau.com/visual-guidebook-flowingdata)
* [Tableau Whitepapers](https://www.tableau.com/learn/whitepapers)
* [Tableau Public Resources](https://public.tableau.com/en-us/s/resources)
* [Online Analytical Processing](https://olap.com/)
* [Datawarehouse for You](https://www.datawarehouse4u.info/)
* [Pinterest](https://www.pinterest.com/pin/96897829462585916/)
* [Roosboard](https://roosboard.com/blog/what-diffrence-between-self-and-traditional-BI.html)
* [EduCBA](https://www.educba.com/excel-vs-tableau/)
* [Dimensions and Measures, Blue and Green](https://help.tableau.com/current/pro/desktop/en-us/datafields_typesandroles.htm)
* [Open Data Soft](https://www.opendatasoft.com/)
* [Datapine](https://www.datapine.com)
* [Evolytics](https://www.evolytics.com)
* [Grazitti](https://www.grazitti.com)
* [Tableau Community](https://community.tableau.com/welcome)
* [Slideshare](https://www.slideshare.net)
* [Izenda](izenda.com)
* [Gaston Sanchez](https://www.gastonsanchez.com/)
* [Evolvetech](http://www.evolvetech.ie/business-intelligence/)
* [Medium](https://miro.medium.com/max/2864/0*F_gTZfV5EtXm6UVq)
* [Quora](https://www.quora.com/How-does-self-service-BI-differ-from-traditional-BI)
* [Tactical Edge](http://www.tacticaledge.us/services/software-development/analytics-and-business-intelligence/)
* [Digite](https://www.digite.com/blog/waterfall-to-agile-with-kanban/)
* [Kdnuggets](https://www.kdnuggets.com/2017/01/four-problems-crisp-dm-fix.html)
* [Researchgate](https://www.researchgate.net/figure/General-architecture-of-the-business-intelligence-process-adapted-from-34_fig1_335781756)
* [Tableau-Wiki-Cevi](https://trello.com/b/IR0xqNMM/tableau-wiki-cevi)

  
