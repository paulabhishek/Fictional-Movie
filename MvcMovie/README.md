/*
            Author: AbhishekPaul_0777040
			Modified date: 14/Oct/2021
 */

 9 AM
 Created a controller with index and welcome action.
 tested controller - passed.

9 40 AM
started with the View. created an empty view for index and welcome action.
successfully ran the code with 0 errors. was able ti manupliate teh URL.

11 AM
started adding Model. 11:40 finished with scaffolding and started Initial migration
ran into More than one DbContext was found error while Initial migration.
corrected the powershell command to 
Add-Migration InitialCreate 
Update-Database
Success!!

added a local db and tested.


2:14 PM
Examined the database that was perviewsly created.
examined the design and the date in the table.
Seeded the table.

4 PM
made changes to the view folder.
Added styles to elements.
tried applying inline style to every element - nogo
Used the wwwroot folder and wrote all my styles in a css file and saved it under CSS folder.

4:50 PM
Use bootstrap crasole slider for the index page.
changed the title and addes more CSS to page background font etc..

7 PM
started configuring Azure service to deploy the app.
AzureDB configuration failed.
realised VS was locally running the app and it was the issue.
successfully publised to Azure but the DB page don't seem to work.

10 PM
Unsuccessfully deploying to Azure..
deployment worked later with no access to the db.
