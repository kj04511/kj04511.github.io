# Internship Based Analysis Report

## Section 1

**General Description of your working environment:**

**Explain the business, its product and/or services, its size (annual sales volume, number of employees), its location, the industry they are in, their expertise, market they are in, geographical location(s), their competition, etc.**

BUDK Worldwide Inc. is an online ecommerce company that operates multiple brands that specialize in weaponry such as knives and swords but also sells survival gear, guns, and tactical gear just to name a few. BUDK Inc. was founded in 1989 as a catalog merchant and has since began shifting more of their operations to online ecommerce since a growing number of their customer base has opted for online shopping as opposed to catalog purchasing. The BUDK Worldwide Inc. brand is housed under the umbrella of On The Edge Brands which consists of a consolidation of the company’s multiple product line brands. The On The Edge brands are as follows: BUDK, True Swords, Kennesaw Cutlery, CH Kadels and United Cutlery. BUDK self-hosts all the websites for each individual brand as well as maintains online stores on Amazon, EBAY, and WISH. BUDK Inc.’s headquarters and distribution center are based in Moultrie, Georgia, which is in Southwest Georgia. BUDK Inc. is an industry leader in the knife industry and has netted an average of $37 million over the past 5 years in sales and has 300+ employees. BUDK Worldwide Inc. is a top 10 industry leader in the knife industry but their competitors are Bubba Knives, Dog Knives, and Jake2Jake Custom Knives just to name a few. To compete in an online marketplace, BUDK Worldwide Inc. has invested heavily in their IT department to manage their self-hosted websites as well as their employee accessible Intranet system that integrates with Amazon, EBAY and WISH for easy product maintenance.

## Section 2

**Identify the objective(s) / problem you are, will be, working on:**

- **Describe the existing function(s), the way system is, has been, working. Investigate the process in detail.**

- **Clearly identify the problem, or more specifically, a discrepancy between an existing and desired state of affairs.**

- **Clearly describe your learning objective, including your duties, responsibilities, and activities for meeting objectives.**

- The function of the system has been the user gathers multiple reports from Amazon and from the BUDK’s database and combine this information together using the Amazon reports and the BUDK reports in order to generate one consolidated report to review the unit sales, profits, fees, inventory levels and other pertinent information for the products sold via Amazon and EBAY. The amount spent on advertisement campaigns for individual items and fees associated with each item a customer purchased is contained within Amazon’s database and has been accessible to the Merchandising, Finance and IT Departments via Amazon’s Seller Central portal but is not useful because it is not coupled with the gross profit information contain on BUDK’s database nor is it aggregable within Amazon’s portal. 
Users currently log into two separate Amazon Seller Central accounts and generate Excel reports from those websites. Because the reports are generated ad-hoc within the Amazon Seller Central portal, the date ranges and multiple report types can be generated by the user via pre-determined drop-down boxes within the portal.  They then select the necessary information to generate the information needed and save the Excel documents. The user accesses the auto-generated Excel reports that are derived from BUDK's database consisting of profits, product costs, vendor costs, etc. The user then proceeds to do a V-LOOKUP in Excel to merge information from the Amazon generated reports and the company generated reports. The user then takes the merged report and does various calculations that are necessary to get the information needed for upper-management decision making. This process is currently being done on a daily basis and the information contained within Amazon’s Seller Central portal is needed by multiple employees.

- The current state of affairs requires that users access multiple reports contained on Amazon’s Seller Central and merge this information into reports auto generated via BUDK’s database. This process currently requires all users that need this information to access Amazon’s Seller Central website and complete this merging process. 

  The desired state of affairs is that the needed information regarding campaign ad spends and Amazon fee contained within Amazon Seller Central be housed within the BUDK’s    database and a single report be created and auto-generated that can contain all of the required information the users need. 

  The discrepancy that exists between these two states is that the information isn’t contained within BUDK’s database and there is no single report that is generated from pre-determined data at pre-determined intervals.

- My learning objective is to enhance my program designing skills, learn a new programming language, experience a program testing environment and learning how to set up report schedules within VisualCron Automation Tool and Scheduler. I will accomplish these objectives by designing a process that will create a way to integrate the data contained in Amazon Seller Central into the BUDK database and work with report users to design a SQL stored procedure that will contain all of the desired data aggregation, calculations and information needed. Because I've only experienced working with Java, I will learn how to query the SQL stored procedure using the C# programming language in Visual Studio to create an interval driven Excel document. I will test the C# code in Visual Studio and debug where necessary to create the desired report. I will create a schedule for the newly created Amazon Seller Central data to be imported into the database. I will create work-instructions for individuals that will be placing the files within the folder to be imported. I will also attend weekly meetings to ask questions, gain additional knowledge and provide status updates on the project. 
  - My duties/responsibilities will be the following for meeting the objectives of this project:
      - Learn the Microsoft SQL Server Management environment
      - Learn the Visual Studio environment
      - Learn BUDK’s intranet environment
      - Interview the users of the report to gain deeper knowledge of the current processes, the information desired on the report and any deadlines that are needed
      - Create process for integrating Amazon Seller Central data into BUDK’s database
      - Create SQL stored procedure based on user interviews
      - Create C# program to query stored procedure and create Excel (use mentor, W3Schools.com and Tutorialpoint.com for additional help and for reference when needed)
      - Continuously debug program for errors
      - Validate data and accuracy
      - Gain user feedback 
      - Incorporate user feedback for report and process improvements
      - Finalize report by setting up schedule and report users within BUDK system
      
## Section 3

**Identify decision criteria important to resolving the problem/objective:**

**These criteria reflect what management thinks is relevant in his/her decision. These might include criteria such as price, product model, efficiency of the existing system, current hardware, software, applications, technology, client/end-user knowledge, and equipment.**

**Since criteria are not equally important, you must assign appropriate weight to each criterion. A simple approach is merely to give the most important criterion a weight of 10 and then assign weights to the rest against this standard.**

**Criteria** | **Weight**
-------- | ---------
Easy to use and understand | 2%
Short development time | 15%
Amazon data integration | 20%
Use existing development tools | 1%
Report is auto generated | 15%
No manual report manipulation | 25%
Easy report revisions | 2%
Defined user list | 3%
Positive user feedback | 2%
Correctly calculated and aggregated data | 15%
**Weighted Project Scores** | **100%**

## Section 4

**Developing alternatives:**

**Develop viable alternatives that could resolve the problem/issue. This section should include at least four alternatives and/or options available for your objective or problem.**

**Review these alternatives with your site supervisor prior to proceeding.**

1.	**Alternative 1:**  This first viable alternative that could resolve the problem is have one central employee/user gather the information from the Amazon Seller Central portal and the BUDK auto-generated reports and merge the information into one report. This solution would ensure that the information is calculated by one person in one uniformed way. It would also ensure that multiple employees were not taking time away from other tasks to do redundant work. 
1.	**Alternative 2:**  The second viable alternative that could resolve the problem is creating a process that will integrate the data contained within Amazon Seller Central into the BUDK database and create a web form via Visual Studio that would be accessible through the BUDK employee Intranet portal that would allow users with access to create ad-hoc reports based on a selection criterion that they would be able to select within the web-form. 
1.	**Alternative 3:**  The third viable alternative that could resolve the problem is having IT staff import into a database table the information contained in Amazon Seller Central reports downloaded from the Amazon portal on a weekly basis and having a SQL stored procedure that would generate the information ad-hoc into an Excel document for distribution to the requestors. This solution would allow the IT staff to be more in control of the data and would ensure that information is accurate based on user specifications. 
1.	**Alternative 4:**  The fourth viable alternative that could resolve the problem is creating a process that will integrate the data contained within Amazon Seller Central reports downloaded by users into the BUDK database and placing that information into a table. Then update existing SQL stored procedures to incorporate the aggregated Amazon information into the BUDK auto generated reports utilized by users. This solution would allow users to view familiar reports and the development time would be far less than creating a new report from scratch. 

## Section 5

**Analyze alternatives:**

**Once alternatives have been identified, you must critically analyze each one. The strengths and weaknesses of each alternative should become evident. You should also take into consideration the criteria and weights you established in step 3.**

**This step needs to be reviewed, verified and approved by your site supervisor.**

### **Alternative 1**

**Strengths**

1.	The data will be aggregated and calculated by one person consistently
1.	No redundant work by multiple employees
1.	No development time

**Weaknesses**

1.	Calculation errors could occur
1.	Only 1 person knows how to create report
1.	Report could be sent to incorrect user/users
1.	Report is not auto generated
1.	Inability to adjust report efficiently
1.	Possible inconsistent report delivery (time/date)
1.	Inability to completely understand data

### **Alternative 2**

**Strengths**

1.	User ability to create ad-hoc reports
1.	Selection criteria for customized report
1.	Web access (BUDK Intranet)
1.	Amazon Seller Central data integrated into BUDK database for future or additional reporting
1.	Existing development tools can be used
1.	Data will be aggregated and calculated accurately

**Weaknesses**

1.	More calculation scenarios
1.	Longer development time
1.	Complex C# code
1.	More user interviews
1.	Report not auto-generated (ad-hoc only)
1.	Could present difficulty for user to understand information generate by their selections
1.	Defined list of approved report recipients

### **Alternative 3**

**Strengths**

1.	Amazon Seller Central data integrated into BUDK database for future or additional reporting
1.	Data will be aggregated and calculated accurately
1.	Knowledgeable IT staff control of workflow functions
1.	Easy report revisions
1.	Short development time

**Weaknesses**

1.	Report is not auto generated
1.	No defined list of approved report recipients
1.	Additional time required from IT staff

### **Alternative 4**

**Strengths**

1.	Short development time
2.	Amazon Seller Central data integrated into BUDK database for future and additional reporting
3.	Data will be aggregated and calculated accurately
4.	Easy report revision
5.	Report is auto generated
6.	Defined list of approved report recipients
7.	Ability to use current development tools
8.	No manual report manipulation
9.	User familiarity with report

**Weaknesses**

1.	Report possibly will not be clear to user

## Section 6

**Select the best alternative:**

**This is the crucial act of choosing the best alternative from among those listed and assessed. You need to choose the alternative that generated the highest score and fits best for the objective/problem. Provide a discussion that supports your selection in detail.**

**This section needs to be reviewed, verified and approved by your site supervisor.**

**Criteria** | **Weight** | **Alternative 1** | **Alternative 2** | **Alternative 3** | **Alternative 4**
-------- | --------- | -------- | --------- | ---------- | ------------
Easy to use and understand | 2% | 20 | 40 | 25 | 15
Short development time | 15% | 50 | 5 | 80 | 100
Amazon data integration | 20% | 0 | 100 | 100 | 100
Use existing development tools | 1% | 5 | 100 | 90 | 100
Report is auto generated | 15% | 0 | 5 | 0 | 90
No manual report manipulation | 25% | 0 | 25 | 100 | 100
Easy report revisions | 2% | 5 | 60 | 90 | 100
Defined user list | 3% | 0 | 100 | 0 | 100
Positive user feedback | 2% | 15 | 70 | 80 | 90
Correctly calculated and aggregated data | 15% | 10 | 100 | 100 | 100
**Weighted Project Scores** | **100%** | **9.45** | **44.55** | **73.4** | **89.8**

![Image of Weighted Chart](https://kj04511.github.io/Weighted%20Score%20Chart.PNG)

Based on the above criteria and weighted scoring chart, Alternative 4 is the best choice as an alternative for the project. Alternative 4 solves the problem of getting the data from Amazon Seller Central reports downloaded by users into the BUDK database and it also adds the Amazon information into the existing report, so the user no longer has to merge documents. Since an auto generated report is used as one of the merging documents in the current process, the SQL stored procedure can be updated to contain the new Amazon data and be integrated into the existing auto generated report. This decreases development time as well as maintains the schedules and user defined lists already established. Additional users can also be added to the report or removed from the reports as necessary. By adding the new data and calculations to the existing report, there is no need for the user to do any manual manipulation to create the reports and it also increases the ease of revisions to the data and/or report. Alternative 4 also allows for the developers to use the development tools that are already utilized by BUDK. This creates no additional development expenses and allows the development work to be done with tools that have a high familiarity factor. The additions to the existing report will enhance the positive user feedback because the reports will be familiar to the existing report users. The short development time also allows for quicker feedback by users and faster revisions when necessary. The users will benefit from having one report to review and utilize when making decisions.

## Section 7

**Implementing the alternative:**

- **Explain your implementation strategy in detail.**

- **Convey the decision to those affected and get their commitment to it.** 

- **Describe the time, cost, and methods in detail.**

**This step needs to be reviewed, verified and approved by your site supervisor.**

### Implementation Strategy

The following implementation strategy was devised for Alternative 4 and requires the use of Visual Studio (C# programming language), Microsoft SQL Server Management and Excel. Below you will find the detailed step-by-step strategy designed to utilize the development tools that are currently in use by BUDK as well as the incorporation of the new Amazon data into the existing report. This strategy maximizes the tools available, shortens development time and allows for me to learn a new programming language and development skills. 

Step 1:  I will identify all primary and secondary stakeholders.

Step 2:  I will begin interviewing the primary and secondary stakeholders to assess which auto generated report is being merged, where the Amazon Seller Central reports are located on the Amazon portal, the preferred interval of delivery, the current interval of delivery of the existing auto-report and the users of the report. I will also gather the following documents from stakeholders: copy of the downloaded Amazon reports generated from Amazon Seller Central, the BUDK auto-generated report used for merging with the Amazon report, and the final manually merged document. 

Step 3:  I will create my defined list of recipients based on the stakeholder interviews and review this list with the IT Manager for approval.

Step 4:  I will study the location (company drive) and the layout of the current auto generated report to better understand the current state of the report.

Step 5:  I will begin creating a process to import the Amazon reports into the BUDK database (BUDK currently uses Microsoft SQL Server Management to manage their database information). This process will be based on how the data is populated by Amazon and the easiest way to get this information into the database (possible daily, weekly and semi-monthly task for a designated user). 

  - Step 5-A:  Create table to hold Transactional Data
  
  - Step 5-B: Create table to hold Advertisement Spending Data 
  
Step 6:  This step will require me to use Visual Studio to create a process to import the Amazon reports into the BUDK database. This step will require the following sub steps:

  - Step 6-A:  Create base drop folder for files
  
  - Step 6-B: Create archive folder within base folder for previously imported files
  
  - Step 6-C:  Create method within Visual Studio to read files, import information into database 	table and move file to archive folder
  
  - Step 6-D:  Set-up schedule for importation within VisualCron Automation Tool and Scheduler
  
Step 7:  Gather test files from Amazon to test importation code in Steps 6 & 7

Step 8:  Validation - Test code and verify information is placed into the correct tables, the data imported is correct and amount of data is correct. 

  - Step 8-A:  Test files separately
  
  - Step 8-B:  Test both files
  
  - Step 8-C:  Review both tables within database and verify information is accurate
  
  - Step 8-D:  Repeat until error free and 100% data validation
  
Step 9:  When 100% data validation and error free testing is attained complete the following sub tasks:

  - Step 9-A:  Clear both database tables
  
  - Step 9-B:  Access the older files from the Amazon Seller Central portal and import those files into	the database using the code created
  
  - Step 9-C:  Verify importation succeeded 
  
Step 10:  Locate the stored for the existing report and review stored procedure for understanding.

Step 11: Begin to add additional columns to the existing stored procedure. This will require SQL coding within the Microsoft SQL Server Management environment. The final manually merged document should be used for data validation during this step. 

Step 12: Once the stored procedure for the existing has been updated, validated and accurately adds the required information begin incorporating this new information into the existing methods in Visual Studio (uses C#). The following sub tasks will need to be completed:

  - Step 12-A:  Verify if a template is used, if so, update the template with the new columns	(	template should match the layout of the final merged document)
  
  - Step 12-B:  Update the C# code in Visual Studio to set properties, fetch data SQL and add to the 	excel creation method for the newly created columns
  
  - Step 12-C:  Create testing folders to hold the updated template and generated test report
  
  - Step 12-D:  Verify the mapping is updated in Visual Studio to these new testing locations
  
Step 13:  Test and debug C# code in Visual Studio until error free.

Step 14:  Verify layout and data match the final merged document, repeat until data and layout is 100% verified.

Step 15:  Send to IT Manager for initial validation and adjustments, once approved proceed to Step 16.

Step 16:  User validation – Send to users approved in Step 3

  - Step 16-A:  If users have changes, verify with IT Manager prior to revisions
  
  - Step 16-B:  Revise and re-validate with users until 100% user acceptance
  
Step 17:  Additional steps:

   - Step 17-A: Add any new users identified in Step 3 to the auto generated user listing 
  
   - Step 17-B:  Verify with IT Manager the need for a schedule change based on interviews conducted in Step 2
   
Step 18:  Get IT Manager’s approval to put updated report into production

Step 19: Create a work-instructions for downloading and importing the Amazon Transactions report and the Amazon Ad Spending report. Provide these reports to IT Manager and designated users that will be responsible for this process.

Step 20:  File the work-instructions within the IT documents folder and review the project with mentor for any final thoughts, questions, or concerns.

- I ask for BUDK’s commitment to Alternative 4 and the strategy outlined above because it maximizes the use of tools already owned by BUDK and shortens the development time. This benefits BUDK because I am a new developer and creating a new report from scratch would significantly increase development time on the project. The inclusion of the Amazon data within the database will also benefit BUDK because the information will be available if needed for other reports. The update of the auto generated report will also allow users to focus on other tasks and take production time doing redundant tasks. One user will be the point of download for the Amazon reports located on the Amazon Seller Central portal and they will only spend less than 5 minutes downloading the saving those files to the base folder for importation. Once the user saves these files the schedule set-up in VisualCron will do the heavily lifting and begin the importation process created to add the data to the specified tables within BUDK’s database. This process not only speeds up the process but also ensures that users are utilizing only one set of accurate data. This also allows users to send one request to the IT department for any changes to the report, so there is only one central change request point for tracking purposes. 

- The time for this project should take no more than 10-12 weeks to complete if no additions or changes are presented to the proposed implementation strategy. The cost for BUDK is zero since this will be done by me through an internship and I will be utilizing the development tools that BUDK already has in place. The only cost foreseen for this project will be the time taken from the stakeholders during the interview process which each interview should not take more than 20 minutes of each user’s time. 

## Section 8

**Evaluating the decision effectiveness:**

**This section should appraise the result of the decision to see whether the problem has been resolved and/or the objective has been achieved.**

**This step needs to be reviewed, verified and approved by your site supervisor.**

- We will distribute emails to notify the users that the new report is in production

- After 2 weeks, we will reach out to the users of the report to see if the users encountered or had any of the following issues:

  - Any issues with the aggregation or calculation on the added data?
  
  - The layout?
  
  - The added columns? 
  
  - Missing information?
  
  - We will also ask the following regarding the usefulness of the report:
  
    - Did the updates resolve your issue of having to merge documents?
    
    - Did the new report save you time during your day? Week?
    
    - Do you need any more information added to the report?
    
    - Is the report overall more or less useful to you after the updates?
    
- We will relay to the users that the task will remain open for 4 weeks and if we do not hear of any revisions, we will close out the task. 
These inquiries will allow BUDK to see if the report has eliminated redundancy in the work completed during the day by various users as well as allows for users to provide valuable feedback. The feedback from the employees will allow the IT Manager to know that the task has been successfully completed and no additional issues have arisen from the updates to the report. Since this is a report update and not a scratch report the feedback focuses on the creation of a more useful report for the users and the elimination of work redundancy. 

[Return to Homepage](https://kj04511.github.io/)
