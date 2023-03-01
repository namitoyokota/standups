# Standups

## Venminder
### 3/1/23
Yesterday
- 1189 which was moving the API service files to a new directory
- 1170 for refactoring our current moment.js code to start using date-fns

Today
- 1175 to create a new enum to store display types for controls
- 1019 which is cleaning up the UI for the add control dialog
- I was looking through all of the UX designs yesterday afternoon and found some differences in the design and the current UI, so I'll also make those minor changes in the same PR as well.

## Hexagon
### 1/29/21
Yesterday
- After stand up, had a meeting with Mark, Joshua, Austin, and Lyna
  - Went pretty well
  - Got some guidance on where to go from here
- Spend the rest of the day trying to migrate my Python script to C# in Visual Studio
- But having trouble with versioning and having the tests be recognized in the load test tool

Today
- Have some ideas on how I can tackle these issues
- Working on fixing those errors and ask for help if needed
- My goal is to finish the migration so Monday I can go more in-depth validations

### 1/28/21
Yesterday
- Continued researching and testing front-end load testing scripts
- Was running into versioning issues and other bugs but got most of that solved
- Met with Austin to keep each other updated with our work and discuss how we can merge them together to create an End-to-End load test

Today
- Meeting with Mark, Joshua, and Austin
- Rest of the day depends on how the meeting goes and any guidance that I get there
- Probably going to be adding validations some and reading through Mark's wiki page for our testing types and parameters

### 1/27/21
Yesterday
- Started using a command line automation tool to run load testing scripts
- Got it running multiple threads with Jmeter scripts
- Started working on Python scripts but kept running into trouble configuring problems and tracking live metrics

Today
- Trying to fix bugs with Python scripts
- Testing the new framework using Java and Junit testing
- Meeting with Austin to plan how we can put our work together


### 1/26/21
Yesterday
- Started further research into front-end load testing features to add
- Found an automation framework to run scripts from the command line
- Was able to get python installed and using the framework to run my previous scripts that I've written using that tool
- Worked to implement validations using a C# script but found out that the framework only supports newer versions of the .NET framework
- This morning, found a workout around using Python

Today
- Working on implementing validations
- Creating more scripts for different tasks
- Add some modularity for reusable code

### 1/25/21
Friday
- Meeting with Mark, Joshua, and Austin
  - Went really well
  - Got to pick a framework and a software to use for front-end load testing
- Wrote a wiki page for my research of framework comparisons
  - Also added an instruction page for installing Selenium and Jmeter
- Started researching into more in-depth performance testing features

Today
- Researching on
  - Adding validations
  - Performing different tasks
  - Configuring environment variables using Config
- Hopefully start adding these features to the scripts

### 1/22/21
Yesterday
- Added 2 more frameworks to try our performance tests on
- Protractor (help from Lyna) and Selenium using Visual Studio and C#
- Created a config file and a PowerShell script to make testing easier
- Documented my research and testing
- Met with Austin to prepare for our meeting today and look for further possibilities

Today
- Meeting with Mark Joshua and Austin
- The rest of the day depends on the content of the meeting

### 1/21/21
Yesterday
- Created a PowerShell script to be able to select which framework to load test
- Created a Config file for log in information and CSS selectors and all scripts use
- Finished with a script for testing with Protractor
- Finished a new script with Selenium in C#
- Documented my research

Today
- Meet with Austin to keep other up to date with our progress
- Continue implementing load testing for the scripts that I've wrote
- Continue documentation

### 1/20/21
Yesterday
- Met with Joshua and Mark after standup
- Got new log in information that solved my error from 2 days ago
- Using that, I implemented the entire process from accessing connect, logging in, staying on for a certain amount of time, then logging out
- Did that with 2 frameworks: Element and Puppeteer
- Both seems to work really well
- Met with Lyna and got a demo of her Protractor scripts
- Started working with Protractor and potentially using it as a performance testing tool but running into some limitations

Today
- Continue research on Protractor
- Implement more testing features for Element and Puppeteer
- Creating a PowerShell script to configure which framework to run and with how many tabs concurrently

### 1/19/21
Friday
- Started implementing the front-end load testing for 2 of the 4 potential frameworks I found

Thursday
- Element & Puppeteer
- Was able to simulate log in screens concurrently from 2 browser tabs
- Got stuck at 2 factor authentication for log in using my account
- Then moved onto using Google but found out that Google Authentication does not support software automated log in for security purposes
- So Mark and Joshua, I will need to talk to you guys about this going forward

Today
- I will look for potential work arounds for automating Google login
- I'm going to be implementing same task from Friday with a framework called Selenium
- Hoping to meet with Lyna and Austin about potentially using Protractor framework for front-end load testing
- Then document information about each framework for comparison so we can eventually pick one that best fits our needs

### 1/15/21
Yesterday
- Austin and I had a meeting with Mark and Joshua
- Updated them on the load testing research
- Started researching browser-based load testing tools
- Came up with 4 potential and started testing 3

Today
- Testing the last testing tool
- Modifying the scripts to open multiple tabs
- Modifying the scripts to access Connect
- Modifying the scripts to read JSON files to get log in information of simulated users

### 1/14/21
Done
- Continued learning to use the SignalRClient with other services not just incidents
- Researched SignalR load testing tools and put together some notes
- Continued testing Visual Studio web load generator

Today
- Meet with Austin
- Meet with Austin and Mark
- Afternoon depends on the meeting

### 1/13/21
Done
- Visual Studio Web Test
  - Only supports Internet Explorer
  - Record http requests with Fiddler
  - Import into visual studio and had trouble with authorization: 401 unauthorized
  - Figured it out this morning how to provide credentials (access token) with header
- SignalR Load test
  - Research on using SignalR
  - Met with Chad on running SignalR client and listening to live updates for Incidents
  - More explanation on where the data is all stored for future testing

To Do
- Start increasing requests and adding validations
- Test SignalR with different services
- Research SignalR load testing tools


### 1/12/21
Done
- Requested for a license: needed justification, now approved
- Downloaded Visual Studio Enterprise and confirmed license
- Met with Austin on back-end performance testing through the PowerShell
- Started research on front-end load testing using Visual Studio
- Installed an extension for performance testing

To DO
- Continue research and start testing some of the Visual Studio's testing capabilities
- Research into testing SignalR connections
- Maybe meet with Austin as needed

### 1/11/21
Done
- Finished onboarding: installing services and running though Service Fabric, verified
- Got help from Craig on debugging each service individually
- Brief overview of what each service is used for, and the Azure Portal
- Updated the onboarding Wiki
- Started researching load testing and reading into Austin's research

To Do
- Need to talk to Mark about what to do going forward

### 1/7/21
Done
- Meeting with Austin, Mark, and Joshua about the performance testing tools
- Continued the onboarding process and got help from Austin
- Updated the CommonIdentity repo's UserManifests so I will have access to Local, Dev, and Staging
- Met with Craig for some explanation on the pipeline and some additional questions
- Got the Antivirus policy updated to the Developer Systems

To Do
- Start installing the services with the updated Antivirus policy and get help as needed
- Set up Swagger Service APIs
- If finished onboarding wiki, update the wiki as needed

### 1/6/21
Done
- Onboarding wiki finished
  - Certificates
  - VPN to Galileo DEV (still needs testing)
- Researched and understood most of the big picture system architecture of HxGN Connect

To Do
- Hoping to get connected with a team member for guidance to see demos more in-depth look into the application and its services

### 1/5/21
Yesterday
- Building tour and equipment
- Started requesting licenses and setting up a development environment
  - Visual Studio
  - Azure
  - Azure DevOps
  - Hexagon VPN
  - Microsoft Office
- Set up home desk set up for remote work

Today
- Finish following the rest of onboarding wiki page
  - Compiler
  - SDK
  - Source Control
  - PowerShell
  - Package Managers
  - Certificate
- Learn about the project and its architecture
- Research and understand topics and technologies that I'm not familiar with
- Install Galileo DEV VPN
- Finish all of the HR documents and elections
