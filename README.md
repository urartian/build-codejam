# CodeJam - With SAP Build, Create Apps, Processes, and Business Sites Without Coding

## Description

This repository contains the material for the CodeJam on using **SAP Build** to create a process, an app, and a business site. 

Specifically, you will get to know the environment by creating:

* A sales order approval process (**SAP Build Process Automation**).
* An app that lets users specify sales order data and trigger that process (**SAP Build Apps**).
* A business site in which you will embed that app (**SAP Build Work Zone**) (optional).

![SAP Build](/images/MyPresentation.png)

### What you will build

You will build an application that allows a user to enter sales order data, and then allows a manager to approve the sales order. To make all this simpler for the user, you will embed the app inside a business website along with other related apps and tools.

To accomplish this, you will create 3 inter-related parts using for each one of the SAP Build tools:

- First, you will create the process with SAP Build Process Automation for taking sales order details, which will send a request for approval to the manager.
- Second, you will create an app with SAP Build Apps that allows a user to enter sales order details and sends the data to the process and triggers the process.
- And third, you will create a workspace in SAP Build Work Zone and embed the app there. (optional)

![image](https://user-images.githubusercontent.com/11659786/231709754-a833a81f-d9ee-4911-9dfe-710fcdcc404c.png)

![image](/images/ex1.1/process.png)

![image](/images/ex1.3/Workzone.png)

### The exercises

Here's an overview of the exercises in this CodeJam.

* 👉 [Getting Started with the SAP Build Lobby](exercises/ex0-Getting-Started/README.md)
  * [Important Tips Before Starting](exercises/ex0-Getting-Started/ImportantTips.md)
* SAP Build Process Automation
  * [Configure SMTP Destination to send mail notifications](/exercises/ex1-SAP-Build-Process-Automation/ex1.0/README.md)
  * [Exercise 1.1 - Create Sales Order Business Process](exercises/ex1-SAP-Build-Process-Automation/ex1.1/README.md)
  * [Exercise 1.2 - Run the Sales Order Business Process](exercises/ex1-SAP-Build-Process-Automation/ex1.2/README.md) 
* SAP Build Apps
  * [Exercise 2.1 - Create SAP Build App to Trigger Workflow](exercises/ex2-SAP-Build-Apps/ex2.1/README.md)
  * [Exercise 2.2 - Populate Dropdown with SAP Data (ES5)](exercises/ex2-SAP-Build-Apps/ex2.2/README.md) (optional)
  * [Exercise 2.3 - Check Status of Process from SAP Build App](exercises/ex2-SAP-Build-Apps/ex2.3/README.md) (optional)
  * [Exercise 2.4 - Deploy SAP Build App to SAP BTP](exercises/ex2-SAP-Build-Apps/ex2.4/README.md)
* SAP Build Work Zone
  * [Exercise 3.1 - Add a Workspace to SAP Build Work Zone](/exercises/ex3-SAP-Build-Work-Zone/ex3.1/README.md)
  * [Exercise 3.2 - Add a Web Dynpro ABAP App to Your SAP Build Work Zone](/exercises/ex3-SAP-Build-Work-Zone/ex3.2/README.md)
  * [Exercise 3.3 - Integrate an SAP Build App Application into SAP Build Work Zone](/exercises/ex3-SAP-Build-Work-Zone/ex3.3/README.md)
  * [Exercise 3.4 - Create/Add UI5 Integration Card to Display Business Data](/exercises/ex3-SAP-Build-Work-Zone/ex3.4/README.md) (optional)

[Extra Credit topics](/exercises/extra-credit/README.md) (coming soon) 