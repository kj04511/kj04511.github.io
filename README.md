## BUDK Worldwide Internship - Readme

BUDK Worldwide is an online ecommerce company that specializes in knives and weaponery. During my internship I will be working in their IT department working on tasks that focus on data analysis and report creation that makes the data more useful. The company is moving away from catalog sales and more towards online sales which has brought the need for more data transparency to make informed advertising, merchandising and marketing decisions. I will be tasked with creating reports that drive this initiative within the organization. 


## Tasks during internship

- During my internship I will be working with Microsoft SQL Server Management and Visual Studio to create programmatically generated Excel documents that will be used by the Ecommerce department, Merchandising department, Marketing department and upper management to regulate inventory, determine item profitability, easily adjust pricing and review an item’s sale trend on third party websites such as Amazon, eBay and Wish. Throughout the internship I have been tasked with creating an Amazon Pricing Report, eBay Pricing Report, and Wish Pricing Report for this purpose.

- I have also been tasked with expanding the existing Website Merchandising Report to account for the multiple company websites. This report will be used to track items displayed on the website using the top down breadcrumb structure of the website. The report will flow with the website such that you will be able to drill down into the Excel document in the same manner as the current website and achieve the same items that are displayed on the website. I am tasked with taking the current report code and creating one report for each website. This report will be used when maintaining the website and tracking inventory and category information (i.e. an item can be in multiple categories on the website). 
 
- The final major report that I have been tasked with is the Warehouse Production Analysis Report. This report will be used to determine the efficiency of the warehouse regarding daily ready to process orders and daily shipments levels. The goal is to take a snapshot of the real-time data and translate that into how much shipment carryover from day to day is being accrued by the warehouse. This report will be used by the CEO to determine if the warehouse is performing as desired daily. 


## How these reports work

These reports are autogenerate reports that do not require any manual creations tasks. Each Excel is setup in VisualCron which is a Windows task scheduler that is located on the server. The reports are placed on a time trigger that allows them to be ran once or multiple times throughout the day. Each report also has a subscriber list which are individuals that want to receive the report. This information is maintained within the database and is easily updatable within the company’s internal intranet system. 
