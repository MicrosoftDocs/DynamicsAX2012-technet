---
title: Run the SRSReportServerWarmup class
TOCTitle: Run the SRSReportServerWarmup class
ms:assetid: f0af28a2-b338-45f9-9b7a-acb85331bc42
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527683(v=AX.60)
ms:contentKeyID: 59626215
ms.date: 06/03/2014
mtps_version: v=AX.60
---

# Run the SRSReportServerWarmup class [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Microsoft SQL Server Reporting Services periodically restarts, and each restart clears the Reporting Services cache. After the cache has been cleared, it may take some time for the next report that is run to display. To minimize the effect of Reporting Services restarts, a new class that is named SRSReportServerWarmup is included with cumulative update 7 for Microsoft Dynamics AX 2012 R2. When the SRSReportServerWarmup class runs, it prepares the report server for use by performing the following tasks:

1.  Loads Microsoft Dynamics AX business logic assemblies

2.  Connects to Reporting Services

3.  Runs a sample report that is named SRSReportServerWarmup

As a best practice, you should run the SRSReportServerWarmup class after Reporting Services restarts. The following procedures explain how to use the SRSReportServerWarmup class.

## Deploy the SRSReportServerWarmup report

When the SRSReportServerWarmup class runs, it prepares the report server for use by running a sample report that is named SRSReportServerWarmup. You must deploy this report to the report server. For information about how to deploy a report, see [Deploy the default reports](deploy-the-default-reports.md).

## Create a batch group

A batch job is used to run the SRSReportServerWarmup class. (You’ll create this batch job in the next procedure.) We recommend that this batch job run within the context of a batch group. Complete the following procedure to create a batch group.

1.  Click **System administration** \> **Setup** \> **Batch group**.

2.  Click **New** to create a new batch group.

3.  In the **Group** field, enter a unique name for the batch group. For example, enter **SSRS**.

4.  In the **Description** field, enter a description to help you identify the batch group.

5.  Click the **Batch servers** tab.
    
    The **Selected servers** list displays the AOS instances that the batch group runs on. The **Remaining servers** list displays the remaining AOS instances that are available as batch servers.

6.  Use the arrow buttons to add servers to the **Selected servers** list or to remove servers from the **Selected servers** list.

## Create a batch job

Complete the following procedure to create a batch job that will run the SRSReportServerWarmup class.

1.  Open the Microsoft Dynamics AX Application Object Tree (AOT).

2.  Expand the **Classes** node.

3.  Right-click the **SRSReportServerWarmup** class, and then click **Open**. A form is displayed that lets you configure the batch job.

4.  Select the **Batch processing** check box.

5.  In the **Task description** field, enter a description for this batch job.

6.  In the **Batch group** list, select the batch group that you created in the previous procedure.

7.  Select the **Private** check box if you want to restrict other users from running this batch job. A private batch job can be run only by the user who created it and only on the computer where the user is logged on.

8.  Click **Recurrence** to specify how often this batch job will run.
    
    For example, if your report server restarts each night, you might want to schedule this batch job to run every morning. In this case, we recommend that you schedule the batch job to run before your employees start to work each day.

9.  Click **Alerts** to send notifications when this batch job ends, has an error, or is canceled.

## Extend the SRSReportServerWarmup class

When the SRSReportServerWarmup class runs, it prepares the report server for use by running a sample report that is named SRSReportServerWarmup. You can customize the SRSReportServerWarmup class so that it runs additional, specific reports.

For example, assume that Phyllis, the Accounts Payable manager in your organization, runs the Vendor Aging report every morning. To ensure that this report renders quickly for Phyllis, you can customize the SRSReportServerWarmup class so that it runs the Vendor Aging report every morning. To do this, you’ll need to create a new method that runs the Vendor Aging report and then configure the SRSReportServerWarmup class to call this new method.

Microsoft Dynamics AX provides sample code to help you create a new method. The following procedure explains how to use this sample code to create a method, and then configure the SRSReportServerWarmup class to call the new method.

1.  Open the AOT.

2.  Expand the **Classes** \> **SRSReportServerWarmup** node.

3.  Is the report that you’re going to run based on a report data provider (RDP) class?
    
      - **Yes** - If the report is based on an RDP class, right-click **runSampleRdpReportWithParameters**, and then click **View Code**. Copy the sample code that is displayed. You’ll use this code as a template for the new method that you create.
    
      - **No** - If the report is not based on an RDP class, right-click **runSampleRdlReportWithParameters**, and then click **View Code**. Copy the sample code that is displayed. You’ll use this code as a template for the new method that you create.
    
    For more information about RDP classes, see [How to: Use a Report Data Provider Class in a Report](how-to-use-a-report-data-provider-class-in-a-report.md).

4.  Create the new method. To do this, follow these steps:
    
    1.  Right-click the **SRSReportServerWarmup** class, and then click **New** \> **Method**.
    
    2.  Select the code that is displayed, right-click, and then click **Paste**. The sample code that you copied in step 3 is displayed.
    
    3.  Customize the code. For example, specify the report design to use. Additionally, if the report requires parameters, enter values for the parameters.
    
    4.  Save the new method.

5.  Configure the SRSReportServerWarmup class to call the new method. To do this, follow these steps:
    
    1.  Right-click the **run** method, and then click **View Code**.
    
    2.  Add code to call the new method that you created in step 4.
    
    3.  Save the **run** method.

6.  Right-click the **SRSReportServerWarmup** class, and then click **Compile**.
    
    The method should compile without errors or warnings.

7.  Click **Build** \> **Generate Incremental CIL**.
    
    When the process is completed, you receive a message that states that the incremental CIL was generated.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

