# Complaint-Management-Database

This repository is a project created on Microsoft Power Apps with Power Automation and Dataverse integration. 

More about the app:

User Side:

This is a complaint management database for government employees and employers. Users are prompted with a screen asking for basic contact information. Then complaints from the user will be stored in a dataverse database for further reviewing and identification from administrators. Then investigation teams can be dispatched to solve the issue. Users can also view their past complaints and statuses of those complaints. When a complaint is submitted, an instant flow is triggered which sends an eamil to the user confirming that investigation staff has recieved the complaint.

Admin Side:

For every submitted complaint there are 4 possible statuses

1. Submitted - Default tag given to every complaint
2. In Progress - Admin has reviewed the case and has dispacted investigators to solve the issue
3. Closed - Admin has decided to not take the case further and no investigators were dispatched
4. Complete - Investigation staff has completed review and investigation on the matter

Admin have options to move the case into any status. When admin moves the complaint to any status, an instant flow is triggered and sends an email to the user updating them on the update. All data metrics are stored in the dataverse database.

To access this app on power apps with all dependencies, export this repository, then in power apps, click on "Apps" on the left naviagation bar. Then click on import canvas app on the top navigation bar, and upload the folder.
