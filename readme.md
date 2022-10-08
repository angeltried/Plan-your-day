# Schedule for the day

## Git clone

Go to github.com and looked up the public repository of module 5. Copy code and
clone with your terminal (mac) into a folder. Open files in vs code.

### Acceptance Criteria

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

#### Angels walkthrough

* html
  1. Cloned starter code into other folder then made my own folder with new repository.
  2. moved the links to one line each.
  3. Inside container i will start with div for time block to make area a row for each hour of the day using grid system also giving name of class for starter code css and self made java later.
  4. Inside the time block div add a  personal div for the time of the day.
  5.  i will add, text area and a button to save time inside first div.
  6. inside button i will add class name for starter code css and java ater and class fas fa-save to look link a save icon.
  7. i will start messing with the col- in each class to position everything like the example. 
  8. start copy and paste the time-block div for each hour of the day.
  9. edit the hour and data-hour for each row.
  
* css
1. made a boodstrap file and  bootstrap mini  download copy paste code 
2. give body default style.
3. start with looking as classes on html to start styling.
4. jumptron header with top of page.
5. make sure time block has text in center
6. give row space and a white border to seperate when it shows color for time
7. give stlye to the hours with a dashed border.
8. give color to past present ans future when the occure
9. style the save buttons

* Java
1. made a bootstrap file and bootstrap mini download copy paste code.
2. start with adding current time and date.
3. make function to initialize schedule
4. for each time block will attach data hour 
5. set todo object to relate hour and accpect text
6. set a local storage to do items
7. for each time clock it will allow to show what part of the day it is.
8. loop thru array then assign the text to the timeBlock with data-hour equal to hour.
  
    
  
##### Turn in

  Make a repository with a unique name. Made folder in my happy face finder day planner inside folder then git clone ssh of new repository using terminal. Save as readme.md into plan your day folder then using vs code create index.html and then folder for assets (styles.css). Git push into repo with intergrated terminal git init , git status, git add . , git commit -m "comment", git push -u origin main