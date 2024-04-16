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































   
