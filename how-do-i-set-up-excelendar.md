# How do I set up Excelendar?

Once you have installed the add-in, open the Excelendar tab in the ribbon bar and click on the "Open Taskpane" button. Once the taskpane is opened, you will need to authenticate with your Microsoft account. The add-in will request the following permission scopes: Calendar.ReadWrite and Mailbox.ReadSettings.

The first permission is so that the add-in can import/export into Outlook Calendar, and the second is in order to retrieve the timezone setting for Outlook Calendar in order to ensure correct datetime information when importing and exporting. These permissions are required in order for the add-in to make the necessary requests to the Microsoft Graph API.

After you have granted the add-in with these permissions, you will be fully authenticated and have full access to all of the add-in's functionality.
