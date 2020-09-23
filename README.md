# Automation Testing with Cypress, Axe and Eyes
This repository is a simple boilerplate code which demonstrates the new trending technology of test automation using JavaScript based tool named cypress. In addition to automation, accessibility and visual testing features are added using Deque Axe and Applitools Eyes
## Getting Started
### Background
This framework is a JavaScript based test automation framework using cypress as node package dependencies. Please refer the below link for detailed information about cypress.io
https://www.cypress.io/

### Set up Steps
* As it is a node.js program, you need to install node.js to get it running. Node.js can be downloaded from this URL by selecting the operating system: Node.js download
* Setup your favourite IDE. 
* For using Cypress Dashboard services, please create a free account by navigating to the below link
https://dashboard.cypress.io/login
* clone the project 
* Navigate to root folder and run the command in terminal npm install
* The above will install the required dependencies for developing and executing the automated test scripts 
* Verify cypress dependencies are added by verifying the below folder has been created after npm install
* First time the cypress runner takes time to load. Type the command in your IDE terminal ‘node_modules/.bin/cypress open’
* You can run the scripts which you want to run from terminal without using cypress runner by typing the following command
 https://docs.cypress.io/guides/guides/command-line.html#Installation








## Folder Structure
 
Cypress has a standard folder structure to be followed for all the projects. But user can customize and override the folder structure by updating this in the cypress.json file
Please refer the below link to get more details on the folder structure
https://docs.cypress.io/guides/core-concepts/writing-and-organizing-tests.html#Folder-Structure

In this boilerplate project, the following applications (angular based) are demonstrated on how to create test scripts
Health Resource Service Administration Connector Job Application
Health Resource Service Administration Application Website
Qovid Application (in development stage)
Google API for API Testing reference
### Script Development Steps
* Identify the bdd specification and write the scripts using describe it combination
Reference: .js files inside cypress/integration/specs and follow the same template
* Create page objects using css selector or jquery as these two are the formats identified by cypress
Reference: .js files inside cypress/support/pageObjects
### Code Snippets


