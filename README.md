# Microsoft Teams self-service app
Contains code for Teams self-service app. Requests are stored in a SharePoint list through PowerApps and processed through Powershell. PowerAutomate formats email messages and deletes SharePoint list items when a request is processed.

Benefits:
Eliminates duplicate display name limitation on the Teams client.
Ensures that the Team email address is unique without random numbers appended to it.
Informs the requestor if a name is already in use and provides names of the current owners.
Gives administrators more control over how teams are created. The script can be modified to include unique naming conventions.
