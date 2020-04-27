# Third-Party APIs: Work Day Scheduler

The goal was to create a simple calendar application that allows the user to save events for each hour of the day using third-party APIs. This app runs in the browser and features dynamically updated HTML and CSS powered by jQuery. This app uses the Moment.js library in the browser to work with date and time. Moment.js library allows you to parse, validate, manipulate, and display dates and times in JavaScript.

This Work Day Scheduler is aimed towards employees with a busy schedule who want to add important events to a daily planner so that they can manage their time effectively.

## Installation
```
i. Fork the Github repository.
ii. Clone the forked repo into your local machine using gitbash/terminal to pull the project and data.
iii. Access the index.html, style.css and script.js files and assets via Visual Studio or in your browser to view the code and website respectively.  
iv. Open and explore the planner.
v. Enter and save events into the planner. 
```

## Usage
jQuery Components Used:
```bash
Moment.js library - functions - DOM methods - window object - jquery selectors - jquery callbacks - append - timers - event delegation - client-side storage 
```

See animation below which demonstrates the application functionality:
![Work Day Scheduler](/assets/Thirt-Party-APIS-homework.gif)

## Key Checks Included ensuring the following:
Given I am using a daily planner to create a schedule:
1. When I open the planner, then the current day is displayed at the top of the calendar
2. When I scroll down, then I am presented with timeblocks for standard business hours
3. When I view the timeblocks for that day, then each timeblock is color coded to indicate whether it is in the past, present, or future
4. When I click into a timeblock, then I can enter an event
5. When I click the save button for that timeblock, then text for that event is saved in local storage
6. When I refresh the page, then the saved events persist