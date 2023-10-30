# Configure SMTP Destination to send mail notifications.

With SAP Build Process Automation, you can configure an Simple Mail Transfer Protocol (SMTP) server for email notifications to notify specific contacts about status changes in active project automations and live processes. To simplify our lives, we will be using the services of Debug Mail to set up a fake SMTP server for email testing.

## Fake SMTP server


1. Go to [www.debugmail.io](https://debugmail.io) and create a free account.
![Sign up](../../../images/ex1.0/Sign%20up.png)
2. Create a new project.
![New project](../../../images/ex1.0/Create%20new%20project.png)
![Project settings](../../../images/ex1.0/Project%20settings.png)
3. Notifications from Build Process Automation
![Notifications](../../../images/ex1.0/Mail%20notifications.png)


## BTP Destinations

With the fake SMTP server in place, we can set up a destination in the BTP cockpit. This way, Process Automation can utilize it for sending notifications.
You have the option to either create a new destination or import an already existing one from. [here](../../ex1-SAP-Build-Process-Automation/destinations/sap_process_automation_mail)

![Destinations](../../../images/ex1.0/Debug%20Mail%20destination.png)
