05 Third-Party APIs: Work Day Scheduler

Your Task
Create a simple calendar application that allows a user to save events for each hour of a typical working day (9am–5pm) by modifying starter code. This app will run in the browser and feature dynamically updated HTML and CSS powered by jQuery.
You'll need to use the Day.js library to work with date and time. Be sure to read the documentation carefully and concentrate on using Day.js in the browser.

User Story

AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively



Acceptance Criteria

GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with timeblocks for standard business hours of 9am&ndash;5pm
WHEN I view the timeblocks for that day
THEN each timeblock is color coded to indicate whether it is in the past, present, or future
WHEN I click into a timeblock
THEN I can enter an event
WHEN I click the save button for that timeblock
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist#

https://github.com/Haid91/Work-Day-Scheduler

https://haid91.github.io/Work-Day-Scheduler/



Pseudo code for html
typical
allows save button to have the icon "save" optional
font families
use of bootstrap component
list timeblocks from 24 hour clock and 12 hours clock translation
jquery and moment links from https://cdnjs.com/libraries/day.js/
Pseudo code for css
typical setup using html attributes and classes
Pseudo code for js
tells engine to load 1)html & 2)css first.
display current day & time.
get nearby values.
taken the change from the sibling html description attribute
taken the change from the parent html id attribute
set items in local storage.
load any saved data from LocalStorage - do this for each hour created. Should follow html 24 hour to 12 hour conversion.
get current number of hours.
use of moment.js
loop over time blocks
check if we've moved past this time, click into css/html given classes of past, present, or future
re-run function
