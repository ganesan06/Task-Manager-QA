# Task Manager QA

A task tracking application designed to monitor tasks and measure the time taken to complete them.

The application helps users track the complete lifecycle of a task, from the moment it is received until it is completed.

## Current Features

* Create and view tasks
* Track tasks using Task Name and Task ID
* Record when a task is received
* Track start and completion time
* Calculate the total time taken to complete a task
* View task details on a dedicated Task Page
* Display task status and completion information

## Task Workflow

**Task Received → Task Started → Task Completed**

For each task, the application tracks:

* Task Name and Task ID
* Received Time
* Start Time
* Completion Time
* Total Time Taken
* Task Status

## Files

* `index.html` — Main task management page
* `task.html` — Task details and time tracking page
* `style.css` — Application styles
* `script.js` — Task management and time tracking logic

## Data Storage

Task data is currently stored in the browser using `localStorage`. No backend or database is required for the current version.

## Future Improvements

* Daily and shift completion reports
* Task analytics and average completion time
* Export task reports
* Backend and database integration
* Multi-user task tracking

---

**Current Focus:** Building a reliable task page that accurately tracks task timing and completion.
