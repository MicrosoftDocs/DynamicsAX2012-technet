---
title: Start the Preprocessing upgrade checklist
TOCTitle: Start the Preprocessing upgrade checklist
ms:assetid: 7b508b00-8132-48a9-aae1-ba93f815ad07
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731839(v=AX.60)
ms:contentKeyID: 35132690
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Start the Preprocessing upgrade checklist 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Preprocessing upgrade checklist** guides you through the data preprocessing tasks on the Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 source system when you upgrade to Microsoft Dynamics AX 2012, Microsoft Dynamics AX 2012 Feature Pack, or Microsoft Dynamics AX 2012 R2.

When you import the upgrade XPO files into the source system, the **Preprocessing upgrade checklist** is installed in the USR layer along with other upgrade framework components:

  - Forms and classes that are required for preprocessing data.

  - Changes to the **Data upgrade cockpit** form.

  - Data preprocessing scripts.

For information about importing the upgrade framework XPO files, see [Install upgrade framework files](install-upgrade-framework-files.md).

## Open the Preprocessing upgrade checklist

After all of the needed XPO files have been imported, open the **Preprocessing upgrade checklist** as follows:

1.  Click the Project icon on the toolbar and navigate to **Projects\> Shared**.

2.  Expand **Shared** and locate either **Ax40PreUpgradeFramework** or **Ax50PreUpgradeFramework**, depending on the version that you are upgrading from. Right-click it, and click **Open**.

3.  Locate **SysChecklist\_preupgrade40** or **SysCheckList\_PreUpgrade50**, depending on the version you are upgrading from. Right-click it, and click **Open** to start the **Preprocessing upgrade checklist**.

## Sections and tasks in the Preprocessing upgrade checklist

The **Preprocessing upgrade checklist** displays the required and optional tasks that are involved in data upgrade preprocessing. The system records the completion of tasks and indicates this status with a check mark. The list of tasks is divided into four sections. When you open the **Preprocessing upgrade checklist**, these sections are collapsed. Expand each section to access the tasks. You can also collapse an expanded section when you have completed the tasks within it.

The following table contains the sections and types of task you will complete during data upgrade preprocessing on the Microsoft Dynamics AX source system.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Section</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Prepare for upgrade</strong></p></td>
<td><p>The tasks in this section test and prepare the source system for upgrade. The tasks include creating the shadow and dictionary tables where the upgrade framework will write the data that you prepare for upgrade in the next section.</p></td>
</tr>
<tr class="even">
<td><p><strong>Prepare application data for preprocessing</strong></p></td>
<td><p>The tasks in this section prepare the Microsoft Dynamics AX source system data for preprocessing while the source system remains in production. Completing these tasks does not affect your production system data.</p>
<p>When you click a task, a form opens and prompts you for information. Because these tasks require knowledge of the application data that you are preparing for upgrade, you will need guidance from a business user in each of the application areas.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Preprocess data on live system</strong></p></td>
<td><p>These tasks run data preprocessing scripts while the source system is still live for production. The prepared data is written into shadow tables in preparation for bulk copy to the Microsoft Dynamics AX 2012 target system.</p></td>
</tr>
<tr class="even">
<td><p><strong>Preprocess data in single-user mode</strong></p></td>
<td><p>These tasks apply final preparation to the source data prior to bulk copy. When you begin the tasks in this section, you start your system downtime window. Your system will not be available for production until you complete the data upgrade tasks on the Microsoft Dynamics AX 2012 target system.</p></td>
</tr>
</tbody>
</table>


Each task in the **Preprocessing upgrade checklist** links to a Help topic that explains the task and provides steps for completing it.


> [!TIP]
> <P>To improve performance during the database-intensive upgrade preprocessing tasks, we recommend that you apply the following parameter to the Microsoft Dynamics AX database before you begin:</P>
> <P>Update RELEASEUPDATECONFIGURATION set NoCompanyDependency = 1</P>
> <P>This setting prevents the execution of scripts from being delayed due to company interdependencies.</P>


  


