---
title: Create a journal approval procedure
TOCTitle: Create a journal approval procedure
ms:assetid: b3484fb1-a5d9-4245-9405-a5cdd4b31aa1
ms:mtpsurl: https://technet.microsoft.com/library/Aa571905(v=AX.60)
ms:contentKeyID: 36811425
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- journal approval
audience: Application User
ms.search.region: Global
---

# Create a journal approval procedure 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to set up approval procedures to define tasks that must be completed before a journal can be posted. A journal approval procedure can contain multiple stages. Each stage includes specific tasks and assigns a specific worker group to be responsible for the task.


> [!NOTE]
> <P>When a transaction is entered in a journal, it is automatically assigned to the first stage of the approval procedure.</P>



After you create an approval procedure and associate it with a journal, the lines that are entered in the journal cannot be posted without approval.

1.  Click **Project management and accounting** \> **Setup** \> **Journals** \> **Journal approval**.

2.  In the **Journal approval** form, click **New**.

3.  In the **Approve** field, type an identifier for the approval procedure, and in the **Name** field, type a name for the journal approval procedure. Then click **Lines**.

4.  In the **Journal approval setup** form, click **New** to add an approval stage for the journal approval procedure.

5.  In the **Status value** field, enter a name to identify the stage.

6.  Select the check box for each task that can be completed in the approval stage.

7.  In the **Group ID** field, select the worker group whose members can perform the actions in the stage.

8.  In the **Next** field, select the name of the next stage in the journal approval procedure.

9.  Repeat steps 4 to 8 for each stage of the approval procedure. Leave the **Next** field empty for the last stage of the approval procedure.

**Example**

You create an approval procedure named Project XYZ. The Project XYZ journal approval procedure has three stages, and a worker group is assigned to complete each stage:

1.  **Enter** – A project worker enters or modifies transactions in a journal (**Expense**, **Hours**, **Fee**, or **Item** consumption).

2.  **Check** – A project supervisor reviews the journal transactions and modifies them as required.

3.  **Post** – A project manager approves and posts the journal transactions.

The following table shows the settings that you entered in the **Journal approval** form to create the Project XYZ approval procedure.

<table style="width:100%;">
<colgroup>
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
<col style="width: 16%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Status value</strong></p></th>
<th><p><strong>Ready for posting</strong></p></th>
<th><p><strong>Check journal</strong></p></th>
<th><p><strong>Editing</strong></p></th>
<th><p><strong>Group ID</strong></p></th>
<th><p><strong>Next</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enter</strong></p></td>
<td><p>Cleared</p></td>
<td><p>Cleared</p></td>
<td><p>Selected</p></td>
<td><p>Project worker</p></td>
<td><p>Check</p></td>
</tr>
<tr class="even">
<td><p><strong>Check</strong></p></td>
<td><p>Cleared</p></td>
<td><p>Selected</p></td>
<td><p>Selected</p></td>
<td><p>Project supervisor</p></td>
<td><p>Post</p></td>
</tr>
<tr class="odd">
<td><p><strong>Post</strong></p></td>
<td><p>Selected</p></td>
<td><p>Selected</p></td>
<td><p>Selected</p></td>
<td><p>Project manager</p></td>
<td><p>N/A</p></td>
</tr>
</tbody>
</table>


## See also

[Apply a journal approval procedure](apply-a-journal-approval-procedure.md)

[About journal approval procedures](about-journal-approval-procedures.md)

[Journal approval (form)](https://technet.microsoft.com/library/aa499141\(v=ax.60\))

[Journal approval setup (form)](https://technet.microsoft.com/library/aa558425\(v=ax.60\))

  


