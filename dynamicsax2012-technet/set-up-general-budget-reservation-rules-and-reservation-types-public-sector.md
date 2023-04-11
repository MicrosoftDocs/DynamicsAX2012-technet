---
title: Set up general budget reservation rules and reservation types (Public sector)
TOCTitle: Set up general budget reservation rules and reservation types (Public sector)
ms:assetid: ae752fd2-0036-45bc-bbaf-51bda49cf021
ms:mtpsurl: https://technet.microsoft.com/library/Dn792460(v=AX.60)
ms:contentKeyID: 65205506
author: tonyafehr
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- public sector
- Forms.BudgetControlConfiguration
- Forms.AssetGroup
- Forms.BudgetParameters
- Forms.JournalizingDefinitionTrans
- Forms.LedgerParameters
- Forms.JournalizingDefinition
- Forms.NumberSequenceTableListPage
- budget reservation
- budget reservations
- general budget reservation
- general budget reservations
- reservation type
- reservation types
- budget reservation rules
- general budget reservation rules
- reservation type setup
audience: Application User
ms.search.region: Denmark, France
---

# Set up general budget reservation rules and reservation types (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

General budget reservations are often used by public sector entities to set aside or earmark budgeted funds so that they are not available for other purposes. To use general budget reservations, you must specify budgetary rules to enable your system to use them, and you must set up at least one general budget reservation type with the settings you want.


> [!NOTE]
> <P>If your organization is in France, you will use commitments instead of general budget reservations. For more information, see <A href="fra-about-commitments-public-sector.md">(FRA) About commitments (Public sector)</A>.</P>



The following illustration shows the steps that are required for setting up the system to use general budget reservations. The numbers correspond to the procedures later in this topic.

![Flow chart for general budget reservation setup](images/Dn792460.Setup_GBR(AX.60).jpg "Flow chart for general budget reservation setup")

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3, with Procurement and Sourcing and the following hotfix: KB3047235</p></td>
</tr>
<tr class="even">
<td><p>Related configuration tasks</p></td>
<td><ul>
<li><p>You are using posting definitions (not required if you do not activate commitment accounting).</p></li>
<li><p>Budget control configuration must be activated, budget control turned on, and an original budget confirmed.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## 1\. Set up budget parameters for regulatory accounting

To set up budget parameters for regulatory accounting, follow these steps.

1.  Click **Budgeting \> Setup \> Budget parameters**.

2.  Under **Regulatory**, in the **Regulatory document type for your region** list, select **General budget reservations**.

3.  Click **Close**.

## 2\. Select source documents for budget control

You can specify which method of purchasing to use with general budget reservations, in reserving funds for planned purchases.

To select source documents, follow these steps:

1.  Click **Budgeting \> Setup \> Budget control \> Budget control configuration**.

2.  Click the **Select source documents** tab.

3.  In the yellow message bar, click **Edit**.

4.  Select the **General budget reservation** check box, and then select the **Enable budget control for line item on entry** check box.

5.  Click the **Activate budget control** tab, and then click **Activate**.

6.  Click **Close**.

When you create a general budget reservation, budget source-tracking entries and accompanying budget-checking results are also created, and budget checking occurs when you create a line or post a reservation.

## 3\. Set up general ledger information for general budget reservations

To make sure that general ledger accounts are fairly stated, you must configure how general budget reservations are used to record accounting commitments. For more information, see [General ledger](general-ledger.md).

To set up general ledger information for general budget reservations, follow these steps:

1.  Click **General ledger \> Setup \> General ledger parameters**.

2.  On the **Ledger** tab, click the **Accounting rules** FastTab.

3.  Select the **Use posting definitions** check box, and then click **Yes** in the confirmation dialog box.

4.  Select the **General budget reservations** check box, and in the Infolog message, click **Close**.

5.  In the **General ledger parameters** form, click **Close**.

## 4\. Create posting definitions

You can configure transaction posting definitions to update different general ledger accounts for different types of general budget reservation. For more information, see [About posting definitions](about-posting-definitions.md).

To create posting definitions for general budget reservations, follow these steps:

1.  Click **General ledger \> Setup \> Posting \> Posting definitions**.

2.  In the **Posting definitions** form, on the Action strip, click **New**.

3.  In the **Posting definition** field, type a brief code for the definition (for example, GenBudgRes).

4.  In the **Module** list, select **Budget reservation**.

5.  Fill out the rest of the form as needed. For more information, see [Set up posting definitions](set-up-posting-definitions.md).

6.  Click **Close**.

7.  **Navigation Path Not Found**

8.  In the **Transaction posting definitions** form, click the **Budget reservation** tab.

9.  In the **Select** group, **General budget reservation** is selected by default. If appropriate, click **General budget reservation year-end close**.

10. On the Action strip, click **New**.

11. In the **Reservation type** field, do one of the following:
    
      - To enter a new transaction posting definition that applies to all reservation types, select **All**. In the **Posting definition** field, select the definition that you created earlier in this topic.
    
      - To enter a new transaction posting definition that applies to a single reservation type, select **Table**. In the **Reservation type relation** field, select the reservation type that you want. In the **Posting definition** field, select the definition that you created earlier in this topic.

12. Create as many definitions as you need, and then click **Close**.

## 5\. Set up the reservation number sequence

To set up the number sequence that general budget reservations will use, follow these steps:

1.  Click **Budgeting \> Setup \> Budget parameters**.

2.  Click **Number sequences**.
    

    > [!NOTE]
    > <P>If no reference or number sequence code already exists for general budget reservations in the form, follow the “Set up individual number sequences” procedure in <A href="set-up-number-sequences.md">Set up number sequences</A>. Then return to this procedure.</P>



3.  In the **Reference** column, click the entry for general budget reservations.

4.  In the **Number sequence** column, select the code to use.

5.  Optional: You can specify unique number sequences for various reservation types. For more information, see Step 6.

## 6\. Create a general budget reservation type

The reservation type determines the nature of a general budget reservation, such as the type of document that relieves the budget reservation, the workflow used to approve the reservation, and default values such as the start and end dates.

To create a general budget reservation type, follow these steps:

1.  Click **Budgeting \> Setup \> General budget reservations \> Reservation type**.

2.  On the Action strip, click **New**.

3.  In the **Reservation type** field, enter a name for the reservation type.

4.  In the **Description** field, enter a description.

5.  In the **Relieving document** field, **Purchase requisition** is selected by default. Change the setting if you need to. This setting specifies what type of document is associated with the general budget reservation.
    

    > [!NOTE]
    > <P>After you create a general budget reservation using the reservation type, you can’t change the reservation to another type.</P>



6.  In the **Reduce carry-forward budget** field, select the check box to have any remaining carry-forward budget associated with a general budget reservation reduced to zero when the reservation is finalized.

7.  Optional: If an approval or other task is required prior to posting the reservation, in the **Workflow** field, select a **General budget reservation** workflow. (If a workflow is not selected, general budget reservations of this type can be posted without workflow.)

8.  Optional: If various reservation types use unique number sequences, the **Number sequence** field is used to select the number sequence code that you want the selected type to use. If a reservation type does not have a document number configured, use the budget parameters document number.

9.  Create more types if you have to, by clicking **New**. When you are finished, click **Close**.

## Next step

After you have set up these rules, you can create general budget reservations. The general budget reservations will apply to the documents that are required for the purchasing method that you select (purchase order, purchase requisition, or vendor invoice). For more information, see [Create a general budget reservation (Public sector)](create-a-general-budget-reservation-public-sector.md).

## Related tasks

[About general budget reservations (Public sector)](about-general-budget-reservations-public-sector.md)

[Setup overview: basic budgeting and budget control](setup-overview-basic-budgeting-and-budget-control.md)

[Set up posting definitions](set-up-posting-definitions.md)

[Set up budget control](set-up-budget-control.md)

[Set up general budget reservation workflows (Public sector)](set-up-general-budget-reservation-workflows-public-sector.md)

[Set up Budgeting workflows](set-up-budgeting-workflows.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p><strong>Public Sector</strong></p>
<p><strong>Encumbrance process</strong></p>
<p><strong>Pre-encumbrance process</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must be a member of the <strong>Budget manager</strong> security role.</p></td>
</tr>
</tbody>
</table>

  


