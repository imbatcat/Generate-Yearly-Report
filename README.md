## Automation for generating yearly report
This is for my assignment from where I'm OJT, this is an automation created by using UIPath, features of this robot includes:
- Performing data scraping and filtering from "https://acme-test.uipath.com"
- Download the reports and group them into each Excel file
- Uploads the Excel file to the server and updates the status of the work item

This project ultilizes the REFramework, a popular template used for designing complex robots that adheres the rules and best practices. There are two robots in the project: Dispatcher and Performer.
The **dispatcher** performs most of the data scraping work and uploads to the Orchestrator - a cloud server where robots can access the resources to - ,and the **performer** retrieves the data and performs the business logic of the work.
