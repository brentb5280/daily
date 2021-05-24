# daily
# calendar


GIVEN I am using a daily planner to create a schedule
WHEN I open the planner
THEN the current day is displayed at the top of the calendar
WHEN I scroll down
THEN I am presented with time blocks for standard business hours
WHEN I view the time blocks for that day
THEN each time block is color-coded to indicate whether it is in the past, present, or future
WHEN I click into a time block
THEN I can enter an event
WHEN I click the save button for that time block
THEN the text for that event is saved in local storage
WHEN I refresh the page
THEN the saved events persist

What I did 
-I added a "Script.js" file to insert the javascript 
-I added the vaibles for the day 9am - 5 pm
-Set up the local storage 
-I changed the Font entered in CSS from white to black to make it easier to read
-added the save button function 
-set up the saved data in the local storage 
