---
title: Using the preprocessing upgrade state transfer tool
TOCTitle: Using the preprocessing upgrade state transfer tool
ms:assetid: 414e3d48-f088-4e59-815e-0f8ad50da298
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731784(v=AX.60)
ms:contentKeyID: 35132615
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Using the preprocessing upgrade state transfer tool [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The preprocessing upgrade state transfer tool helps you minimize downtime during upgrade. The tool also helps you avoid putting an additional load on your production Microsoft Dynamics AX system while you prepare to upgrade it. This topic describes how to create a test system that is a replica of your production system, perform data preprocessing on the test system, and then transfer the completed preprocessing state back to the production system.

## How the state transfer tool works

The state transfer tool operates on a Microsoft Dynamics AX source system where some of the tasks of the **Preprocessing upgrade checklist** have been completed. The tool analyzes the code in the upgrade preprocessing project to identify the upgrade staging and framework tables that are required to capture the state of the **Preprocessing upgrade checklist**. The tool then uses the Microsoft SQL Server Bulk Copy Program (BCP) utility to copy these tables to a second Microsoft Dynamics AX source system. During bulk copy, you can add processor threads to improve data throughput.

## Plan before you use the state transfer tool

The state transfer tool is intended to help minimize the amount of upgrade preprocessing that must be performed on a production system. Use the state transfer tool if you want to offload the live upgrade preprocessing task to a test server. However, note that use of this tool requires careful consideration and planning. We recommend that you test the tool on a non-production system before you use it for upgrade in your production environment. Also, after you perform a state transfer, you must reconcile the updated data in your test system with the data in your production system.


> [!WARNING]
> <P>Do not modify the data on your production Microsoft Dynamics AX system by loading the results of the state transfer tool until you have repeatedly and successfully tested this procedure on a non-production test system.</P>



## Prepare to perform a state transfer

Before you perform a state transfer, you must complete the following tasks on the test and production source systems.

## Prepare the production system

1.  On the production system, import the preprocessing XPO that is appropriate for the Microsoft Dynamics AX version that you are upgrading. For more information, see the [Microsoft Dynamics AX 2012 Upgrade Guide](http://go.microsoft.com/fwlink/?linkid=212541).

2.  On the production system, install the upgrade-related label file (.ald) files. Also install the upgrade-related Help files (.chm) files. For more information, see the [Microsoft Dynamics AX 2012 Upgrade Guide](http://go.microsoft.com/fwlink/?linkid=212541).

3.  On the **Preprocessing upgrade checklist**, complete the **Check upgrade readiness** task and resolve any validation errors. Enable triggers to track necessary data, based on prompts from the upgrade readiness checks. For more information about this step, see [Check upgrade readiness](check-upgrade-readiness.md).

4.  The test system must be an exact replica of the production system. Copy the USR layer (.aod) file on the production system, and back up the production system database:
    
    1.  Copy the USR layer (.aod) file. Typically, this file is located at C:\\Program Files (x86)\\Microsoft Dynamics AX\\40\\Application\\\<application instance\>\\axusr.aod or C:\\Program Files\\Microsoft Dynamics AX\\50\\Application\\\<application instance\>\\axusr.aod. Have this file available for installation on the test system.
    
    2.  Use Microsoft SQL Server Management Studio to back up the Microsoft Dynamics AX database. Have this backup file available for installation on the test system.


> [!IMPORTANT]
> <P>After you copy the USR layer and make backup of the database, you must avoid making changes to the application on your production system. Data transactions may continue (allowing continued business operations), but metadata changes, customizations, changes to the AOT, and anything that changes the behavior of the application can cause the state transfer to fail.</P>



## Prepare the test system

The following steps produce a test source system that is configured identically to the production source system.


> [!WARNING]
> <P>Do not import the upgrade XPO into the test source system. The necessary upgrade framework code is provided in the AOD file that you copied from the production source system. Importing the XPO overwrites element IDs and causes runtime errors.</P>



1.  Install the upgrade-related label files (.ald) files. Also install the upgrade-related Help (.chm) files. For more information, see the [Microsoft Dynamics AX 2012 Upgrade Guide](http://go.microsoft.com/fwlink/?linkid=212541).

2.  Install the USR layer (.aod) file that you copied from the production system. Typically, this file is installed at C:\\Program Files (x86)\\Microsoft Dynamics AX\\40\\Application\\Appl\\Standard\\axusr.aod or C:\\Program Files\\Microsoft Dynamics AX\\50\\Application\\Appl\\DynamicsAX5\\axusr.aod.

3.  Use SQL Server Management Studio to restore the database backup from the production system as the Microsoft Dynamics AX database on the test system.


> [!IMPORTANT]
> <P>After you complete these steps, you must restart Application Object Server (AOS).</P>



The test source system is now ready for upgrade preprocessing. We recommend that you complete the following tasks on the **Preprocessing upgrade checklist**:

1.  All tasks in the **Prepare application data for preprocessing** section

2.  **Run live preprocessing scripts**

3.  **Run delta preprocessing scripts**

## Enable the database connection

Windows integrated security is used to connect to the production source system from the test source system. The administrative user who is performing the state transfer must have access to the Microsoft Dynamics AX database on the production source system. Otherwise, the production source system rejects the database connection. Open SQL Server Management Studio on the production source system, and follow these steps:

1.  Grant access to the Microsoft Dynamics AX database to a domain user who has administrative privileges on the test source system.

2.  Add this user to the **db\_owner** and **public** database roles.

## Open the Preprocessing upgrade state transfer form

After you have completed upgrade preprocessing on the test system, open the **Preprocessing upgrade state transfer** form on the production system. The form is opened from a private project that is installed by the preprocessing framework XPO.

1.  Click the **Project** icon on the Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 toolbar.

2.  Expand **Private**.

3.  Double-click **xferUpgState (usr)**.

4.  Scroll down to **xferUpgState (usr)**, right-click, and then click **Open**.

## Perform the state transfer

1.  In the **Server name** field, enter the name of the test system.

2.  In the **Database name** field, enter the name of the Microsoft Dynamics AX database for the test system.

3.  Click **Run** to start the upgrade state transfer. The state transfer tool validates conditions in both the test system and the production system. If no errors are found, the tool schedules batch jobs to bulk copy all shadow, dictionary, auxiliary, and framework tables from the test source system to the production source system.

A form opens so that you can monitor and manage the bulk copy process. The form is called **Batch list** in Microsoft Dynamics AX 4.0 and **Batch tasks** in Microsoft Dynamics AX 2009. You can use the form to pause or rerun jobs if you have to.


> [!IMPORTANT]
> <P>To use the state transfer tool, you must enable administrative user access between the test and production systems by using Windows integrated security.</P>



## Perform post-transfer tasks

After the state transfer is complete, perform the following tasks.

1.  Open the **Preprocessing upgrade checklist** and rerun the tasks in the section **Prepare application data for preprocessing**. This will allow you to make manual adjustments to new data from the delta between production system backup and completion of the state transfer.

2.  The only tables that this tool copies over are those that are imported as part of the preprocessing XPO - hence, no production data is copied over from the test system back into production. As a result, you must manually synchronize the data in two number sequence tables on the production system, as shown:
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Table name</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>CRM_1</p></td>
    <td><p>Party numbers</p></td>
    </tr>
    <tr class="even">
    <td><p>CRM_2</p></td>
    <td><p>Location numbers</p></td>
    </tr>
    </tbody>
    </table>
    
    To do this, check the next value and maximum value for each of these number sequences in the test environment and transfer those values manually to the corresponding tables in the production environment. Subsequent scripts in the upgrade process that use these number sequences will pick up the correct values when they are executed.

3.  Finally, run the delta preprocessing scripts, and then continue with upgrade preprocessing in single-user mode.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

