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
### 3/1/21
Friday
- Move my project directory in WebRoot and pushed that code in the pipeline
- Still running into issues with the dotnetcore version during the built
- Worked on implementing testing on units
- Got in a good spot for that
- In the afternoon, started setting up my machine to start developing the frontend

Today
- I'm meeting with Jeremy to get help on setting up Angular
- Work on hiding the incident IDs in the DOM


### 2/26/21
Yesterday
- Started implementing units made some progress but still working on that
- Added ability to configure units, incidents, or both

Today
- Fix build issue from Joshua's exclusions update so pushing that change
- Meet with Lyna sometime today to see how she implemented tests against units
- Hoping to finish units today

### 2/25/21
Yesterday
- Ran a small load test with Austin to test our tooling
- Made some minor changes in the afternoon, and cleaned up the code with some comments
- Worked on pushing the code to git but ran into a build error with nuget packages

Today
- I will be trying to fix that
- Start working on load testing Units

### 2/24/21
Yesterday
- Worked on the errors that I was having with not being able to read the DOM fast enough and some other bugs that I documented from earlier in the week
- Implemented a whole new approach for that, seems to be working for now
- Clean up some code and added comments
- Made it more dynamic to prepare to start adding a script for units
- Met with Joshua and Austin to discuss where to go from here

Today
- I will be running a load test with Austin soon just to test our tooling
- Make adjustments as needed
- Push the code into Git
- Hope to start working on units

### 2/23/21
Yesterday
- Able to get each client logged into different account for the load test
- Got memory performance recorded at the start and the end (do a comparison)
- Ran issues with the script not being able to read the DOM fast enough when Austin's back-end is too fast
- Bugs with detached elements from the DOM because of the dynamic reading of the incidents
- Documented all of those problems and have a fix that I'll be implementing for most of the day

Today
- Cleaning up the code along the way to prepare to push to the webroot repo

### 2/22/21
Friday
- Ran different instances of load test to try and duplicate the situation from our last load test on Thursday where we think a lot of the users got logged out
- Was not able to make that happen again
- Figured out that not all users actually got logged out but the DOM just updated and my script was running into an error since it was trying to access an element which was no longer there
- Have a console log file output with filtering of only warning and severe information
- Rest of the afternoon was spent debugging an issue with reading notifications from Thursday's load test
- Finally figured out the problem at the end of the day

Today
- Trying to fix the notifications issue
- Joshua was able to create 20 more test users so will be testing logins with these accounts
- Recording memory performance

### 2/19/21
Yesterday
- Attempted to run a load test in the morning but ran into issues with the dev environment
- Started the performance test in the afternoon once that was fixed
- About 10-15 minutes into the test, the simulated clients started having some issues
- Spent the rest of the day digging into why and how that happened
- It seems like all of the clients got logged out all at once at that point

Today
- Try to look into how the users got logged out
- Have more issues to look into from the test yesterday with my script so will be looking into that

### 2/18/21
Yesterday
- Spent time in the morning adding a feature to log in multiple users for the safe cities tenant instead of just one that I had implemented previously
- Was having an issue with running 2 tasks concurrently and one would get stuck once in a while but got that figured out and fixed
- Attempted to run a load test yesterday afternoon so will be re running that today

Today
- I also have a sync up meeting with Joshua and Mark later in the day

### 2/17/21
Yesterday
- Most of the day was fixing a lot of small bugs with the counting of new incidents and making sure that they all match with the back-end
- Had a front-end performance test meeting to discuss different approaches and new changes to be made to the DOM
- Met with Austin to do a small test and prepare for the load test today and discuss a few things there

Today
- We're going to be running another load test on the dev environment with more data this time
- We'll be analyzing the data and making sure the program ran without any errors
- Before then, hoping to add a feature to log in with multiple users instead of just one that I have now
- More implementations here and there from what I've discuss in the sync up meetings

### 2/16/21
Yesterday
- Spent most of the morning time fixing bugs in the load test script
- Started working on implementing testing of units
- Met with Joshua and Austin for a sync up meeting and talked about where to go from here
- Researched into reading the console log from chrome seems like that is a possibility
- Ran a small load test in the afternoon in the afternoon just on my computer with 2000 incidents per hour from Austin's script
- The client seems to have trouble reading new incidents one by one so I'll more into that today

Today
- Implement units
- Meeting with Joshua and Jeremy to discuss how we can improve the front-end 

### 2/15/21
Friday
- Implemented more in-depth incident reading using the expand button such as primary contact, cross street, and others for the automation script
- Added 2 concurrent tasks
  - one for reading incidents from the tab that I already had
  - 2nd task for reading incidents from the notifications tab
- I ran some short tests afterwards and validated that two tasks read the same amount of incidents total
- But, bad news, I actually ran it again this morning and I found that the duplicate incidents bug was back on the dev environment I think it could be caused from what Craig just said that they worked on

Today
- Fixing the problem of not being able to read in-depth incident info when running concurrent tasks
- Hoping to meet with Joshua and Austin
- I am planning to start tackling a lot of the new tasks from the sprint board

### 2/12/21
Yesterday
- Spent most of the morning cleaning up the code for the automation script
- Had a bug where I was reading some of the existing incidents instead of just new incidents so fixed that
- Created a log file to view the metrics of all of the clients combined after the test
- Spent the afternoon adding multi-threading to start listening to incidents from the incidents tab and from the notification concurrently. That's working now

Today
- Was going to start working on reading the incidents from the notifications
- Read additional incident info
  - So getting primary contact, attachments, and more
  - Which I had trouble previously
- Start researching into how I can approach a lot of the new tasks like
  - Running multiple users
  - Running multiple tenants
  - Storing incident id so modifications and deletions can be tracked
- When those are implemented
- Maybe meet with Austin for some sync up and a test

### 2/10/21
Yesterday
- Most of the morning time I spent with Austin making a lot of minor tweaks to our load testing scripts
- In the afternoon, we ran a load test for 2 hours from 1-3 on the dev environment
- Successfully finished the test without any major errors but still need some improvement going forward

Today
- Have a performance test meeting to discuss our test results from yesterday
- Just some preparations for the sprint reviews


### 2/9/21
Yesterday
- Started a load test starting at 2 o'clock
- My automation script had errors detecting new incidents after a little while
- So we decided to try again today.
- For the rest of the day, I made some minor tweaks
- Austin and I tested again to make sure everything works at the end of the day
- 
Today
- Austin and I will be running a load test again after standup
- If everything goes well with the test, we'll be reviewing the metrics afterwards
- And I'm planning on adding more features

### 2/8/21
Friday
- Made changes to the browser automation script according to the E2E sync up meeting from

Thursday
- Also met with Austin on how we can run our tests concurrently on a dev environment

Today
- I think after stand up, Joshua and Austin wanted to meet to plan for our test in the afternoon
- I'll be making some changes to the script to try and get that closer to perfect (I think there are still bugs)
- In the afternoon, like I said already, Austin and I will be running our test 

### 2/5/21
Yesterday
- Most of the day was spent debugging some small issues, cleaning up the code and final tests
- Sync up meeting for E2E testing
- Went well, know where to go from here
- Yesterday after the meeting and this morning was spent researching how I can implement some of the new features

Today
- So today I'll be working on adding those to the automation script

### 2/4/21
Yesterday
- Spent time in the morning try to figure out some of small bugs and got most of that fixed
- Found out the problem I was running into for reading in the incidents from the front-end seemed a little complicated so I will bring that up at the sync up meeting today
- In the afternoon, I worked on adding validations and outputting the results into a file
- Also spent some time running a load test to see its results

Today
- I have a sync up meeting in the afternoon
- So I will be spending most of the day cleaning up the code, running some tests, and putting some notes up of what I've been working on

### 2/3/21
Yesterday
- Started working on reading incidents from the website with the css selectors Had some trouble in the morning but talked to Lyna for a bit and finally got that somewhat working
- Added comparison functions to use for validations of incidents
- Added in-depth loggers more focus on the load testing portion

Today
- Fixing errors for reading in incidents
  - May need to talk to someone that understands the front-end well
  - Currently can read
- Load testing with different scenarios

### 2/2/21
Yesterday
- Had a sync up meeting for E2E testing after standup
  - Got updates on what Austin has been working on
  - Explained the problem with versioning
  - And got help on where to go from here
- Spent the morning time testing different scenarios of load test
- Spent the rest of the day working on the automation script for the front-end
  - Added a logger to keep track of all of the actions being performed
  - Added error catching so programs won't just shut down when running into exceptions
  - Started working on validations and have it to where I can read the expected incidents that should be displayed on the web

Today
- Continue working on the validations of incidents
- Adding configurations
- Testing those implementations with different load test scenarios

### 2/1/21
Friday
- Spent some time researching into the different .NET frameworks
- Figured out the problem with using the load testing framework was that the .NET Core 2.1 wasn't supported
- Moved my Python automation script into C# with .NET Core 3.1 which is only supported by Visual Studio 2019 version
- Today we need to discuss whether this is the approach to go with from now on or not

Today
- Spending more time implementing the automation script into C#
- Start looking into our testing plans to figure out the best way to implement

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
