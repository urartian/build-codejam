# Exercise 1.0 - Configure SMTP Destination to send mail notifications.

With SAP Build Process Automation, you can configure an Simple Mail Transfer Protocol (SMTP) server for email notifications to notify specific contacts about status changes in active project automations and live processes.

## Fake SMTP server

To simplify our lives, we will be using the services of Debug Mail to set up a fake SMTP server for email testing.

1. Go to [www.debugmail.io](https://debugmail.io) and create a free account.
![Sign up](../../../images/ex1.0/Sign%20up.png){width=400px height=550px}
2. Create a new project.
![New project](../../../images/ex1.0/Create%20new%20project.png)
![Project settings](../../../images/ex1.0/Project%20settings.png){width=350px height=700px}
3. Notifications from Build Process Automation
![Notifications](../../../images/ex1.0/Mail%20notifications.png)


## BTP Destinations

With the fake SMTP server in place, we can set up a destination in the BTP cockpit. This way, Process Automation can utilize it for sending notifications.

![Destinations](../../../images/ex1.0/Debug%20Mail%20destination.png)
