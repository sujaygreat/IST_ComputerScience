#Problem Instructions


Flix2You is looking for a company to help them design a solution that meets the requirements they have set forth. As a team and aided by course materials, course content, and quality external resources, you need to create a proposal to meet the requirements of Flix2You. Keep in mind; your organization is not
the only one being solicited for this contract.

Good luck to each of the teams. May your solution be the winning one!

##Problem Introduction
Flix2You wants to expand its current operations. The goal of Flix2You is to make better use of their current data which would then allow them to apply analytics to better understand how they formulate a new strategy for their business. "We have collected data in our system for almost 9 years. So we know we are data ‘rich’ but as they also say….’information poor’, says Steve LaSalle, a corporate vice-president. Flix2You wants to be the most comprehensive video rental portal in the country.

The purpose of this problem is for your team to create a solution that meets the needs of Flix2You, a movie rental company. Flix2You already has a website but is wants to better understand who their customers are and how they can increase revenue. Flix2You is searching for an organization that will help them create a solution to manage the data and database that drives the Flix2You site and their corporation.

The goal of this problem is to assist Flix2You in their initiative to design a solution that will create a data repository for easier querying and applying analytics to better understand their data. More specifically, Flix2You needs an organization to create a database design, create a backup and recovery plan, conduct a user analysis for using the new database, analyze current data, create database reports, and identify any legal issues for the new repository that Flix2You needs to be aware of.

It is the responsibility of your team to demonstrate the nature of the solution by producing a problem document which is actually a plan to help Flix2You and solve their problem. Requirements for the document are detailed throughout this document.

One of your team’s responsibilities is to ensure that each of your team members participate equally throughout the design and development of the products. It is highly recommended that, prior to starting the project, each member of your team chooses a role from which you will play throughout the project. Choose the participants that you feel will most strongly make your case to the Board of Directors.

Project Manager
Database Administrator
Data Analyst
Quality Assurance
Programmer
Problem Objectives
After completing this problem, you should be able to:

Deliver a document covering the requirements of the project
Discuss your teams understanding of the scope of work for the project
Summarize the various features of the project
Develop a plan for completing the project (to include project timeline)
Identify the resources that will be needed to complete the project
Identify the administrative and staff needs for using the system
Explain the various user views included in the database design
Make recommendations as to the server hardware necessary for this new data repository
Develop and document the conceptual design
Create the relational schema to implement the relationships documented in the conceptual design
Prepare a plan for data backup and recovery
Describe the access and security measures used for the system
Explain how you will deal with issues around security of data transmission
Create the new tables as needed
Develop appropriate queries to satisfy end-user needs and apply analytics
Design appropriate queries and reports
Create any disclaimers and privacy statements needed for the site
Problem Assignment
Scope of Project

It is the intent of Board of Directors to solicit proposals for Flix2You. The Flix2You board of directors has solicited your project team to submit a plan to maintain and update the database that runs the Flix2You website. Within this proposal, you should address the database design, design a backup and recovery plan, conduct a user analysis for the database, assign user privileges, analyze current data (analytics) and create SQL statements that would generate reports from the database, and identify any legal issues that Flix2You needs to be aware.

NOTE: You do not need to submit a functioning application.

Upon completion of the proposal, your team should submit one copy of the document to your instructor via this assignment page.

##Problem Document

As part of the project, your team is required to create a project document. This document will be used to demonstrate your understanding and the scope of the project and your suggested solution. Use the following guidelines when creating your document:

The document will be no longer 30 single spaced pages
Use Arial 12pt Font, table of contents, and page numbering
APA format for references & citations (this include in-text citations)
must include, at a minimum, the following sections noted below
##I. Document Cover (1 Page)

As part of the submission procedures for this proposal, you are required to prepare a document cover. The cover needs to include the following:

Proposal Title
Class Section
Instructor Name
Your Company/Team Name, Address, and Telephone Number
Date of Submission
Any other Relevant Information
##II. Table of Contents (1 page)

Create a document table of contents that outlines the major document headings and subheadings along with their page numbers.

##III. Executive Summary (1 page)

Create a one-page summary, of your plan, which is brief, to the point, and will hopefully evoke sufficient interest in the recipient to warrant taking a closer look. It is used to summarize the major parts of the document and entice the reader to continue reading the rest of the document.

##IV. Project Overview (2-3 pages)

Scope of Work

Clearly state the problem to be addressed. Discuss your understanding of Flix2You’s needs and requirements for the new system.

##V. Project Management (2-4 pages)

Project Plan

Provide a proposed plan for completing the project that includes, at a minimum, the following information. See provided Microsoft Project.mppView in a new window file provided as a starting point. Embed the Gantt Chart in your Word Document such that it is easy to read and does not take up many pages.

To experience a great tutorial on MS Project visit Penn State’s Microsoft IT Academy (Links to an external site.).

You will need to fill in additional information:

Microsoft Project (or equivalent) Gantt Chart to include:
An in-depth explanation of what it will take to complete the project
Proposed project timeline (includes a start and an end date)
Project deliverables
Major milestones
Project Resources and Budget

Identify the resources you feel will be needed to complete the proposed project. You should focus on identifying the following:

The personnel needed to be able to complete the project, the time they will need to spend on the project, along with job titles and the associated costs.
A description of the roles and responsibilities for each of the identified personnel.
##VI. User Analysis (1-2 pages)

Users

Identify and describe the roles and responsibilities of the various users who will need to add, update, and manage the data stored in the Flix2You database. Identify the needs that the staff of Flix2You will have for the system (backend). Who will have just read only access? Who will be able to have read and write access? NOTE: This system is for the appropriate Flix2You employees. Site visitors will not have the ability to query corporate data.

Database Access

After identifying the users, identify the appropriate level of access that each user has to the database. Should every user be able to access the same information, or does there need to be some sort of hierarchy? Also describe the process to set and change these access privileges, and identify who is responsible for changing these privileges.

##VII. Organization of Data (3-4 pages including diagrams)

Existing database analysis – Identifying relationships

The database that drives the Flix2You website is a generic e-commerce database that was purchased as “off-the-shelf” software and was then modified by a prior group of database consultants. The database currently works with the Flix2You website, but it is difficult to query and understand the data in the current database. When queries are run, it slows down the online system and often disrupts customer transactions.

Given the existing database schema, analyze the entities, relationships between these entities, and cardinalities of these relationships. Determine what the structure will be that will hold your extracted dataset. Then, construct the corresponding ER Diagram for the new database design.

NOTE: The existing database schema can be found in the problem resources section of this document.

Existing database analysis – Normalization/Denormalization Approaches

Create the tables in the new database. Several possible approaches to this solution exist

Normalized Approach: If your team offers this type of solution be sure your design is in 3rd Normal Form. Once all the tables are in 3rd Normal Form, explain why they are in the 3rd Normal Form and develop and document the SQL necessary to create at least 3 of the related tables in the new database structure. In addition to creating the tables, use SQL to populate these tables with sample data.

Denormalized Approach or Alternative Approaches: Any other possible solution will require at a minimum of 2 tables developed, and included the SQL necessary to create these tables. In addition to creating the tables, use SQL to populate these tables with sample data. Do Nothing: Although this sounds extreme, is there a way to keep things as they are and improve the situation. (least recommended).

##VIII. Database Administration (2-4 pages)

Identify the roles and responsibilities of a DBA and any other administrative personnel who will be using the system. Include hardware/software knowledge, infrastructure knowledge, and clustering knowledge a DBA would need to have to succeed in administrating this system.

Database Backup and Recovery

Prepare a plan suggesting to Flix2You how they should store their data and backup and recovery strategies. Discuss how you will deal with technical issues that may occur while using the site. Outsourced 3rd solutions can be utilized. Note that any work contracted by 3rd Party solutions should be investigated for security, reliability, and cost.

Data Access and Security

Determine what types of security measures need to be in place so the system cannot be breached. Multiple levels of security will be necessary:

Database security – describe how you will secure the database so only people with the correct login/password will be able to access the data.
Privacy statement – explaining how a customer’s data will be used.
Anticipate any legal implications or disclaimers that need to appear on the site due to employees having access to customers’ personal information. Should employees have to sign disclaimers?
Dataload
If creating a “new read only” database that will pull data from an operational database, be sure include a discussion (eg. Plan) as to how you intend on updating the data that will be contained in your proposed database design. This would include frequency of the update, timeframe as to when the update would be conducted etc.

If creating a new design that is replacing the current operational database, be sure to include a discussion as to your company’s plan to migrate the existing database data to the new system and how it may or may not impact daily operations.

##IX. Database Dashboard and Analytics (2-4)

Database Dashboard

The executives at Flix2You would like to see a ‘dashboard’ created that management can log into securely and view weekly reports that contain specific information regarding the sales and demographics of the users of Flix2You. The dashboard should be informative, easy to understand, easy to use, and provide the ability to export data to MS Excel and print to a .pdf. The dashboard should provide the ability to drill down thru various levels of detail. Additionally, the dashboard should be able to run on a tablet device (eg. iPad, Android, etc.).

The dashboard should contain a graphical representation of the data. You will need to do some research on various dashboards. The purpose of this section is to have you demonstrate your ability to provide the SQL Queries needed to generate a web based report that details various corporate data owned by Flix2You. An example dashboard can contain the following information but is not limited to:

Movie Information

Movie name
Rating
When it was rented (day of the week)
How often it was rented
Revenue related information Company Information
Monthly, Quarterly revenues
Number of downloads, sales, etc.
Number of new members
The query should group the data accordingly for ease of reading and the user information associated with each product should be sorted in ascending order by Last Name.

##X. Legal Issues (1–2 pages)

Determine any disclaimers or privacy statements that need to be stated within this document and also located somewhere within the website for the customers to view. Some items that should be included are:

 

Privacy Statement – how do you plan on keeping the customer’s data private? How will the customer’s data be used? What security is in place to maintain the data remains private?
Terms and Conditions for Use – create a ticketing purchasing policy, that will include terms for refunding services and identify the ramifications of violating the terms and conditions.
##XI. List of References (Page count is whatever is appropriate)

Your team must compile a list of references that were used to help create your proposal document. This list of references should follow APA format. This section should not be considered part of the overall page count for the document.

Problem Resources
Background Flix2You is an established business (12 years old) and functions much like Netflix, Blockbuster, and Redbox. The primary focus of this business is to allow customers to make movie rentals online and have them sent to their homes. What differentiates Flix2You is why this project is moving forward. They realize they are on the verge of possibly stopping their growth and concede to Netflix, Blockbuster, and Redbox. They must understand their data in order to make a better business strategy allowing them to increase revenue.

The organization now employs 50 employees.

12 employees are upper level management and administrative support.
18 are mid-level management
20 are hourly employees working in warehousing and logistics.
The Flix2You management is young but eager to grow their business. However, they find that they cannot access the data to make well informed decisions and create a strategy for the business. So a great deal hinges on the timeliness and success of the project. Managers would like to not only have hardcopy reports created but also a backend that they would log into via the website and see the data wherever and whenever they like.

Flix2You Consumer

Site The current Flix2You URL for the consumer site is http://www.personal.psu.edu/fja100/flix2you (Links to an external site.). We have provided this to you as a resource to help you determine some of the features that will need to be incorporated into the administrative site.

History of Flix2You

Flix2You is a company that started in May 2002 with two rental locations, one located in Scranton, PA and the other one in Pittsburgh. These then grew to 520 locations on the East Coast of the United States. As of December 2013, we have closed our brick and mortar locations and gone completely online with almost 20 Million users. The savings were quite satisfying to shareholders but we have now realized we are no longer growing as aggressively. We anticipate offering more downloads via our website. Future downloads may include video games and apps.

Flix2You has rented millions of videos since it inceptions. We receive approximately 20,000 unique hits daily and expect for that number to increase significantly as we increase available downloadable movies and other offerings. One of our major concerns is that we won’t understand who is coming to our site and what movies we will offer, how we should offer them, or what types of downloads would be good. Since this is competitive market, we cannot afford to lose any customers so we are willing to spend a significant amount of money to ensure the infrastructure is scalable, reliable, and secure. But more importantly, that the new system gives us the information we need.



###DEMO PICTURE





Current Technical Infrastructure

Flix2You’s current corporate database is utilizing the 64-bit edition SQL Server 2008 as the backend DBMS and IIS and ASP.net/PHP as the technology solution used to build the data driven web pages. Recently, Flix2You has had some concerns that the infrastructure currently in place is not robust enough to handle the future backend business demands of the site. We are open to any ideas of moving to a more robust solution, if warranted. We have already invested a substantial amount of money into the current system and we want to now fully leverage it by creating this repository to better understand our data. We want to be data rich AND information rich!

Our IT data center is located in Scranton, PA.

Tech Specs:

CPU/Motherboard: HP ProLiant DL 180 G6 Intel Xeon 5500
Memory: 4 x 2 GB PC3-10600E DDR3
RAID Controller: HP Smart Array Controller p400
Local Storage: 2 x 250 GB Drives for C:
3 x 1 TB RAID-5 drives
Operating System: Microsoft Windows 2008 R2 Standard Edition, Standard 5-user CAL
Database: Microsoft SQL Server 2008 Standard Edition

Telecommunications and IT

Current headquarters and central warehouse are provided by Choice One (dedicated T-1 line). The current server is in a locked closet in the office manager area. IT personnel provide support for local area network on office premises. They are not familiar with database administration or development. They also provide desktop pc support. Current website is hosted off premise on a GoDaddy.com corporate level account.

The website and database are managed by a third party vendor on an as needed basis. They are not competing for this contract.






###ERD DIAGRAM
