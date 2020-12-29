# Student Information System

## Introduction
During the pandemic, entire Education system was forcefully shifted to online mode. Most of the things worked fine, few needed little change and few were challenging. One of the challenge I faced during this time was to share personalised information with the parents. I didn't want to share entire class's score with everyone, rather the task was to give a individualised information to parents regarding the 
1. Quiz Score
2. Daily Attendance
3. Daily Task status

## Suggested Solution
One of the suggested solution, was to store everything in a database and then creating a client interface for the parents with personalised logins. Little too much, in terms of programming, resources and time-investment.

I came with an alternative using Excel sheet. I used excel as a database as well as the client interface.

## Detailed Solution
1. Create a database for Quiz score, attendance, task completion etc.
2. Create individual excel sheets, one for each student
3. Link the individual excel sheet to the data base.
4. Upload the database and all the files to the cloud folder (OneDrive, Google Drive etc.)
5. Share the individual file link with the parents.

## Updating
After this every time when parent will access that link, s/he will be able to see the current progress level of his/her child.

Unfortunately, file will be updated only if it is open in the desktop app. To ensure that the file is opened in the desktop app when we click the link, we may follow the steps given at the following [help document.](https://support.microsoft.com/en-us/office/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773)

## Advance
This is a bare minimum version of the application. For more advance version, we may store entire dataset in a SQL Database and create individual reports using Python bindings. Later link to those Python generated files may be shared with the parents. We may even create a login entry for parents on the WordPress website or the school website and directly share the SQL data
