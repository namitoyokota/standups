# Standups
A history of my standups.

## Venminder
> December 5th, 2022 - Present

### 3/1/23
Yesterday
- 1189 which was moving the API service files to a new directory
- 1170 for refactoring our current moment.js code to start using date-fns

Today
- 1175 to create a new enum to store display types for controls
- 1019 which is cleaning up the UI for the add control dialog
- I was looking through all of the UX designs yesterday afternoon and found some differences in the design and the current UI, so I'll also make those minor changes in the same PR as well.

## Hexagon Safety & Infrastructure
> January 4th, 2021 - November 23rd, 2022

### 10/29/21
Yesterday
- We had a sync up meeting for Create Incidents in the afternoon so spent the morning time jotting down some notes and testing
- The meeting went really well so afterwards
- I started working on some of the additional changes that we talked about
- That first round of changes are done so

Today
- I'm going to try and finish the rest out today

### 10/28/21
Yesterday
- I finished up allowing the Create Incidents UI to be also used for editing incidents
- So now most of the implementations should be done

Today
- I'm going to be testing everything
- And jot down some notes for the sync up meeting at 1:30

### 10/27/21
Yesterday
- I finished up adding priorities for Create Incidents UI and
- Started working on setting a default value for the user list dropdown

Today
- I'm going to finish that up this morning and then
- We have a meeting to talk about setting priorities in onboarding setup
- So will probably be working on that for rest of the day
- And I'm also off early today at 3

### 10/26/21
Yesterday
- Worked on connecting the backend for priorities to Create Incidents but had some issues so
- I started working on the UI for keywords

Today
- I talked to Jared about the issue and we found out that it was just that the URL had been updated so I'm back on priorities today and hopefully finish that up

### 10/25/21
Friday
- I worked on adding priorities to Create Incidents UI
- And also talked with Jared throughout the day on the REST API
- We had some issues there but he was able to figure that out so

Today
- I'm going to be testing his changes and will be finishing that up

### 10/20/21
Yesterday
- I had issues with my local services so that took out most of the day
- At the end of the day I made a PR for uploading files on Create Incident but Jeremy pointed some things out so I'll be working on fixing that today and then start working on Editing Incidents

### 10/19/21
Yesterday
- I worked on uploading files in Create Incidents and I think I have everything ready but ran into an issue with Traefik at the end of the day so still talking to Stephen on that

Today
- When we get that figured out, I'll move on to editing incidents

### 10/18/21
Friday
- I worked on a new dropdown component in identity to be used in the Create Incidents UI
- Had some hiccups along the way but I got it finished so

Today
- I'll start working on uploading files and then attaching it on incident creation

### 10/15/21
Yesterday
- I pushed up some of changes for Create Incidents and then
- Started working on a work around for an issue I had that Hunter helped me out with

Today
- I have one more thing to work on there and then will be back on Incidents

### 10/14/21
Yesterday
- I continued working on the Create Incident UI and

Today
- Will be more of the same

### 10/13/21
Yesterday
- I fixed a small styling issue in recovery
- And then finished up a basic wizard for the Create Incidents UI so push that PR up and now it's on dev behind a feature flag and
- It's very minimal but did some testing this morning and that seems to be working just fine so

Today
- So today I will be adding more functionalities to that

### 10/12/21
Yesterday
- I was also in the Create Incidents meeting
- I continued working on the UI for that and also
- went back to recovery to fix a bug that Joel found and pushed that out as well

Today
- I'm back on Create Incidents and I'll try and get a protype up by the end of the day

### 10/11/21
Friday
- I met with Jeremy in the morning to discuss the Create Incidents UX, the feature flag removal, and also the validator script
- So I worked on those most of the day and finished up the feature flags and validator scripts done

Today
- I have a meeting to talk about the Create Incidents UX design and I'll continue to work on that 

### 10/8/21
Yesterday
- I started looking into the Create Incidents story and started implementation for that
- Got most of the UI layout done and
- Also this morning I pushed up the PR for the recovery to fit Joel's changes

Today
- I will be back on creating incidents and additing the logic and the functionality 

### 10/7/21
Yesterday
- I finished up removing the enhancement flag in feature flags
- And Hunter found an issue in identity so I fixed that
- Then moved onto the recovery manager restore change that I just have ready locally for now

Today
- I will be off today at 3 but Joshua and Mark, I will need to talk about what my next task is at some point

### 10/6/21
Yesterday
- I continued working on removing the feature flags and got all of ones that I pushed in tested
- I'm still looking through the enhancement flag

Today
- But I will finish that up this morning and then go back to recovery to make the restore changes

### 10/5/21
Yesterday
- I worked on removing the feature flags from the frontend and I got a good bit of it done so

Today
- I'm going through each one and validating that on staging
- I have a couple more longs to finish but I should finish that today

### 10/4/21
Friday
- I worked on adding the validator scripts
- And I got through all of the repos except for the 2 that I need to talk to Jeremy about so

Today
- I'm back on removing feature flags and testing those changes

### 10/1/21
Yesterday
- I talked with Jeremy on the feature flags that need to be removed from the frontend and started working on that
- And also this morning talked with Jeremy again to learn about the new validator change so I just created a list of repos that I need to go through so

Today
- I'll be working on both of those :)

### 9/29/21
Yesterday
- I continued hardening the recovery manager page and got a couple of prs there but everything should be in now so

Today
- I'm going to be testing all of those changes and preparing for the sprint review

### 9/28/21
Yesterday
- I worked on the bug in organization set up when saving changes and I pushed that change but the issue is still there on dev today so Jeremy is fixing that now
- Then I continued working on bug fixes and one of the issues, there's not an easy solution so Joshua Mark and Lyna if yall have time after standup, I would like to show you guys that and Jeremy if you can stay on here as well just in case

Today
- I'm going to push that change
- And continue on with the hardening

### 9/27/21
Friday
- I finished up the change to the organization setup layout that I talked to Jeremy about on Thursday and came up with a solution on
- There is an issue with the save functionality so I'm looking into that now but after I finish it, Joshua I would like to show you the change we came up with
- I also got in more bug fixes for the recovery manager and

Today
- I will be looking into the organization setup error and
- I also have 1 more round of bug fixes to go through in recovery manager that I need to get some help from Hunter on

### 9/24/21
Yesterday
- I worked on refactoring the tenant config page but ran into an issue so talked to Jeremy on that and he came up with a solution so I needed to re-work my changes but I have that update ready now

Today
- I'm doing some tests there so should have a PR up soon
- And then after that I'm going back to recovery manager and finish up all of the bug fixes

### 9/23/21
Yesterday
- I finished up the admin recovery page and finished that up
- Joel and I got a solution for the restore issue we had from group testing so we got that fix in as well and
- Later in the day I started working on the Organization Setup page refactoring for each page to have it's individual save buttons so

Today
- I just finished up the feature flags page so I'm going to move onto Tenant and hopefully finish that up today

### 9/22/21
Yesterday
- We had a group testing for recovery manager and that went really well
- Started working on the changes in the provisioner view that we talked about, got that done

Today
- But this morning, recovery had an issue deplying on dev and staging so Joel helped me look into that
- And today, I'll be working on finishing up the admin viewand I also have to go back to the tenant config to refactor the layout as well

### 9/21/21
Yesterday
- Yesterday I continued working on the recovery manager
- And also finished up a bug on the board for feature flags

Today
- We have a meeting to test recovery and after that
- I will be working on any bug fixes that come up and also a few other bugs on the board

### 9/20/21
Friday
- I had a prototype for the recovery manager refactoring and worked on that most of the day and also a few other small changes
- Finishing up that PR now and I will be out for a couple of hours this morning but I should be back online around 1 oclock and will continue working on recovery manager

### 9/17/21
Yesterday
- I made a lot of bug fixes and improvements to the recovery manager and got that PR up
- Also talked to Velvet and Joel on some of the ui refactoring ideas to indicate the status of the backups better so I made a prototype for that and Joshua I would like to show you that and hear your thoughts if you have time after standup


Today
- So today will be working on that and also have a few other small things I have to change in tenant and feature flags

### 9/16/21
Yesterday
- I continued working on the recovery manager tweaks and talking to Joel and Velvet throughout the day and

Today
- Will be more of the same

### 9/15/21
Yesterday
- I continued making changes to the recovery manager. Finished all of that and I also
- Had some build pipeline issues here and there but got that figured out with some help from Joshua

Today
- I'm talking to Joel on more hardening tasks for the page so I'll be working on that today

### 9/14/21
Yesterday
- I worked on a lot of small changes and fixes to the reocvery manager and talked to Lyna throughout the day on that
- That PR is up now and

Today
- I got the designs from the UX team for the logos so I'll be working on those and more hardening tasks today

### 9/13/21
Friday
- I added the recovery manager to the tenant configuration page
- And made a few other changes to fit that in common recovery
- I spent rest of the day testing and I found one main issue that I still haven't been able to figure out why it's happening

Today
- I'm going to be focusing on fixing that and also a few other hardening task

### 9/10/21
Yesterday
- Made more updates to the recovery manager and pushed that in
- I was hoping to test it on dev but the build never triggered the webroot angular build so I need to look into that
- And also Hunter finished the tenant config page so

Today
- I'm going back to add the page and adding the admin recovery manager page
- And once I finish that, I'll spend a lot of time testing everything

### 9/8/21
I was on PTO Friday afternoon and yesterday, but

Friday
- Morning I worked on bug fixes for the recovery manager and pushed that in and

Today
- Will be more of the same

### 9/3/21
Yesterday
- I continued working on implementing the recovery manager ui to webroot and got that done with some help from Jeremy and Craig so
- It should be on dev and staging for us to test now and

Today
- I have a demo meeting with a UX guy, Jared, right after standups, and then after that, I will be testing and looking for bugs to fix
- And I'll be on PTO in the afternoon

### 9/2/21
Yesterday
- I worked on getting the recovery manager page up on webroot
- Jeremy helped me on that throughout the day and
- I think I have all of the changes ready so I'm testing that now so

Today
- I'm going to try and get that done this morning and I'll be working on anything that comes up from that
- And if not, I'll be onto the organization set up page to add recovery manager there as well

### 9/1/21
Yesterday
- I was dealing with issues most of the day
- So the first things was my local environment running into an error but Craig and Chad helped me out on that like they said
- And I also had issues with recovery notifications and APIs but talked to Joel about that and found some bugs in my code that was causing those so I got all of those fixed and testing all of my other
- changes and finished a new PR

Today
- I'll be working on adding the recovery manager UI to webroot

### 8/31/21
Yesterday
- I finished up making changes to the organizations list component in the tenant repo
- Got that finished and also made the final changes to recovery but ran into an error so talked to Jeremy about that and he helped me out with that this morning so

Today
- I'm going to push that PR up but I'm also having some service fabric issues after reinstalling yesterday so I'll also be looking into that as well

### 8/30/21
Friday
- I finished up all of the refactoring for Joel's backend changes to recovery
- And also got all of the styling updated and tested the notifications as well so finished up that PR at the end of the day and today

Today
- I'm going back to tenant to make a small change and then
- Will be back on recovery to finish up the ui before I connect it to webroot

### 8/27/21
Yesterday
- I finished up the refactoring to match Joel's backend changes for recovery
- And after that I started working on a lot of the smaller tasks for the UI so

Today
- I'm going to get that PR up and also
- Joel's working on changes to the notifications so after he's done with that, I'll be making those changes and
- I also need to go back to tenant to make a small change there as well

### 8/26/21
Yesterday
- I continued working on the recovery manager and worked with Joel about his backend changes

Today
- Finishing up refactoring for that late yesterday so I'm working on a PR right now and after that, I'll be working on just hardening and try to wrap it up

### 8/25/21
Yesterday
- Continued working on making the changes to the recovery manager UI
- And talked with Joel throughout the day so

Today
- I'm going to do some testing this morning and then work on the styling and more smaller tasks after that

### 8/24/21
Yesterday
- We had a recovery manager meeting and came up with some refactoring to do
- So worked on that for the rest of the day and

Today
- Will be more of that and also coordinating with Joel on his backend updates

### 8/23/21
Friday
- I continued working on the recovery manager ui and finished up the admin page also with a lot of testing and bug fixes

Today
- I'll be doing more testing and then have a sync up meeting at 1:30

### 8/20/21
Yesterday
- I continued working on the recovery manager and putting in some final features in and some other bug fixes so

Today
- I'm going back to finish up the admin page and from there will be a lot of testing and bug fixes

### 8/18/21
Yesterday
- I continued working on the notifications for the recovery manager and got that done at the end of the day so working on that PR now and then after that

Today
- I will be working on a lot of the small tasks that I've been holding off on

### 8/17/21
Yesterday
- I started working on the notifications for recovery manager

Today
- And I'm hoping to wrap that up today

### 8/16/21
Friday
- I talked with Joel in the morning to talk about an issue with tokens
- And ended up figuring out a different issue also so I fixed that
- And then met with Jeremy to get some help on the recovery manager and figured out that I need to refactor some code
- I have a PR up for that

Today
- I will be working on notifications

### 8/13/21
Yesterday
- I found an issue in tenant so discussed with Jeremy on that
- And after he got that fix in, I added a small change to recovery manager, finished that pr
- And started looking through other repos to try and understand the notifications

Today
- I'm going to get some help from Jeremy on signalr and hopefully finish up signalr today

### 8/12/21
Yesterday
- I finished up the global pipelines page for the recovery manager
- And got some help from Hunter on a lot of the styling issues I was having
- That PR is up now so

Today
- I'll be working on implementing SignalR and updating the UI live accordingly

### 8/11/21
Yesterday
- I finished up a popup dialog for restore and restoring by capabilities
- Got a pr up for the UI but the restore operation itself is failing so

Today
- I'm going to be looking into that
- And then move on to fixing some of the styling issues and then the global pipelines page

### 8/10/21
Yesterday
- I'm still working on the recovery manager ui
- I got most of the organizations and system page done so created a pr for that
- And then start working on a dialog to pop up on restore

Today
- I'm going to continue on that
- And then work on one more task afterwards

### 8/6/21
Yesterday
- I fixed a bug in common tenant and then
- Went back to the recovery manager ui and created a pr for what I had so far
- Jeremy got the upgrades done at the end of the day but

Today
- I'm having issues with those changes so I'm going to try fix that and if I get solve that, then I'll continue on with the implementations

### 8/5/21
Yesterday
- I continued working on the recovery manager UI and

Today
- I have a couple of things to change that Jeremy mentioned and along with a few issues so I'll be working on that
- And hopefully get a PR up if I get to a good stopping point

### 8/4/21
Yesterday
- I continued working on the recover manager UI

Today
- I'm hoping to get to a good stopping point today so I can push all of the changes and Jeremy can work on the upgrade

### 8/3/21
Yesterday
- I spent the morning looking through the auditing checklist and some email things
- And then continued working on the recovery manager ui for rest of the day and

Today
- I will be more of the same working on the recovery manager

### 7/24/21
- I was out all last week so this morning I spent some time catching up on everything

Today
- I also looked through the board and I saw that there's a story for feature flag feedbacks. mark should I go ahead start on that or keep going with the recovery manager ui?

### 7/23/21
Yesterday
- I worked on a styling issue in activity monitor
- And then worked on the feature flag changes for rest of the day
- I'm basically done with that but I'm having issues with translation tokens so

Today
- I'm gonna look more into that more and
- Then have a meeting for the recovery manager
- Lyna also found a bug in the organization list so I'll try and fix that today as well
- Oh and also I'll be out for the entire week next week so if anyone needs anything let me know

### 7/22/21
Yesterday
- I continued working on the recovery manager ui and made some pretty good progress
- This morning, I found a styling issue for activity monitor so I'll look into that after standup and then

Today
- I also need to make the changes to the feature flags UI from Emma's backend changes but I'm not sure what that might look like exactly, so Joshua if you have any ideas let me know. And
- After that I'll be back on the recovery manager

### 7/21/21
Yesterday
- I continued working on the recovery manager UI
- Talked to Joel throughout the day as well as needed as well and

Today
- I'm almost done with the admin view so I will finish that up and then
- Move on to the provisioner view

### 7/20/21
Yesterday
- I cotinued working on the recovery manager UI and

Today
- Will be more of the same

### 7/19/21
Friday
- I finished up the organizaiton list component in tenant with help from Hunter like he said
- And I tested the changes to make sure everything is all working and it looks like it is so

Today
- I'm back to the recovery manager UI and getting start on the prototyping

### 7/16/21
Yesterday
- I pushed in a bug fix for an error jeremy found in feature flags
- Then moved back to tenant to finish up the organization list component and today

Today
- I'm still finishing that up
- And after that, I'll keep working on the recovery manager

### 7/15/21
Yesterday
- I continue working on the organization list component in tenant
- It's taking me longer than I expected but I got some help from Hunter and Stephen yesterday so it should be done soon and

Today
- After that, I'll get back on the recovery manager

### 7/14/21
Yesterday
- I worked on making small changes to feature flags throughout the day like Joshua said
- And then worked on a shared component in tenant that I'm almost done with that so

Today
- I'm going to be finishing that up today and then get back to working on the recovery manager

### 7/13/21
Yesterday
- I created a pr for feature flags to display the last modified date
- And continued working on the recovery manager but

Today
- I need to go back to feature flags and make changes to fit Emma's versioning changes that she talked about
- And I also need to make a new component in common tenant for the organization list to be used in the recovery manager ui so I'll be working on those today

### 7/12/21
Friday
- I got started on the layout for the recovery manager UI and connecting the API
- Then went back to feature flags to make changes according to Emma's updates

Today
- I'm doing some testing for the feature flags and that PR should be up soon
- After that, I'll be going back to the recovery manager

### 7/9/21
Yesterday
- I started looking into the new recovery manager UI
- I got some help from Jeremy setting up a new frontend project
- And then got the pipeline to build angular as well

Today
- I'm going to start on the new component and setting up the UI layout

### 7/7/21
Yesterday
- I worked on a lot of small changes and bug fixes
- And did some testing afterwards
- At the end of the day, Emma found a change I need to make so

Today
- I will be working on that and another spacing issue I found
- And I'll do more testing and take some bug fixes on the board if there are any

### 7/6/21
Friday
- I continued hardening for the feature flag changes
- Got a couple of PRs up and completed

Today
- I'm going to be testing those changes on staging
- And see if I can find any other issues
- And Joshua, like Emma said, if you have time to talk after standup that'll be great

### 7/1/21
Yesterday
- I spent time testing the feature flag changes on testing
- And found some things that I need to fix so I got that in at the end of the day

Today
- Will be more of the same and look into any other fixes or QA as well

### 6/30/21
Yesterday
- We had group testing for feature flags and
- I spent most of the day getting those changes and it should be up now
- And at the end of the day, got to fixing all of the load test tools

Today
- I'm going back to feature flags for a second to fix something and talk with emma on her changes
- And after that I'll get started on the QA tasks or any bug fixes

### 6/29/21
Yesterday
- I worked on a lot of the hardening tasks for feature flags and
- Also got to fixing the backend device load test tool error Lyna was having

Today
- We have the group testing
- And finish up rest of the tasks on the board

### 6/28/21
Friday
- I worked on finalizing all of the changes to feature flags and
- Got the PRs up for that
- Also met with Emma throughout the day

Today
- I have some clean up to do in the manifest files and
- I'm also waiting on that PRs to go through to dev so we can do some testing and fix anything if any comes up

### 6/25/21
Yesterday
- I continued working on the feature flag changes

Today
- I will be finishing that up

### 6/24/21
Yesterday
- We had a feature flags demo like everyone said and then
- Spent rest of the day fixing the bugs and making small changes

Today
- Will be more of the same

### 6/23/21
Yesterday
- I continued working on the feature flag changes
- Those PRs are finishing up now so I'm waiting on that to finish

Today
- We have a demo for Velvet on that
- I will spend rest of the day trying to get all of the changes applied on dev
- And any other issues that come up

### 6/22/21
Yesterday
- I continued working on feature flags

Today
- I'll be finishing it up

### 6/21/21
Friday
- Continue working on the feature flag changes
- And got to a pretty good spot with that so

Today
- I'll be finishing that up and start on the testing with Emma

### 6/18/21
Yesterday
- worked on the feature flag changes that we talked about from the meeting most of the day and

Today
- Will be more of the same 

### 6/16/21
Yesterday
- Continued my work on feature flag groups UI and I think I finished all of the implementations so

Today
- Will be a lot of testing and I should get a PR up by the end of the day

### 6/15/21
Yesterday
- I continued working on the groups feature flags
- I have all of the UI done and the API endpoints connected

Today
- I'm going to finish up the logic to keep track of the changes being made by the user

### 6/14/21
Friday
- I implemented the api calls to the feature flag groups ui
- Had to work on some refactoring from the conversation we had with Joshua

Today
- I have a 2nd COVID shot at 10 oclock
- And when I get back, I'll to be working on the add group dialog and hopefully finish that up today

### 6/11/21
Yesterday
- Continued working on the groups ui for feature flags and made really good progress

Today
- I'm going to start implementing the logic to connect with the backend apis

### 6/10/21
Yesterday
- I worked on adding a new component in identity to be used in feature flags
- had to cry to Hunter and Jeremy for help but I did get it done at the end of the day so

Today
- Back to feature flags to continue working on groups

### 6/9/21
Yesterday
- Finished up the force push button in feature flags and worked with Emma on that throughout the day
- Started brainstorming the groups implementations and I have a good idea now so

Today
- I'm getting started on that

### 6/8/21
Yesterday
- I continued working on the groups ui for feature flags
- And also had a meeting to discuss about that
- Spent rest of the day working with emma to add a force push feature where you can change the flags for everyone below the setting you're changing it in

Today
- I'll work on finishing that up and test it
- Get started on the groups feature since there's a lot of new changes that we discussed in the meeting

### 6/7/21
Friday
- Talked with Emma after standup and throughout the day about some feature flag stuff
- Then started working on the groups list implementation I have the basic UI done

Today
- I'm going to continue working on the UI and get started with connecting the backend
- And also have a sync up meeting for feature flags

### 6/4/21
Yesterday
- I finished up the organization manager PR and am almost done with the groups feature flags UI so

Today
- I'm meeting with Emma today to make sure that it's working and talk about the logic
If that goes well, I'll get that PR up and I'll start working on implementing that back in the
organization manager

### 6/3/21
Yesterday
- Continued working on the feature flag changes
- And chatted with Jeremy and Hunter throughout the day to get some help

Today
- I'm waiting on that PR to go through to make sure there aren't any more issues
- and then I will move on to the groups UI once that's done

### 6/2/21
Yesterday
- I had a few changes I need to make to feature flags so I got that done
- I then went back to common tenant and created a PR but had some merge issues so

Today
- I'll be working to fix that
- And then go back to feature flags to start implementing the groups feature

### 6/1/21
Friday
- Talked about changes to the feature flags UI with Joshua and Emma in the morning
- Worked on those most of the day and finished up the PR

Today
- I'm going to back to the tenant UI to add the changes from Friday

### 5/28/21
Yesterday
- Met with Emma in the morning like she said
- And I finished up the PR for the part of the feature flags UI update
- Also made some error detection changes to the performance test tool
- Then had a meeting with the UX team at the end of the day

Today
- I'm going back to the CommonTenant to try and get my feature flags menu to pop up in a dialog

### 5/26/21
Yesterday
- I finished up the feature flag implementations for setting flags globally and tenant wide
- Did some testing and
- Then created a PR and spent rest of the day fixing the things Jeremy mentioned in the code review

Today
- I will continue working on pushing the changes to master
- And work on preparing for the sprint review demo with Austin

### 5/25/21
Yesterday
- Continued working on the new feature flags changes
- Got all of the implementations done except for groups so

Today
- I'm going to finish up the UI changes and try to get a PR up for review

### 5/24/21
Friday
- I continued working on the feature flags changes to the front end
- Made some pretty good progress
- Talked to Emma throughout the day about some changes to the backend like she said

Today
- I'm going to keep working on the changes and hopefully finish up tenants menu

### 5/21/21
Yesterday
- Met with Emma in the morning to get clarification on her feature flags update
- Continued working on implementing those changes
- Got pretty far with that so

Today
- I will continue working on that same thing

### 5/20/21
Yesterday
- I had issues with running the v2 APIs feature flags locally so spent some time trying to fix that and also went back and forth with Emma throughout the day
- I got a new injectable component set up for the tenant menu
- Still working on connecting that to the updated endpoints

Today
- After standup, Emma and I are meeting just so that I can get a clarification on her implementations and also talk about what I'm thinking on my side
- And then I'll get started on setting feature flags globally

### 5/19/21
Yesterday
- Worked on adding a new feature flag and detecting that flag so that the UI is changed accordingly
- Then started creating a new injectable component and that took a little while but I think I got it now so

Today
- I will start implementing the v2 changes the new component and creating a new flag so the component can work for both tenant and global changes

### 5/18/21
Yesterday
- I started looking through the FeatureFlags enhancements
- I spent most of the time trying to understand everything and reading though the wiki for adding a new feature flag
- I think I have a pretty good idea of the direction I need to go and I also did get a new feature flag going for the enhancement changes so

Today
- I'm going to continue working on that

### 5/17/21
Friday
- Spent most of the morning time reading through the wiki and looking through code to try and understand everything on the frontend
- Started working on the tenant edit page's UI changes in CommonTenant and I think I got all of that done
- I am still waiting on an update with a part of the design so I will finish that once I get that back from the UX team

Today
- I'm planning on getting started with Feature Flags and look into how the APIs are being called so I can start making changes with the new v2 endpoints that Emma implemented
- And then work on the rest of the UI changes

### 5/14/21
Yesterday
- Met with Joshua and Emma like they said to look over the UX design for feature flags and talk about the changes that I need to make on the frontend
- Spent rest of the day to look through the CommonTenant and CommonFeatureFlags repo to try and understand them
- Messaged back and forth with Jeremy about some of the questions I had

Today
- Still not understanding it fully so I'm going to go back to the documentation to re-read the UI wiki page again
- Then I'll get started on looking into the organization set up page and start making changes

### 5/13/21
Yesterday
- We had the demo after stand up
- And worked on a couple of things for the tool and pushed up the final version to the master branch
- I updated the documentation with new configurations and how to download the tool from the artifacts
- I'm pretty much done with the performance test tool for now so Joshua and/or Mark if we can talk about what I need to get started on whenever you get a change that'll be great

### 5/12/21
Yesterday
- I worked on hardening the tool and also running with multiple clients
- I was able to test from my machine for 30 minutes with 5 clients and an hours with 10 clients and they both seemed to have worked pretty well
- In the afternoon, I started preparing for the demo we have today after standup and also talked to Austin for a bit about that

Today
- We have the demo
- After that, I'll make sure the wiki has everything that is needed
- And push the final version to master

### 5/9/21
Yesterday
- Morning, I had to go back to the localization changes to the CommonLibraries repo since the build didn't go through for some reason and got that working now
- Updated the wiki with the workflow of the tool and also the errors that you may run into and how to fix those
- Went to the VM to run some tests but with it only having 8GBs of RAM, it was running out of memory when using multiple clients

Today
- I'm planning on trying to optimize the program better and see if I can find any memory leaks
- After that, I'm hoping to run a big test and see what I can find from that

### 5/8/21
Yesterday
- Hunter and I continued working on adding the localization changes to all of the repos
- I made a few mistakes so I had to cry to Hunter and Joshua for help a few times but
- We did get all of the updates pushed up and everything seemed to be working

Today
- I will go back to the performance load test unless something comes up
- I'll add the workflow to the wiki explaining how the tool works
- And any errors that can happen and how to fix those
- And also try and run the test on the VM as well

### 5/7/21
Yesterday
- Started implementing the localization changes to all of the repos with Hunter
- We got pretty far I think we have about 5 or 6 more to go

Today
- So I will be working on the rest of that today

### 5/5/21
Yesterday
- I was having internet problems here and there but spent most of the time just preparing for the demo and seeing if there are any bug fixes I need to work on
- Also ran a small test and found out that turning off notifications seemed to work better when interacting with cards or the map

Today
- I will work on wrapping up the load test tool for the sprint
- There are a few things that I need to add to the wiki and I think I also messed up the attachments in the gitignore file so I'll look more into that today

### 5/4/21
Yesterday
- Met with Austin to talk about the demo for the sprint review
- Then went to go get the first dose of the vaccine but luckily I was feeling completely fine
- In the afternoon, I tried to test all of the things Austin and I planned on doing

Today
- I'll continue to work on that to see if there's anything in the tool I need to fix

### 5/3/21
Friday
- Cleaned up the code and pushed the completed version of the frontend performance test tool the master branch of CommonWebroot
- Also wrote the documentation for the tool on the wiki and finished that as well

Today
- Austin and I are getting on a call after standup to talk about the sprint review and planning what we can do
- I also have an appointment for the vaccine at 10:45 so I will be out for a bit around that time
- Rest of the day, I will work on preparing for the sprint review demo and fix any issues that I run into

### 4/30/21
Yesterday
- Had a sync up meeting for the performance test like they said
- After that I started running some tests but found out that the tabbed space bug is still there so talked to Jeremy for a bit
- Then also made some configuration file templates for different scenarios of a test

Today
- Do some cleanup of the code before I push it back up to the master branch
- I'll work on the documentation of the tool and see how far I can get

### 4/29/21
Yesterday
- Implemented fixes for all of the bugs that I could find in the front end performance test tool
- Started working on the documentation for the tool

Today
- We have a sync up meeting for the end to end load test
- So I'll spend this morning preparing for that and running some tests
- Then the rest of the day depends on how the meeting goes

### 4/28/21
Yesterday
- Finished up adding modularity to the card interactions in the performance test tool
- Did some research on recording the network tab in the chrome dev tools but ran into limitations with the versioning of Selenium so left that alone for now
- Ran a lot of different test scenarios to see if I can break any of the test and ended up finding some bugs that I need to fix

Today
- Most of the morning time I'll spend hardening the tool and doing some testing after that
- After that, I'll work on pushing the code up to the master branch and writing some documentation on the wiki

### 4/27/21
Yesterday
- Added a new logic so in case of a failed test, the test should always log out if the user is still signed in
- Added an additional feature to the filtering of the card so that when you don't configure what kind of cards to interact with, that filtering function is ignored
- Continued on adding more modularity to interactions with the cards but had some errors and I realized that some of the common cards aren't in the exact same architecture for the different entities so I just put in a fix for that

Today
- I will be running some tests to make sure everything is working and then move on to doing some research on recording network traffic from the chrome dev tools
- And get started on implementing that if possible

### 4/26/21
Friday
- Implemented changing of priority when posting in channel
- The test now takes a screenshot of the current state of the UI when an error is detected
- Started working on adding more modularity to interactions with card

Today
- I'm going to continue working on that
- And do some research to see if I can record the network tab in devtools using Selenium

### 4/23/21
Yesterday
- Worked on outputting the configurations files after each test so you can see all of the configurations you set for that specific test
- Implemented filtering feature for interacting with the card so you can tell the program what kind of entity to interact with by the title name or the tenant
- Ran into issues with chat and channel where sending an attachment can slow the UI so got that fixed as well

Today
- Notifications testing seems to run into issues once in a while so I'll look into fixing that this morning
- Then move onto creating more modularity in the functions
- Rest of the day I'll continue to harden the tool and work on more clean up the code

### 4/22/21
Yesterday
- Chased down the bugs that I caused from the new features that I added Tuesday
- Finished up reactions for channels and implemented reactions for chat and completed testing for that so that seems to be working just fine

Today
- I have a few more small features to add
- And the rest of the day I'll just spend hardening the tool and making sure it can catch any errors during the test

### 4/21/21
Yesterday
- Implemented a lot of the small tasks that I discussed with Joshua on Monday
- Finished up viewing entities on the map which should drive the tiles to load
- Updated the memory log to record the timestamp, updated all of the json files to print out throughout the test instead of just at the end so you can see everything live
- Worked on clearing the unmanaged alarms
- Also finished up creation of new channels when configured

Today
- I ran some tests in the morning and it looked like the new features broke a few things so I'll have to chase that down
- Then move on to the reactions in chat and channel
- I think chat may be a little hard to implement since I was having issues before
- I can also run some load tests related to the memory leak and see if I can contribute to figure out that issue as well

### 4/20/21
Yesterday
- Ran some tests on the VM in the morning
- Then met with Joshua to talk about the progress of the performance test tool and some improvements that can be made
- Spent the rest of the day implementing those and doing some research for the interactions with the map

Today
- Today will be more of the same
- Hoping to finish up the reactions for chat and channel, interaction with the map but in the alternative way that Joshua mentioned yesterday, and then clearing alarms from the UI

### 4/19/21
Friday
- I wrapped up the chat and channel implementation that I was working on for last week
- Combined all of the previous tasks and ran a big load test to make sure everything was working fine

Today
- I'm going to run a test on the VM since I was previously having trouble with that and see how that goes
- I'll probably be facing some issues so if I can solve that, I'll move on to the documentation of the tool and getting ready to push the final version up soon

### 4/16/21
Yesterday
- Spent most of the day debugging a lot of the small issues that I've been holding off to fix for a while now
- Some of them took longer than expected but most of it should be done
- Still have a couple of more things on the list that I need to validate and/or fix
- But I also added a hard exception handling that can catch any error and then refresh the page if needed to restart the test at any time

Today
- Attempt to finish up the rest of the bug fixes
- I'm wanting to run a load test with all of the features together and see how that goes

### 4/14/21
Yesterday
- Continue working on the load test tool for Channels
- I have all of the features implemented but the tool runs into a few problems here and there so today will be mostly debugging and testing what I implemented yesterday
- Hoping to get back to a lot of small bugs that I've been avoiding for a while and trying to get that done

### 4/13/21
Yesterday
- Continued working on the front end side of the performance test tool
- Finished up chat
- Started working on channels and got a really good foundation

Today
- Will be continuing to work on the channels and hopefully finish that up

### 4/12/21
Friday
- Worked on the automation for the interaction with chat of the performance test on the front end side
- Actually got most of it done
- Finished up configurations for who to send the chat to, the different messages you can send, and also attachments so that can drive the backend to get some load
- Of course did some load tests and error handling

Today
- Try to finish up the chat in the morning
- Adding features to send messages to multiple users, leaving the chat, and things like that
- Planning to get started on channels in the afternoon

### 4/9/21
Yesterday
- Merging of the performance test tool up on the master branch of CommonWebRoot finished up
- So started working on the documentation on how to use that on the wiki
- Got that finished
- Started working on implementation for the chat load test and got to a pretty good spot with that so I will be working on finishing that up today

### 4/8/21
Yesterday
- Worked on hardening the performance test tool and ran some small tests with Austin to make sure all of the implementations were working
- That went well so I went ahead and created a PR for the updated version of the tool
- In the afternoon, I worked on setting up the VM and running the tests there
- There were a few small hiccups here and there but I think it should work fine now

Today
- Start working on the documentation for the tool on the wiki
- Afterwards, I will start on implementing interactions with the chat
- I have an eye doctor appointment at 3:30 so I'll getting off a little early today

### 4/7/21
Yesterday
- I added a lot of small improvements to the performance test tool from what we talked about in the sync up meeting Monday
- I worked on refactoring the architecture so that now I can configure what part of the connect site I want to focus on interacting with
- Got to a really good spot
- Also tried to implement interactions with the map but still having trouble there so I'm going to have to do some more thinking

Today
- I'm going to do a little more clean up and testing this morning, and after that, I'll go ahead and push all of the changes to the master branch and see if I can get the test running on the VM

### 4/6/21
Yesterday
- Had a performance test sync up meeting in the morning to discuss our progress and where to go from here
- The meeting went really well so spent the afternoon making some of the small changes that we have talked about
- Also got to test some of the front end changes I made last week but the devices console log wasn't working so ended up asking Jeremy for help

Today
- Apparently it was a versioning issue so created a PR for that this morning
- So for the rest of the day, will be doing some refactoring to the code from the meeting notes from yesterday
- Try to finish up interactions with the map as well

### 4/5/21
Friday
- In the morning time, met up with Austin to run a load test on staging to test our tooling
- Spent the rest of the day hardening to tools and fixing minor bugs that I found from the test
- Also added more configurations and made some notes to prepare for a sync up meeting today

Today
- Have the sync up meeting for performance test like I said earlier
- And the rest of the day depends on the content of that and hopefully get some directions going forward

### 4/2/21
Yesterday
- Worked on adding console logging from the frontend for all HTTP requests and Signal R data for Alarms and Assets so I can read that information in the performance test tool
- Got the PRs done for both
- Worked on hardening the tool and running some small tests but found an issue where the client behaves differently when running headless

Today
- This morning I figured out the issue to be the window size set differently on headless so the DOM was a little different but fixed that issue
- Today after standup, Austin and I are planning on get together to run a test so we can test our tooling
- Rest of the day will be mostly hardening the tool and cleaning up the code

### 4/1/21
Yesterday
- Worked on interacting with the map on the performance test tool
  -Finished up zooming in and out but couldn't get the drag to work
- So moved on to interacting with devices, alarms, and assets
  - Got most of the features implemented but it seems like I need to do some digging to find the issues that I was running into when I ran a small test at the end of the day

Today
- I'm going to look into fixing those bugs and more hardening, and also adding configurations in min and max format
- Austin seems like he is getting pretty far with Alarms so I'm going to implement the Common Logging for the frontend for Alarms and Assets

### 3/31/21
Yesterday
- Continued to work on the front end side of the end to end performance test
- Finished up implementation for interacting with units and notifications
- Started working on the map at the end of the day but could not figure out how I can move on the map with either drag and drop or arrow keys

Today
- Will do more research on that. Have some ideas on what I can try but if it doesn't work, will go ahead and get started on the 2nd half of the interactions which will be alarms, assets, and devices

### 3/30/21
Yesterday
- Started working on refactoring the front end performance test according to the discussion from last Friday in the sync up meeting
- There was a good bit of changes I needed to make then I thought so that took longer than I expected but I did get a really good foundation to build on top of today and also finish all of the incident interactions

Today
- Going to move on to finishing up units and notifications
- Start working on interacting with the map

### 3/29/21
Friday
- Had a meeting for the performance test with Mark and Joshua to teach us the dynamic duo or the youngins I forget what Mark calls us but we talked about the devices and how other capabilities work with that
- Started working on a plan going forward and how all of the front end automations will work
- Set up a workspace and the tabs specifically designed for the load test
- Also implemented assets and alarms reading from the console on my end just so I can focus the user interactions for today

Today
- Aim to finish up the interactions with incidents and units
- So tomorrow I can get started on devices

### 3/26/21
Yesterday
- Started implementations for the devices
- Got the frontend data logging for the creates, updates, and deletes to the console
- Got the script to enable reading that data (need testing)
- Finished up triggering the test to end at any time
- Combined all that later in the afternoon and ran some tests (seem to go pretty well)

Today
- Have a performance test sync up
- Test devices and hopefully finish that up
- Work on a few minor bug fixes that I found from yesterday's test

### 3/24/21
Yesterday
- Worked on some minor bug fixes and cleaned up some code for the performance test tool
Pushed that to the repo but had some build issues and I think Joshua is going to try and make an
exclusion if he has time
- In the afternoon, met with Austin and trying to figure out how I can add a manual trigger to end the test anytime
- That implementation took longer than I thought but did get that finished
- This morning, I removed the entityID attributes from the DOM that I added last sprint for incidents, units, and devices since there is no need for that now

Today
- Look into the build issues like I said earlier
- Start some documentation on what I've worked on and some of the ideas I have for moving forward
- May get started on logging devices on the frontend and adding the data recording part for the script as well

### 3/23/21
Yesterday
- Mostly finished implementations for functions to interact with incidents and units for the frontend side of the performance test tool
- Ran different cases of load tests to test my script. Most of the tests seems to run perfectly.
- Found a bug that I just fixed this morning. Took me a little while to replicate.

Today
- I have a few more minor tweaks that I needs to make
- Afterwards, I'm going to run some more tests just to validate the fixes
- And work on cleaning up the code so I can push the code up to the repo this afternoon or maybe tomorrow

### 3/22/21
Friday
- Was able to get a lot of small tasks done for the front-end script of the performance test tool
- Finished functions for switching tenants, workspaces, presets and tabs
- Finished up all of the metrics that I could think of to print out in a log file and also the configurations
- Research any ways that I can trigger the unit test to end at any time but couldn't find any way so ended just simply adding the date to the end time configuration so running the test for multiple days should be possible now

Today
- Finish up automations for interacting with incidents and units
- Planning to run a small load test so I can test all of the things that I worked on Friday and see if I can improve and prepare for the big load test soon

### 3/19/21
Yesterday
- Worked on hardening the load test tool specifically on the data reading aspect
- Got to run a small load test with Austin for incidents and units concurrently and that seemed to work perfectly
- After the meeting, I had a lot of small tasks going forward so ended up spending time organizing those and documenting them

Today
- I'm going to focus on preparing for user interactions so a lot of small tasks from my notes
- Like swapping tenants, workspaces, and presets
- Making sure I get all of the edge cases and error detections
- I also have some research to do so that's what I'll be working on today

### 3/18/21
Yesterday
- Continued working on the front end load test
- Finished up hardening for reading data from the console for incidents and units
- Added more metrics for the result output
- Made some changes to the load test harness script
- Started working on hardening for the front-end

Today
- Few changes to the metrics
- Add a few more configurations
- Finish up hardening for the front-end interactions with incidents and units
- Start adding more cases of user interactions afterwards

### 3/17/21
Yesterday
- Finished up reading incidents from console and got that tested
- Worked on making changes to the frontend to call CommonLogging for Units (created PR)
- Met with Austin for a sync up and he suggested that I would use the nuget package to create Incident and Units objects for better modularity instead of creating my own classes
- Had trouble with dependencies yesterday but finally got that figured out this morning

Today
- I'm going to finish up reading from the data from the console
- And start on the hardening for that since Austin seems like he's in a good spot

### 3/16/21
Yesterday
- Worked on recording the incident data from the console
- Took me longer than I expected just because I had to combine the SignalR response I get and the API calls from the HTTP response but I think I have that finished

Today
- Will run some tests to make sure incidents data is caught and stored correctly
- Move onto units but that shouldn't take a long time
- Continue to work on the frontend automations

### 3/15/21
Friday
- Worked on recording the metrics into a log file after the test for the performance test script
- Listened in on group testing meeting for activity monitoring
- Then moved on to recording of the data itself from the console
- Ran into issues of reading objects so ended up changing the frontend to return the string of the object instead of the object itself
- Got help from Jeremy
- Created a PR for that change and the changes looked good on the dev

Today
- This morning, I will finish up recording of the data
- Adding more configurations to the test
- And continue adding more automation scripts

### 3/12/21
Yesterday
- Worked on a lot of the refactoring for the automation script
- Started testing for incidents, basically done with that
- Still not seeing Jeremy's changes on the dev for the console logs, so Jeremy if you could take a look at that sometime today if you have time, that'll be great. I could also be doing something wrong so not sure why.
- Also had group testing for notifications
- Mark, the issue you encountered with yesterday at the notifications group testing where you expand on a unit and you can't scroll down afterwards, we said that was only for units on staging, but I noticed it was there on incidents also on dev this morning. Don't know how helpful that is but wanted to let you know.

Today
- Finish up testing for incidents
- Start on units but that should be very similar so shouldn't be too hard
- Group testing for activity monitoring
- Hoping to get to reading data from console log

### 3/11/21
Yesterday
- Had a meeting with Jeremy and Joshua on the frontend like they said
- Talked with Joshua afterwards on some automation ideas and moving my 2019 project into 2017
- Started working on setting up an architecture for the new approach
- Got to a really good spot there. Ready to implement new scripts.

Today
- Group testing for notifications
- Start implementing some automations
- Get started on reading the console log and catching data from there

### 3/10/21
Yesterday
- Had a performance test meeting at 11
- Prepared my script and a demo until then
- The meeting went well
- We discussed how we can approach the front end better
- In the afternoon, I spent a lot of time playing with the front end so I will have some ideas to automate real user interactions
- Took some notes

Today
- Meeting at 10 with Jeremy and Joshua on how I can record the front data better
- Will continue to work on the content of the meeting for today

### 3/9/21
Yesterday
- Kept working on the scroll bar that I was running to issues to Friday
- Ended up having to use a JavaScript query but that's working now
- Kept working on adding finishing touches to the notifications, got to a good spot there
- Ran a couple of tests to test my tooling
- Had to add some error handling this morning

Today
- Have a performance test sync up meeting like they said, and the rest of the day depends on that
- Probably a lot of clean up and pushing the code
- Maybe even get started on devices

### 3/8/21
Friday
- Continued to work on the performance test for Units
- Made a few fixes
- But have been running into a lot of issues with scrolling on elements

Today
- I think I finally got that working just now, so will be adding more to that today
- Also, have not yet finished with reading notifications so I'm hoping to get all of that finished today

### 3/4/21
Yesterday
- I've been using a tool called Taurus to turn my front end unit test into a load test with multiple
clients
- Talked to Joshua a bit, since this is a python project, I worked on implementing this tool in a PowerShell script to simplify the build process. Got that done.
- Yesterday, I edited the front-end for devices to add entity id, created a PR for that
- Also met with Austin to discuss testing of units
- Rest of the day was spent working on reading units from the dom. Realized that I need to change my method a little so

Today
- Will continue to work on that today

### 3/3/21
Yesterday
- Updated the incidents to read the entity id from card component attribute
- Ran some tests to ensure that it was working
- Updated units to also read the entity id and use that as the unique identifier
- Start working on notifications and setting up an architecture since it was previously designed just to listen to incident notifications

Today
- Going to continuing to work on notifications but implement units
- Hoping to get to a good spot there by the end of the day
- Catch different pages that can be loaded like 502 and onboarding process so it can act accordingly and not get stuck

### 3/2/21
Yesterday
- Met with Jeremy to get help on setting up the Angular environment
- Got that set up and spent some time looking through the folder to try and understand the architecture and also read some of the wikis
- Started working on adding the entity IDs as attributes for the common-card component and finished that for Incidents and Units
- Created a PR for both

Today
- This morning I looked through the staging and the dev environment to make sure the changes took place correctly
- Working on implementing a read for incident IDs in the performance test script
- Hoping to get a small test run in for incidents
- Continuing to work more on load testing units that I took a pause on last week

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
Yesterday
- Visual Studio Web Test
  - Only supports Internet Explorer
  - Record http requests with Fiddler
  - Import into visual studio and had trouble with authorization: 401 unauthorized
  - Figured it out this morning how to provide credentials (access token) with header
- SignalR Load test
  - Research on using SignalR
  - Met with Chad on running SignalR client and listening to live updates for Incidents
  - More explanation on where the data is all stored for future testing

Today
- Start increasing requests and adding validations
- Test SignalR with different services
- Research SignalR load testing tools


### 1/12/21
Yesterday
- Requested for a license: needed justification, now approved
- Downloaded Visual Studio Enterprise and confirmed license
- Met with Austin on back-end performance testing through the PowerShell
- Started research on front-end load testing using Visual Studio
- Installed an extension for performance testing

Today
- Continue research and start testing some of the Visual Studio's testing capabilities
- Research into testing SignalR connections
- Maybe meet with Austin as needed

### 1/11/21
Yesterday
- Finished onboarding: installing services and running though Service Fabric, verified
- Got help from Craig on debugging each service individually
- Brief overview of what each service is used for, and the Azure Portal
- Updated the onboarding Wiki
- Started researching load testing and reading into Austin's research

Today
- Need to talk to Mark about what to do going forward

### 1/7/21
Yesterday
- Meeting with Austin, Mark, and Joshua about the performance testing tools
- Continued the onboarding process and got help from Austin
- Updated the CommonIdentity repo's UserManifests so I will have access to Local, Dev, and Staging
- Met with Craig for some explanation on the pipeline and some additional questions
- Got the Antivirus policy updated to the Developer Systems

Today
- Start installing the services with the updated Antivirus policy and get help as needed
- Set up Swagger Service APIs
- If finished onboarding wiki, update the wiki as needed

### 1/6/21
Yesterday
- Onboarding wiki finished
  - Certificates
  - VPN to Galileo DEV (still needs testing)
- Researched and understood most of the big picture system architecture of HxGN Connect

Today
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
