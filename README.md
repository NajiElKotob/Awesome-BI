# Awesome BI
Awesome Microsoft Business Intelligence Resources

=== Beta Awesome List ===

```sh

```

## Table of contents

* [BI Heroes at YouTube](#r-heroes-at-youtube)
* [Essential Concepts](#essential-concepts)
* [Videos](#videos)
* [Tutorials :star2:](#tutorials)
* [Books](#books)
* [Groups and Communities](#groups-and-communities)
* [Tools](#tools)
* [Learning](#learning)
* [Sample Databases](#sample-databases)
* [Datasets](#datasets)
* [The Beauty of Data](#the-beauty-of-data)
* [Data Security and Protection](#data-security-and-protection)
* [Exams and Certificates](#exams-and-certificates)
* [Competitive Analysis](#competitive-analysis)
* [Summits and Conferences](#summits-and-conferences)
* [Third-party Resources](#third-party-resources)

## Official Websites
* [Data Platform](http://www.microsoft.com/data) - Microsoft
* [Search product lifecycle](https://support.microsoft.com/en-us/lifecycle/search)

## BI Heroes at YouTube
> sorted alphabetically :heart:
* [Big Data Analytics with HDInsight: Hadoop on Azure](https://www.youtube.com/watch?v=-Qx7AIV0dqY) - ~5 hours
* [Statistics for Data Science (Beginner)](https://www.youtube.com/watch?v=74oUwKezFho) ~8 hour

## Blogs
* [SQL Server BI](https://sqlserverbi.blog/) - Paul Turley 
* [Microsoft SQL Server Versions List](https://sqlserverbuilds.blogspot.com/) - This unofficial build chart lists all of the known Service Packs (SP), Cumulative Updates (CU), patches, hotfixes and other builds of MS SQL Server.

## Groups and Communities
* [LinkedIn Groups](https://github.com/NajiElKotob/Awesome-Power-BI/blob/master/README.md#groups)

## Books
* In Progress...


## Essential Concepts

### BI Terms and Concepts
* [Glossary](https://github.com/NajiElKotob/Awesome-BI/blob/master/Glossary.md)
* [Star Schema](https://docs.infor.com/help_lawson_cloudsuite_10.1/index.jsp?topic=%2Fcom.lawson.help.reporting%2Fcom.lawson.help.bpwag-w_10.4.0%2FL55461185818015.html) - In the data warehouse database, data is arranged into hierarchal groups called dimensions and into facts and aggregate facts. The combination of facts and dimensions is called a star schema.
* [Business Intelligence Maturity Model](https://medium.com/@christopher.shayan/business-intelligence-maturity-model-ff87f360d45c)
* [Data governance and the death of schema on read](https://www.oreilly.com/ideas/data-governance-and-the-death-of-schema-on-read)
* [Nine Laws of Data Mining](http://khabaza.codimension.net/index_files/9laws.htm) - Tom Khabaza

### CRISP-DM
* [CRISP-DM](https://www.sv-europe.com/crisp-dm-methodology/) - Cross-Industry Standard Process for Data Mining
* [CRISP-DM 1.0 (PDF)](https://www.the-modeling-agency.com/crisp-dm.pdf) - Step-by-step data mining guide

### Kimball Group
* [Kimball design tips](https://www.kimballgroup.com/category/before-diving-in)
* [Kimball Techniques](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/kimball-techniques)
* [Data Warehouse and Business Intelligence Toolkit Books](https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/books)

     
## Enterprise Information Management (EIM)
Enterprise Information Management (EIM) can best be defined as a set of technologies, processes, disciplines and practices used to manage an organization’s data and content as an enterprise asset. Managing information in an enterprise typically involves integrating data from across the enterprise and beyond, cleansing the data, matching the data to remove any duplicates, standardizing the data, enriching the data, making the data conform to legal and compliance requirements, and then storing the data in a centralized location with all the necessary security settings.
* [Enterprise Information Management (EIM): Bringing Together SSIS, DQS, and MDS (Video)](https://channel9.msdn.com/Events/TechEd/Europe/2012/DBI310) - Channel9
* [Enterprise Information Management](https://www.washington.edu/uwit/eim/) - University of Washington


### ETL
* [SSIS - SQL Server Integration Services](https://docs.microsoft.com/en-us/sql/integration-services/sql-server-integration-services) - Microsoft Integration Services is a platform for building enterprise-level data integration and data transformations solutions. Use Integration Services to solve complex business problems by copying or downloading files, loading data warehouses, cleansing and mining data, and managing SQL Server objects and data.

### MDM


### DQM



##  Business Intelligence Semantic Model (BISM)
* Semantic Layer 
     * [What is Semantic Layer?](https://www.jinfonet.com/resources/bi-defined/semantic-layer/) - A semantic layer acts as an intermediary between the business user and corporate data. Data is represented as objects named as common business terms for business users to navigate. This allows business users to work with corporate data without needing to know all the finer technical details. Many reporting tools use a semantic layer to allow business users to create their own ad hoc reports
     * [Making Sense of the Semantic Layer](https://www.kimballgroup.com/2013/08/design-tip-158-making-sense-of-the-semantic-layer)
     * [Understanding the SQL Server 2012 BI Semantic Model (BISM)](https://www.mssqltips.com/sqlservertip/2818/understanding-the-sql-server-2012-bi-semantic-model-bism/)

### Videos
* [Analysis Services What is the Difference between Tabular and Multidimensional Models](https://www.youtube.com/watch?v=Y0hWQh7EJME)
* [Optimizing multi-billion row tables in Tabular](https://www.sqlbi.com/tv/optimizing-multi-billion-row-tables-in-tabular-sqlbits-2017/) - SQLBI
* [DirectQuery in Analysis Services - Best practices, performance, use cases](https://www.youtube.com/watch?v=gSC5ghcGwGk) - DirectQuery is a feature of Analysis Services that transforms a Tabular model in a semantic layer on top of a relational database, transforming any MDX or DAX query in a real-time request to the underlying relational engine using the SQL language.
    * [DirectQuery in SQL Server 2016 Analysis Services whitepaper](http://download.microsoft.com/download/F/6/F/F6FBC1FC-F956-49A1-80CD-2941C3B6E417/DirectQuery%20in%20Analysis%20Services%20-%20Whitepaper.pdf)
    
### Tutorials
* [Analysis Services tutorials](https://docs.microsoft.com/en-us/sql/analysis-services/analysis-services-tutorials-ssas) - Microsoft
    * [Tabular modeling - Adventure Works Internet Sales Tutorial](https://docs.microsoft.com/en-us/sql/analysis-services/tutorial-tabular-1400/as-adventure-works-tutorial)
        * [Import data by using a native query](https://docs.microsoft.com/en-us/sql/analysis-services/tabular-models/ssas-import-query)
        * [Create a calculated table](https://docs.microsoft.com/en-us/sql/analysis-services/tabular-models/create-a-calculated-table-ssas-tabular)
        * [Bi-directional cross filters in tabular models](https://docs.microsoft.com/en-us/sql/analysis-services/tabular-models/bi-directional-cross-filters-tabular-models-analysis-services)
        * [Relationships](https://docs.microsoft.com/en-us/sql/analysis-services/tabular-models/relationships-ssas-tabular)
        * [Translations in Tabular models](https://docs.microsoft.com/en-us/sql/analysis-services/tabular-models/translations-in-tabular-models-analysis-services)
        * [Tabular model solution deployment](https://docs.microsoft.com/en-us/sql/analysis-services/tabular-models/tabular-model-solution-deployment-ssas-tabular)
        * [How to automate SSAS tabular model processing in SQL Server 2016](https://www.sqlshack.com/how-to-automate-ssas-tabular-model-processing-in-sql-server-2016)
        * [Enable DirectQuery mode in SSDT](https://docs.microsoft.com/en-us/sql/analysis-services/tabular-models/enable-directquery-mode-in-ssdt)
    * [Multidimensional modeling - Adventure Works Tutorial](https://docs.microsoft.com/en-us/sql/analysis-services/multidimensional-tutorial/multidimensional-modeling-adventure-works-tutorial)
        * [Set Impersonation Options](https://docs.microsoft.com/en-us/sql/analysis-services/multidimensional-models/set-impersonation-options-ssas-multidimensional)


## Tools
* [SSDT - SQL Server Data Tools](https://docs.microsoft.com/en-us/sql/ssdt/download-sql-server-data-tools-ssdt)
* [SSMS - SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms)
* [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download)

### Utilities
* [SqlQueryStress](https://github.com/ErikEJ/SqlQueryStress)
   * [How to Fake Load Tests with SQLQueryStress](https://www.brentozar.com/archive/2015/05/how-to-fake-load-tests-with-sqlquerystress/)
* [SQL-Load-Generator](https://github.com/cankaya07/SQL-Load-Generator)

## Learning
* In Progress...

## Sample Databases and Datasets
### Sample Databases
* [WideWorldImporters](https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/wide-world-importers)
    * [Design a multidimensional business intelligence (BI) semantic model](https://www.microsoftpressstore.com/articles/article.aspx?p=2812063)
    * [Data Dictionaries and ER Diagram - WideWorldImportersDW](https://dataedo.com/samples/html/WideWorldImportersDW/)
* [AdventureWorks](https://github.com/microsoft/sql-server-samples/releases/tag/adventureworks)
    * [AdventureWorks](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorks2017.bak)
    * [AdventureWorksDW](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2017.bak)
    * [AdventureWorksLT](https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksLT2017.bak)

### Datasets
* [Awesome Datasets](https://github.com/NajiElKotob/Awesome-Datasets)


## The Beauty of Data
* [How the Recession Reshaped the Economy, in 255 Charts](https://www.nytimes.com/interactive/2014/06/05/upshot/how-the-recession-reshaped-the-economy-in-255-charts.html) - Jermy Ashkenas and Alicia parlapiano
* [Information is Beautiful](https://informationisbeautiful.net/)

## Data Security and Protection
* [Cyber Security Hub - Data](https://www.cshub.com/data) - Data misuse or mismanagement is a top cause of today's breaches. Cyber Security Hub regularly touches upon data-driven stories
* [World's Biggest Data Breaches & Hacks](https://informationisbeautiful.net/visualizations/worlds-biggest-data-breaches-hacks/) - informationisbeautiful.net

## Exams and Certificates
### Exams
* [Querying Data with Transact-SQL](https://www.microsoft.com/en-us/learning/exam-70-761.aspx) (70-761)
* [Developing SQL Databases](https://www.microsoft.com/en-us/learning/exam-70-762.aspx) (70-762)
* [Administering a SQL Database Infrastructure](https://www.microsoft.com/en-us/learning/exam-70-764.aspx) (70-764)
* [Provisioning SQL Databases](https://www.microsoft.com/en-us/learning/exam-70-765.aspx) (70-765)
* [Implementing a Data Warehouse using SQL](https://www.microsoft.com/en-us/learning/exam-70-767.aspx) (70-767)
* [Developing SQL Data Models](https://www.microsoft.com/en-us/learning/exam-70-768.aspx) (70-768)

### Certificates
* [MCSE: Data Management and Analytics](https://www.microsoft.com/en-us/learning/mcse-data-management-analytics.aspx)
* [MCSA: BI Reporting](https://www.microsoft.com/en-us/learning/mcsa-bi-reporting.aspx)
* [MCSA: SQL 2016 BI Development](https://www.microsoft.com/en-us/learning/mcsa-sql2016-business-intelligence-certification.aspx) 


## Summits and Conferences
* [2019 Business Intelligence Summit](https://www.conferenz.co.nz/events/2019-business-intelligence-summit)

<br/>[:top:](#table-of-contents)

## Third-Party Resources
* [Presto - Distributed SQL Query Engine for Big Data](https://prestodb.github.io/) - Presto is an open source distributed SQL query engine for running interactive analytic queries against data sources of all sizes ranging from gigabytes to petabytes.

> Suggest more Power BI Resources 
