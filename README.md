#Task Manager QA

A task tracking application designed to monitor tasks and measure the time taken to complete them.

The application focuses on tracking the task lifecycle and providing clear visibility into how long each task takes.

##Current Features
*Create and view tasks
*Track task details using Task Name and Task ID
*Record the time when a task is received
*Start and stop task tracking
*Track the time taken to complete a task
*Display task status and completion information
*View task details on a dedicated Task Page

##Task Time Tracking

Each task can be tracked from the moment it arrives until it is completed.

Task Received → Task Started → Task Completed

The application records:

*Task Name
*Task ID
*Received Time
*Start Time
*Completion Time
*Total Time Taken

This helps users understand exactly how many minutes are required to complete each task.

##Files
*index.html — Main task management page
*task.html — Individual task details and time tracking page
*style.css — Application styles
*script.js — Task management and time tracking logic

##Data Storage

Task information is currently stored using the browser's localStorage.

This means the application works without a backend or database for now, and the data is stored locally in the user's browser.

##Future Improvements
*Task reports and analytics
*Daily and Shift completion reports
*Average task completion time
*Export task reports
*Backend and database integration
*Multi-user task tracking

Current Focus: Building a reliable task page that accurately tracks when a task comes in, when work starts, when it is completed, and the total time taken.
