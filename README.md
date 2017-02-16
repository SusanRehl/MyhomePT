# My Home Physical Therapy App

## Purpose:
1. Accurately record the exercises prescribed
2. Make exercises easily available for reference
3. Ability to set reminders to exercise
4. Log exercise performance

## Features:
1. Setup the app for your personal use
     A. Create account and login
     B. Create an exercise set. A person can have multiple exercise sets. For example, frozen shoulder, sprained ankle, carpal tunnel.
     C. Dashboard lists your exercise sets, and allows you to edit or delete them and create a new set. Also allows you to make each set active or inactive.
2. Create an exercise set
     A. Name the set (example: Frozen Shoulder)
     B. Enter date started, and date finished when done
     C. Add an exercise to the set:
          - name of exercise (example: Arm Circles)
          - upload a main photo and additional photos  (example: photo beginning and photo ending)
          - description (example: Lay on back and move arm in circles, keeping arm straight, trying to press arm as close to ground as possible. Go in one direction, then go in the other direction.)
          - Number of repetitions (example: 10)
          - Duration of each repetition (example: na)
          - Number of times per day to be done (example: 10)
          - Active / inactive toggle button in case your exercises change throughout the course of your physical therapy
     D. Additional instructions, such as applying ice or heat, taking medication, etc.
     E. Save button
3. Usage
     A. View an exercise set, as a reference
     B. Log your activity
          - Shows today's date
          - Takes the maximum number of times per day of all exercises in that set, and creates that number of empty checkboxes (example: 10 checkboxes)
          - Upon completion of first set in the day, click on the first checkbox. The checkbox will show as checked, and be grayed out. The time will be captured and displayed, and will appear next to the grayed out checkbox (example:  [x] 7:05am would be grayed out. Remaining 9 [ ] would be bold.)
          - Optional alert capability (haven't decided yet what form this will take)
     C. Show your performance over time
          - Shows monthly calendar since the start of that exercise set
          - Tallies the number of times completed per day and displays that number in the day's box. Also color codes the box depending on the percentage of completion (haven't decided methodology yet)
          - Displays an average number of times completed per day since the start of that exercise set.
     D. Changes
          - Can make any exercise inactive
          - Can add or delete exercises from any exercise set
          - Can make any exercise set inactive
          - Can add or delete exercise sets.

This app is intended specifically for mobile use.

## Technologies to be used:
AngularJS
JavaScript
NodeJS
Express.js
PostgreSQL
Angular UI Bootstrap
Angular Animate
Angular Material
Angular XEditable
Angular Routes
Karma
Jasmine
HTML5
CSS3
Picturefill
