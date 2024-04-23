# Data-Analytics---Week-1
# CHAPTER 1

What is Data Analytics?
Analytics is at the heart of modern business. Virtually every organization collects large quantities of data about its customers, products, employees, and service offerings. Managers naturally seek to analyze that data and harness the information it contains to improve the efficiency, effectiveness, and profitability of their work.

The ultimate role of a data analyst is to transform raw data into actionable insights that guide decision-making processes within an organization. This involves several key responsibilities and skills.

# Data Collection and Preparation:
Sourcing data from various channels, including databases, spreadsheets, and external sources.
Cleaning and organizing the data to ensure it is accurate, consistent, and ready for analysis.

# Data Analysis:
Employing statistical methods, machine learning techniques, or other analytic tools to interpret data.
Identifying trends, patterns, and correlations that might not be immediately obvious.

# Data Visualization and Storytelling:
Creating visual representations of the data, such as charts, graphs, and dashboards, to make complex information easily understandable.
Articulating findings in a compelling narrative to communicate the significance of the data to stakeholders.

# Decision Support:
Making recommendations based on data-driven insights to help guide business decisions.
Providing context around the data, including potential implications and future trends.

# Collaboration and Communication:
Working closely with other departments, such as marketing, finance, and operations, to understand their data needs and provide insights.
Effectively communicating complex data findings in a clear and concise manner to non-technical stakeholders.

# Continuous Learning and Adaptation:
Keeping up-to-date with the latest industry trends, tools, and technologies in data analysis.
Adapting to new types of data and analytical methods as the organization's needs evolve.

# Three pillars of Analytics
 Analytics is made possible by modern:
 -Data
 -Storage
 -Computing capabilities.

 # The analytics process

 - Data Acquisition
 - Cleaning and Manipulation
 - Analysis
 - Visualization
 - Reporting and Communication

   # Analytics Techniques
   - Descriptive Analytics
   - Descriptive Analytics
   - Presciptive Analytics
  
   # Machine Learning, Artificial Intelligence and Deep Learning

- Machine learning uses algorithms to discover knowledge in your datasets that you can then apply to help you make informed decisions about the future. That is true regardless of the specific subject matter expertise where you're working, as machine learning has applications across a wide variety of fields. 

For example, here are some cases where machine learning commonly adds value:

- Segmenting customers and determining the marketing messages that will appeal to different customer groups.
- Discovering anomalies in system and application logs that may be indicative of a cybersecurity incident.
- Forecasting product sales based on market and environmental conditions.
- Recommending the next movie that a customer might wish to watch based on their past activity and the preferences of similar customers.
- Setting prices for hotel rooms far in advance based on forecasted demand.

Artificial intelligence (AI) includes any type of technique where you are attempting to get a computer system to imitate human behavior. As the name implies, you are trying to ask computer systems to artificially behave as if they were intelligent.

Machine learning (ML) is a subset of AI techniques. ML techniques attempt to apply statistics to data problems in an effort to discover new knowledge. Or, in other terms, ML techniques are AI techniques designed to learn.

Deep learning is a further subdivision of machine learning that uses quite complex techniques, known as neural networks, to discover knowledge in a particular way. It is a highly specialized subfield of machine learning that is most commonly used for image, video, and sound analysis.  

# Analytics Tools

Software helps analysts work through each one of the phases of the analytics process. These tools automate much of the heavy lifting of data analysis, improving the analyst's ability to acquire, clean, manipulate, visualize, and analyze data. They also provide invaluable assistance in reporting and communicating results.

Some of these tools are well-known to most computer users. For example, people are generally familiar with spreadsheet tools such as Microsoft Excel or Google Sheets.

Other analytics tools require more advanced skills. For example, the R programming language is designed to provide analysts with direct access to their data, but it requires learning some basic coding skills.

Tabular Data
Tabular data is data organized into a table, made up of columns and rows. A table represents information about a single topic. Each column represents a uniquely named field within a table, also called a variable, about a single characteristic. The contents of each column contain values for the data element as defined by the column header.

Structured Data Types
Structured data is tabular in nature and organized into rows and columns. Structured data is what typically comes to mind when looking at a spreadsheet. With clearly defined column headings, spreadsheets are easy to work with and understand. In a spreadsheet, cells are where columns and rows intersect.

Unstructured Data Types
Unstructured data is any type of data that does not fit neatly into the tabular model. 
Examples of unstructured data include digital images, audio recordings, video recordings, and open-ended survey responses.

Semi-structured Data Type
Semi-structured data is data that has structure and that is not tabular. Email is a well-known example of semi-structured data. Every email message has structural components, including recipient, sender, subject, date, and time. However, the body of an email is unstructured text, while attachments could be anything type of file.

# Categories of Data

QUANTITATIVE AND QUALITATIVE DATA
- Regardless of structure, data is either quantitative or qualitative. Quantitative data consists of numeric values. Data elements whose values come from counting or measuring are quantitative.
- Qualitative data consists of frequent text values. Data elements whose values describe characteristics, traits, and attitudes are all qualitative.

DISCRETE VS CONTINUOS DATA
- Numeric data comes in two different forms: discrete and continuous. A helpful way to think about discrete data is that it represents measurements that can't be subdivided. You may intuitively think of discrete data as using whole numbers, but that doesn't have to be the case.
- Instead of counting, when you measure things like height and weight, you are collecting continuous data. While whole numbers represent discrete data, continuous data typically need a decimal point.
- Qualitative data is discrete, but quantitative data can be either discrete or continuous data.

CATEGORICAL DATA
Text data with a known, finite number of categories is categorical.

DIMENSIONAL DATA
Dimensional data contains groupings of individual attributes about a given subject. 

# Common File Formats
Text Files
-Text files are one of the most commonly used data file formats. As the name implies, they consist of plain text and are limited in scope to alphanumeric data. One of the reasons text files are so widely adopted is their ability to be opened regardless of platform or operating system without needing a proprietary piece of software. 
-Many coding languages have libraries that make it easy to write comma- or tab-delimited files. When a file is comma-delimited, it is known as a comma-separated values (CSV) file. Similarly, when a file is tab-delimited, it is called a tab-separated values (TSV) file.

Javascript Object Notation (JSON)
-JavaScript Object Notation (JSON) is an open standard file format, designed to add structure to a text file without incurring significant overhead. One of its design principles is that JSON is easily readable by people and easily parsed by modern programming languages. Languages such as Python, R, and Go have libraries containing functions that facilitate reading and writing JSON files.

Extensible Markup Language (XML)
Extensible Markup Language (XML) is a markup language that facilitates structuring data in a text file. While conceptually similar to JSON, XML incurs more overhead because it makes extensive use of tags. Tags describe a data element and enclose each value for each data element. While these tags help readability, they add a significant amount of overhead

Hypertext Markup Language
HyperText Markup Language (HTML) is a markup language for documents designed to be displayed in a web browser. HTML pages serve as the foundation for how people interact with the World Wide Web. Similar to XML, HTML is a tag-based language.

# CHAPTER 3

THE RELATIONAL MODEL
In 1969, IBM's Edgar F. Codd developed the relational model for database management. The relational model builds on the concept of tabular data. In the relational model, an entity contains data for a single subject. When creating an IT system, you need to consider all the entities required to make your system work. You can think of entities as nouns because they usually correspond to people, places, and things.

ERD
The entity relationship diagram (ERD) is a visual artifact of the data modeling process. It shows the connection between related entities.

A unary relationship is when an entity has a connection with itself. For example, Figure 3.4 illustrates a unary relationship where a single manager has multiple employees.

A binary relationship connects two entities. Binary relationships are the most common and easy to explore, whereas unary and ternary are comparatively complex and rare.

A ternary relationship connects three entities. For example, you might use a ticket entity to connect a venue, a performing artist, and a price.

RELATIONAL DATABASE
Relational databases are pieces of software that let you make an operational system out of an ERD. You start with a relational model and create a physical design. Relational entities correspond to database tables, and entity attributes correspond to table columns. 


NON-RELTIONAL DATABASE
A nonrelational database does not have a predefined structure based on tabular data. The result is a highly flexible approach to storing data. However, the data types available in relational databases are absent. As a result, you need to know more about the data itself to interact with it. Data validation happens in code, as opposed to being done in the database. 

Examples of nonrelational databases include key-value, document, column family, and graph.

#DATABSE USE-CASES

ONLINE TRANSACTIONAL PROCESSING 
OLTP systems handle the transactions we encounter every day. Example transactions include booking a flight reservation, ordering something online, or executing a stock trade. While the number of transactions a system handles on a given day can be very high, individual transactions process small amounts of data. OLTP systems balance the ability to write and read data efficiently.

NORMALIZATION
Is a way of structuring a database in a way that minimizes duplicating data.

ONLINE ANALYTICAL PROCESSING
OLAP systems focus on the ability of organizations to analyze data. While OLAP and OLTP databases can both use relational database technology, their structures are fundamentally different. OLTP databases need to balance transactional read and write performance, resulting in a highly normalized design.

SCHEMA CONCEPTS
- A data warehouse is a database that aggregates data from many transactional systems for analytical purposes. Transactional data may come from systems that power the human resources, sales, marketing, and product divisions. A data warehouse facilitates analytics across the entire company.

- A data mart is a subset of a data warehouse. Data warehouses serve the entire organization, whereas data marts focus on the needs of a particular department within the organization. For example, suppose an organization wants to do analytics on their employees to understand retention and career evolution trends. To satisfy that use case, you can create a data mart focusing on the human resources subject area from the data warehouse.

- A data lake stores raw data in its native format instead of conforming to a relational database structure. Using a data lake is more complex than a data warehouse or data mart, as it requires additional knowledge about the raw data to make it analytically useful. Relational databases enforce a structure that encapsulates business rules and business logic, both of which are missing in a data lake.

DIMENSIONALITY
Dimensionality refers to the number of attributes a table has. The greater the number of attributes, the higher the dimensionality. A dimension table provides additional context around data in fact tables.

# CHAPTER 4

Duplicate Data
Duplicate data occurs when data representing the same transition is accidentally duplicated within a system.

Redundant Data
Redundant Data happens when the same data elements exists in multiple places within a system. Frequently data redundancy is a function of intergrating multiple systems.

Missing Values
Occurs when you expect an attribute to contain data but nothing is there.

Invalid Data
Are values outside the valid range for a given attribute.

Non-parametic Data
Nonparametric data is data collected from categorical variables.

Data Outliers
A data outlier is a value that differs significantly from other observations in a dataset.

Specification Mismatch
A specification describes the target value for a component. A specification mismatch occurs when an individual component's characteristics are beyond the range of acceptable values.

Data-type Validation 
Data type validation ensures that values in a dataset have a consistent data type.

DATA MANIPULATION TECHNIQUES
Recoding Data
Recoding data is a technique you can use to map original values for a variable into new values to facilitate analysis.

Derived Variables
A derived variable is a new variable resulting from a calculation on an existing variable.

Data Merge
A data merge uses a common variable to combine multiple datasets with different structures into a single dataset.

Data Blending
Data blending combines multiple sources of data into a single dataset at the reporting layer.

Concantenation
Concatenation is the merging of separate variables into a single variable. 

Data Append
A data append combines multiple data sources with the same structure, resulting in a new dataset containing all the rows from the original datasets.

Imputation
Imputation is a technique for dealing with missing values by replacing them with substitutes.

Reduction
Reduction is the process of shrinking an extensive dataset without negatively impacting its analytical value. 

Circumstances to check for quality
Data Acquisition
Data Transformation and Conversion
Data Manipulation
Final Product Preparation

DATA QUALITY DIMENSIONS
Data Accuracy
Data Completeness
Data Consistency
Data Timeliness
Data Uniqueness
Data Validity

METHOD TO VALIDATE QUALITY
Reasonable Expectations
Data Profiling
Data Audits
Sampling
Cross Validation

# CHAPTER 5

MEASURES OF FREQUENCY
Count
Percentage
Frequency

MEASURES OF CENTRAL TENDENCY
Mean - The mean, or average, is a measurement of central tendency that computes the arithmetic average for a given set of numeric values.
Median - dentifies the midpoint value for all observations of a variable.
Mode - The mode is a variable's most frequently occurring observation. 

MEASURES OF DISPERSION
Range - s the difference between its maximum and minimum values.
Distribution - is a function that illustrates probable values for a variable, and the frequency with which they occur. 
Normal Distribution - is symmetrically dispersed around its mean, which gives it a distinctive bell-like shape.
Skewed Distribution - has an asymmetrical shape, with a single peak and a long tail on one side. 
Bimodal Distribution - has two distinct modes, whereas a multimodal distribution has multiple distinct modes.
Variance - is a measure of dispersion that takes the values for each observation in a dataset and calculates how far away they are from the mean value.
Standard Deviation - is a statistic that measures dispersion in terms of how far values of a variable are from its mean. 

HYPOTHESIS TESTING
 A hypothesis test consists of two statements, only one of which can be true. It uses statistical analysis of observable data to determine which of the two statements is most likely to be true.

 Hypothesis Testing with the Z-test
 Hypothesis testing with the Z-test is appropriate when you have a sample size over 30 and a known population standard deviation, and you are using the normal distribution.

Hypothesis Testing with the T-test
A t-test is conceptually similar to a Z-test, but uses the t-distribution instead of the standard normal distribution. You interpret the results of a t-test the same way you interpret a Z-test in terms of critical regions, confidence levels, and p-values.

Hypothesis Testing with Chi-Square
The chi-square test is available when you need to assess the association of two categorical variables. In this case, the null hypothesis asserts that there is no association between the variables, and the alternative hypothesis states that there is an association between them.

Simple Linear Regression
Simple linear regression is an analysis technique that explores the relationship between an independent variable and a dependent variable. 

Exploratory Data Analysis
An exploratory data analysis (EDA) uses descriptive statistics to summarize the main characteristics of a dataset, identify outliers, and give you context for further analysis. 

While there are many approaches to conducting an EDA, they typically encompass the following steps:
Check Data Structure
Check Data Representation
Check if Data Is Missing
Identify Outliers
Summarize Statistics
Check Assumptions

# CHAPTER 6
Programming Languages

R - The R programming language is extremely popular among data analysts because it is focused on creating analytics applications. 
Python - 
SQL - The Structured Query Language (SQL) is the language of databases.
Any time a developer, administrator, or end user interacts with a database, that interaction happens through the use of a SQL command. SQL is divided into two major sublanguages:

The Data Definition Language (DDL) is used mainly by developers and administrators. It's used to define the structure of the database itself. It doesn't work with the data inside a database, but it sets the ground rules for the database to function.
The Data Manipulation Language (DML) is the subset of SQL commands that are used to work with the data inside of a database. They do not change the database structure, but they add, remove, and change the data inside a database.

There are three DDL commands that you should know:

The CREATE command is used to create a new table within your database or a new database on your server.
The ALTER command is used to change the structure of a table that you've already created.
The DROP command deletes an entire table or database from your server.

There are also four DML commands that you should know:

The SELECT command is used to retrieve information from a database. 
The INSERT command is used to add new records to a database table.
The UPDATE command is used to modify rows in the database. .
The DELETE command is used to delete rows from a database table.

STATISTICS PACKAGES
IBM SPSS
SPSS is one of the oldest statistical software packages, first released in 1968, but it continues to be used today by many statisticians.

Stata
Stata is yet another statistical analysis package that dates back to the 1980s and continues to be updated today. It offers essentially the same features as SPSS and SAS and provides users with both a graphical interface and a command-line interface depending on their personal preference. Stata is less widely used than the more popular SAS and SPSS tools.

Minitab
The final statistical software package covered on the Data+ exam is Minitab

MACHINE LEARNING
IBM SPASS Modeler
IBM's SPSS Modeler is one popular tool for building graphical machine learning models. Instead of requiring that users write code, it provides an intuitive interface where analysts can select the tasks that they would like the software to carry out and then connect them in a flowchart-style interface.

RapidMiner
RapidMiner is another graphical machine learning tool that works in a manner similar to IBM SPSS Modeler. It offers access to hundreds of different algorithms that may be placed in a visually designed machine-learning workflow. RapidMiner also offers prebuilt analytic templates for common business scenarios. 

ANALYTICS SUITES

IBM Cognos
IBM Cognos is an example of one of these integrated analytics suites. It uses a web-based platform to offer analysts within an organization access to their data and is backed by IBM's Watson artificial intelligence capability. The major components of Cognos include the following:

-Cognos Connection is a web-based portal that offers access to other elements of the Cognos suite.
-Query Studio provides access to data querying and basic reporting tools.
-Report Studio offers advanced report design tools for complex reporting needs.
-Analysis Studio enables advanced modeling and analytics on large datasets.
-Event Studio provides real-time data monitoring and alerting, allowing business leaders to be immediately notified when certain events take place and/or provide automated responses to those events.
-Metric Studio offers the ability to create scorecards for business leaders to quickly analyze key metrics from across the organization.
-Cognos Viewer allows stakeholders to easily interact with data and analyses prepared using Cognos.

Microsoft Power BI
ower BI is Microsoft's analytics suite built on the company's popular SQL Server database platform. Power BI is popular among organizations that make widespread use of other Microsoft software because of its easy integration with those packages and cost-effective bundling within an organization's Microsoft enterprise license agreement.

The major components of Power BI include the following:

-Power BI Desktop is a Windows application for data analysts, allowing them to interact with data and publish reports for others.
-The Power BI service is Microsoft's software-as-a-service (SaaS) offering that hosts Power BI capabilities in the cloud for customers to access.
-Mobile apps for Power BI provide users of iOS, Android, and Windows devices with access to Power BI capabilities.
-Power BI Report Builder allows developers to create paginated reports that are designed for printing, email, and other distribution methods.
-Power BI Report Server offers organizations the ability to host their own Power BI environment on internal servers for stakeholders to access.

Microstrategy
MicroStrategy is an analytics suite that is less well-known than similar tools from IBM and Microsoft, but it does have a well-established user base.

Domo
Domo is a software-as-a-service (SaaS) analytics platform that allows businesses to ingest their data and apply a variety of analytic and modeling capabilities. It is not a very widely used tool.

Datorama
Salesforce Datorama is an analytics tool that focuses on a specific component of an organization's business: sales and marketing. It's not a general-purpose analytics tool but is instead focused on applying machine learning, visualization, and other analytics techniques to the sales and marketing process.

AWS QuickSight
AWS QuickSight is a dashboarding tool available as part of the Amazon Web Services cloud offering. This tool's power comes from the fact that it is available on a pay-as-you-go basis and its integration with the powerful data storage, data warehousing, machine learning, and artificial intelligence capabilities offered by the Amazon cloud.

Tableau
Tableau is arguably the most popular data visualization tool available in the market today. The focus of this tool is on the easy ingestion of data from a wide variety of sources and powerful visualization capabilities that allow analysts and business leaders to quickly identify trends in their data and drill down into specific details.

Qlik
Qlik is another popular SaaS analytics platform, offering access to cloud-based analytics capabilities. The major products offered by Qlik include the following:

QlikView is the company's original analytics platform that focuses on providing rapid insights.
Qlik Sense is a more advanced platform providing more sophisticated analytics capabilities (at a higher cost, of course!).

BusinessObjects
BusinessObjects is an enterprise reporting tool from SAP that is designed to provide a comprehensive reporting and analytics environment for organizations. 

# CHAPTER 7


# CHAPTER 8
DATA GOVERNANCE


Data governance involves creating a comprehensive framework of policies, procedures, and standards to effectively manage an organization's data throughout its lifecycle, ensuring security, quality, and compliance.
Data governance requires multiple individuals to fulfill various roles, with data stewardship being a crucial concept.

-Data stewardship involves developing policies and procedures for maintaining data quality, security, privacy, and regulatory compliance within an organization.

Data Use Agreements
A data use agreement (DUA) is a contractual document for transferring private data between organizations.

Security Requirements
encryption is the process of encoding data with a key so that only authorized parties can read it.

Payment Card Information
The Payment Card Industry (PCI) is a non-governmental body that governs card-based financial payments.

Use Requirements
Use requirements specify how to collect, process, use, store, retain, and remove data.

Master data management (MDM)
is a data governance discipline that uses processes, tools, and technologies to ensure that data assets across an organization have a single source of truth.

Throughout the duration of the course, we have delved deep into the realm of data analysis, exploring various techniques, tools, and methodologies to extract meaningful insights from raw data.

One of the key takeaways from this course is the understanding that data is not merely numbers and statistics but a powerful resource that drives informed decision-making across diverse industries and sectors.












































































   
