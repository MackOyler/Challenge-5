# Workday Scheduler

![screenshot of site](https://camo.githubusercontent.com/6dbc0065ce426c1f77274ee9d33de6e0d1765f3296bf997c4ff71c66e82e1627/68747470733a2f2f7261772e6769746875622e636f6d2f727761796e65776869746531352f4461696c792d576f726b2d506c616e6e65722f6d61696e2f6173736574732f696d672f73637265656e73686f742e706e67)

## Live Deployment Link
-[Scheduler](https://mackoyler.github.io/Workday_Scheduler/)

## Learning Goals

The purpose of this webpage was to create a workday scheduler that would be able to be saved and not lose data after refreshing or closing. 

## Development Team
- [Mack Oyler](https://www.linkedin.com/in/mack-oyler/)

### User Story
AS AN employee with a busy schedule
I WANT to add important events to a daily planner
SO THAT I can manage my time effectively

- GIVEN I am using a daily planner to create a schedule
  -WHEN I open the planner
    -THEN the current day is displayed at the top of the calendar
  -WHEN I scroll down
    -THEN I am presented with time blocks for standard business hours
  -WHEN I view the time blocks for that day
    -THEN each time block is color-coded to indicate whether it is in the past, present, or future
  -WHEN I click into a time block
    -THEN I can enter an event
  -WHEN I click the save button for that time block
    -THEN the text for that event is saved in local storage
  -WHEN I refresh the page
    -THEN the saved events persist
