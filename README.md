# Jira Sub-Task Creator 

[![Chrome Web Store](https://img.shields.io/chrome-web-store/v/acdnmaeifljongleeegkkfnfcopblokj.svg)](https://chrome.google.com/webstore/detail/jira-sub-task-creator/kpkkhaidgijhkojdnfangmdihodjocjm?hl=en&gl=IE)

As a Scrum Master, I had to manually create all the Sub-tasks for the Stories that were Ready for the Sprint.

The process takes some time, having to create 8-10 Sub-tasks for each Story (around 20 per Sprint), 
when 5-6 of them were Default Sub-tasks, the same for all stories. This (tedious) process was taking me around 1-2 hours per Sprint,
depending on the amount of Stories.

Having that in mind, I used the REST API call provided by Jira and created a Chrome Plug-in
where you can create all the sub-tasks for the Stories you need in just 1 click, cutting down the time spent on this to seconds.

## Pre-Reqs 

You need to be logged in Jira in order to the Plug-in to work.

When you are creating a new sub-task, DO NOT CLICK outside the plug-in, doing so will lose all your changes.

After clicking the CREATE button, wait for the timer to click away as Jira needs some seconds to process the request.

## Set up
1. Clone this repo
2. Go to chrome://extensions/
3. Enable Developer mode
4. Click load unpacked
5. Select the subdirectory "JiraSubTaskCreator" in the repo you cloned
You should see an icon for the extension now.

## New Features for SilverCloud
* Changed subtasks to SilverCloud specific subtasks
* Adds time on subtask creation for PO Review, Peer Code Review 1/2
* Template drop down/button now copy SilverCloud templates to the clipboard

