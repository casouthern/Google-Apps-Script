calculating your usage from the Google Cloud Console to show daily usage by Credential for the past 30 days.

To export traffic by credential:
Go to the APIs & Services Dashboard.
Select the Metrics tab.
Click dropdown under “Select Graphs” and choose Traffic by Credential.
Have only 1 of 14 APIs selected under “Filters”.
Export Traffic by Credential.csv
From downloads save Traffic by Credential.csv as google sheets. 
To create a new project:
In Google Drive go to New and select Google Sheets.
Add four sheets named Sheet1, Sheet2, Report1 and Report2.
In Google Sheet select Tools then Script editor.
Select Blank Project.
(optional) rename default Script file Code.gs
Paste the below code into your blank project, save your changes and refresh sheets.  Learn more on Google Apps Script development.
To run your script:
Paste values from Traffic by Credential into Sheet1.
In Script editor, select Run then Run Function and choose calculate30Days.
To run from sheets, select custom menu Calculate Usage then 30 Days.
