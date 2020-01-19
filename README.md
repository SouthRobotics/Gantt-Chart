# Gantt-Chart
This is the code embedded into the Google Site for the Gantt charts that read off of the Google Sheet

# How it works
  
   The spreadsheet linked in all of the files is read by the Gantt Chart on the google site:
   https://sites.google.com/view/southrobotics
   
   Each page filters out different information to make charts with less info
   
   1weekgraph.html -> Graphs all teams for one week starting at the current date
   Full_team_schedule.html -> Graphs all of the teams for all times (aka everything in the spreadsheet)
   One_week_Team.html -> Graphs one specific team for one week starting at the current date
   Full_one_team.html -> Graphs one specific team for all times (aka everything in the spreadhseet for one team)
   
   
# How to make changes
  If the occasion ever arrises where the link to the spreadsheet changes or the team names change (or you add or remove a team or something), the code is very easy to fix
  
  At the top of all the files there are variables for the spreadsheet called spreadSheetLink
  At the top of the files where it applies, there is a variable for the name of the team to get all events for
  
  Once you change it in the file, you must then go to the google site and edit it. In there you must click on the pencil icon that appears when you click on the graph. Then edit and replace the old code with the new code. You must do this for all of the graphs, so I suggest trying not to change anything if you don't need to.
  
# How to format the spreadsheet 
  Team names should be consistent with these: (they are case sensitive)
 
    Mechanical  
    Electrical
    Programming  
    PR
    
  You can have more team names then that, but they will only show up in the all teams graph
  
  
  Task ID's matter for dependencies
  
    -Make sure that all of the dependencies are exactly the task ID's
    -To have multiple dependencies, list them separated by commas
    -It is recommended that you follow a certain naming pattern:
      Mechanical: M001 
      Electrical: E001
      Programming: P001
      Public Relations: PR001
      etc
      
# Debugging
  If you get this error: 
