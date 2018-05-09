---
title: 'Examples: Budgeting and budget control'
TOCTitle: 'Examples: Budgeting and budget control'
ms:assetid: 418595c9-6c9a-433a-89c0-cd963b6007a2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242261(v=AX.60)
ms:contentKeyID: 36056729
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- budget control examples
- examples of budget control
---

# Examples: Budgeting and budget control 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Examples 1 through 3 for budgeting and budget control show the balances and results for budget register entries that have the following budget types: **Original budget**, **Transfer**, or **Revision**. Examples 4 and 5 describe manual budget reservations and how to set up a budget group.


> [!NOTE]
> <P>This topic includes information about financial budgets. For information about budgets for projects, see <A href="about-project-budgets-and-forecasts.md">About project budgets and forecasts</A>.</P>



## Example 1: Create an initial budget amount for financial dimensions

You are setting up the budget for the next fiscal year. Department and Cost center are the financial dimensions that are defined for Budgeting. You enter a budget register entry that uses budget model A and a budget code that has a budget type of **Original budget**. When you submit the budget register entry, the budget model is updated with the amounts for the Department and Cost center dimension values, based on the date that was entered for each budget account entry.

Budget register entry number: **BUD\_0001**

Budget model: **A**

Budget type: **Original budget**

The budget account entries in the budget register entry contain the following dates, financial dimension values and names, and amounts. In the **Budget register entry** form, the dimension values are displayed in a column. The dimension names are displayed when you move the pointer over the field for the financial dimension values.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>To dimension values</p></th>
<th><p>Dimension names</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>Dept1-CC1</p></td>
<td><p>Sales department – West region</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="even">
<td><p>February 1</p></td>
<td><p>Dept1-CC1</p></td>
<td><p>Sales department – West region</p></td>
<td><p>1,500.00</p></td>
</tr>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>Dept1-CC2</p></td>
<td><p>Sales department – East region</p></td>
<td><p>10,000.00</p></td>
</tr>
<tr class="even">
<td><p>March 1</p></td>
<td><p>Dept1-CC2</p></td>
<td><p>Sales department – East region</p></td>
<td><p>15,000.00</p></td>
</tr>
</tbody>
</table>


## Budget balances for Sales department – West region

This example assumes that no other original budget register entries have been submitted to the budget model or the financial dimensions. After the original budget register entry was submitted, the budget balances for the Sales department – West region (Dept1-CC1) are as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Period</p></th>
<th><p>Period balance</p></th>
<th><p>Accumulated balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>1,000.00</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="even">
<td><p>February 1</p></td>
<td><p>1,500.00</p></td>
<td><p>2,500.00</p></td>
</tr>
<tr class="odd">
<td><p>March 1</p></td>
<td><p>0.00</p></td>
<td><p>2,500.00</p></td>
</tr>
<tr class="even">
<td><p>April 1</p></td>
<td><p>0.00</p></td>
<td><p>2,500.00</p></td>
</tr>
<tr class="odd">
<td><p>Continues to December 1</p></td>
<td><p>0.00</p></td>
<td><p>2,500.00</p></td>
</tr>
</tbody>
</table>


## Budget account entries for Sales department – West region

In the original budget register entry, the budget account entries for the Sales department – West region (Dept1-CC1) are as follows.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Budget account entry date</p></th>
<th><p>Budget register entry number</p></th>
<th><p>Budget type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="even">
<td><p>February 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>1,500.00</p></td>
</tr>
</tbody>
</table>


## Budget balances for Sales department – East region

This example assumes that no other original budget register entries have been submitted to the budget model or financial dimensions. After the original budget register entry was submitted, the budget balances for the Sales department – East region (Dept1-CC2) are as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Period</p></th>
<th><p>Period balance</p></th>
<th><p>Accumulated balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>10,000.00</p></td>
<td><p>10,000.00</p></td>
</tr>
<tr class="even">
<td><p>February 1</p></td>
<td><p>0.00</p></td>
<td><p>10,000.00</p></td>
</tr>
<tr class="odd">
<td><p>March 1</p></td>
<td><p>15,000.00</p></td>
<td><p>25,000.00</p></td>
</tr>
<tr class="even">
<td><p>April 1</p></td>
<td><p>0.00</p></td>
<td><p>25,000.00</p></td>
</tr>
<tr class="odd">
<td><p>Continues to December 1</p></td>
<td><p>0.00</p></td>
<td><p>25,000.00</p></td>
</tr>
</tbody>
</table>


## Budget account entries for Sales department – East region

In the original budget register entry, the budget account entries for the Sales department – East region (Dept1-CC2) are as follows.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Budget account entry date</p></th>
<th><p>Budget register entry number</p></th>
<th><p>Budget type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>10,000.00</p></td>
</tr>
<tr class="even">
<td><p>March 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>15,000.00</p></td>
</tr>
</tbody>
</table>


## Example 2: Create a budget transfer

Some of the budget amount from the Sales department – East region (Dept1-CC2) has to be moved to the Sales department – West region (Dept1-CC1) for an upcoming event. You use a budget register entry that has a budget type of **Transfer** to reduce the Sales department – East region (Dept1-CC2) budget and increase the Sales department – West region (Dept1-CC1) budget. You enter a budget register entry that uses budget model A and a budget code that has a budget type of **Transfer**. You enter dimension values Dept1-CC1 in the first budget account entry for 1,000.00, and dimension values Dept1-CC2 in the second budget account entry for -1,000.00. You submit the budget transfer.

Budget register entry number: **BUD\_0002**

Budget model: **A**

Budget type: **Transfer**

The budget account entries in the budget register entry for the transfer contain the following dates, financial dimension values and names, and amounts. In the **Budget register entry** form, the dimension values are displayed in a column. The dimension names are displayed when you move the pointer over the field for the financial dimension values.

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
<th><p>Date</p></th>
<th><p>To dimension values</p></th>
<th><p>Dimension names</p></th>
<th><p>Amount</p></th>
<th><p>From dimension values</p></th>
<th><p>Dimension names</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>Dept1-CC1</p></td>
<td><p>Sales department – West region</p></td>
<td><p>1,000.00</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>January 1</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>-1,000.00</p></td>
<td><p>Dept1-CC2</p></td>
<td><p>Sales department – East region</p></td>
</tr>
</tbody>
</table>


## Budget balances for Sales department – West region

After both the original budget and the budget transfer are submitted, the budget balances for the Sales department – West region (Dept1-CC1) are as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Period</p></th>
<th><p>Period balance</p></th>
<th><p>Accumulated balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>2,000.00</p></td>
<td><p>2,000.00</p></td>
</tr>
<tr class="even">
<td><p>February 1</p></td>
<td><p>1,500.00</p></td>
<td><p>3,500.00</p></td>
</tr>
<tr class="odd">
<td><p>March 1</p></td>
<td><p>0.00</p></td>
<td><p>3,500.00</p></td>
</tr>
<tr class="even">
<td><p>April 1</p></td>
<td><p>0.00</p></td>
<td><p>3,500.00</p></td>
</tr>
<tr class="odd">
<td><p>Continues to December 1</p></td>
<td><p>0.00</p></td>
<td><p>3,500.00</p></td>
</tr>
</tbody>
</table>


## Budget account entries for Sales department – West region

After both the original budget and the budget transfer are submitted, the budget account entries for the Sales department – West region (Dept1-CC1) are as follows.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Budget account entry date</p></th>
<th><p>Budget register entry number</p></th>
<th><p>Budget type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="even">
<td><p>February 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>1,500.00</p></td>
</tr>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>BUD_0002</p></td>
<td><p>Transfer</p></td>
<td><p>1,000.00</p></td>
</tr>
</tbody>
</table>


## Budget balances for Sales department – East region

After both the original budget and the budget transfer are submitted, the budget balances for the Sales department – East region (Dept1-CC2) are as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Period</p></th>
<th><p>Period balance</p></th>
<th><p>Accumulated balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>9,000.00</p></td>
<td><p>9,000.00</p></td>
</tr>
<tr class="even">
<td><p>February 1</p></td>
<td><p>0.00</p></td>
<td><p>9,000.00</p></td>
</tr>
<tr class="odd">
<td><p>March 1</p></td>
<td><p>15,000.00</p></td>
<td><p>24,000.00</p></td>
</tr>
<tr class="even">
<td><p>April 1</p></td>
<td><p>0.00</p></td>
<td><p>24,000.00</p></td>
</tr>
<tr class="odd">
<td><p>Continues to December 1</p></td>
<td><p>0.00</p></td>
<td><p>24,000.00</p></td>
</tr>
</tbody>
</table>


## Budget account entries for Sales department – East region

After both the original budget and the budget transfer are submitted, the budget account entries for the Sales department – East region (Dept1-CC2) are as follows.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Budget account entry date</p></th>
<th><p>Budget register entry number</p></th>
<th><p>Budget type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>10,000.00</p></td>
</tr>
<tr class="even">
<td><p>March 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>15,000.00</p></td>
</tr>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>BUD_0002</p></td>
<td><p>Transfer</p></td>
<td><p>-1,000.00</p></td>
</tr>
</tbody>
</table>


## Example 3: Create a budget revision

Revenue is exceeding original forecasts. Therefore, the Travel expense budget can be increased to provide more travel opportunities. To increase the budget, you enter a budget register entry that uses budget model A and a budget code that has a budget type of **Revision**. You submit the budget revision.

Budget register entry number: **BUD\_0003**

Budget model: **A**

Budget type: **Revision**

The budget account entry in the budget register entry contains the following dates, financial dimension values and names, and amounts. In the **Budget register entry** form, the dimension values are displayed in a column. The dimension names are displayed when you move the pointer over the field for the financial dimension values.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Date</p></th>
<th><p>To dimension values</p></th>
<th><p>Dimension names</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>March 1</p></td>
<td><p>Dept1-CC1</p></td>
<td><p>Sales department – West region</p></td>
<td><p>5,000.00</p></td>
</tr>
</tbody>
</table>


## Budget balances for Sales department – West region

After the original budget, budget transfer, and budget revision entries are submitted, the budget balances for the Sales department – West region (Dept1-CC1) are as follows.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Period</p></th>
<th><p>Period balance</p></th>
<th><p>Accumulated balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>2,000.00</p></td>
<td><p>2,000.00</p></td>
</tr>
<tr class="even">
<td><p>February 1</p></td>
<td><p>1,500.00</p></td>
<td><p>3,500.00</p></td>
</tr>
<tr class="odd">
<td><p>March 1</p></td>
<td><p>5,000.00</p></td>
<td><p>8,500.00</p></td>
</tr>
<tr class="even">
<td><p>April 1</p></td>
<td><p>0.00</p></td>
<td><p>8,500.00</p></td>
</tr>
<tr class="odd">
<td><p>Continues to December 1</p></td>
<td><p>0.00</p></td>
<td><p>8,500.00</p></td>
</tr>
</tbody>
</table>


## Budget account entries for Sales department – West region

After the original budget, budget transfer, and budget revision entries are submitted, the budget account entries for the Sales department – West region (Dept1-CC1) are as follows.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Budget account entry date</p></th>
<th><p>Budget register entry number</p></th>
<th><p>Budget type</p></th>
<th><p>Amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Revision</p></td>
<td><p>1,000.00</p></td>
</tr>
<tr class="even">
<td><p>March 1</p></td>
<td><p>BUD_0001</p></td>
<td><p>Original budget</p></td>
<td><p>1,500.00</p></td>
</tr>
<tr class="odd">
<td><p>January 1</p></td>
<td><p>BUD_0002</p></td>
<td><p>Transfer</p></td>
<td><p>-1,000.00</p></td>
</tr>
<tr class="even">
<td><p>March 1</p></td>
<td><p>BUD_0003</p></td>
<td><p>Revision</p></td>
<td><p>5,000.00</p></td>
</tr>
</tbody>
</table>


## Example 4: Create a manual budget reservation

Generally, budget reservations are not created manually. They are created when source documents such as purchase requisitions and purchase orders are entered. However, if an adjustment must be made to the reservation balance, or if you want to reserve budget funds without a purchase requisition or purchase order, you can create a manual reservation of budget funds by using a budget register entry that has a budget type of **Pre-encumbrance** or **Encumbrance**.

You are a member of a user group that can exceed the budget funds available. In the **Budget funds available** area of the **Budget control configuration** form, the budget funds available calculation is set up as follows: (**Original budget** + **Budget revisions** + **Budget transfers**) - (**Actual expenditures** + **Budget reservations for encumbrances** + **Budget reservations for pre-encumbrances**).

## Entry does not exceed the available budget balance

The following information describes what occurs when an entry passes a budget check on the budget funds available.

You must reserve funds for a training event for the Sales department – West region (Dept1-CC1). You enter a budget register entry that uses budget model A and a budget code that has a budget type of **Encumbrance**. On a budget account entry, you enter dimension values Dept1\_CC1 and an amount of 500.00. When the budget account entry is saved, a green check mark indicates that budget funds are available for the entry. You can complete the processing of the entry by clicking **Update budget balances** on the **Action Pane** in the **Budget register entry** form.

## Entry exceeds the available budget balance

The following information describes what occurs when an entry does not pass a budget check on the budget funds available.

You must reserve funds for a future purchase of office supplies for the Sales department – West region (Dept1-CC1). You enter a budget register entry that uses budget model A and a budget code that has a budget type of **Encumbrance**. On a budget account entry, you enter dimension values Dept1-CC1 and an amount of 10,000.00. When the budget account entry is saved, you receive a message that the 10,000 entry amount that you saved exceeds the available budget balance for dimension Dept1-CC1. You are in a user group that can exceed the budget funds available. Therefore, you can update the budget balances.

## Example 5: Set up a budget group

A budget group provides a group of dimensions or dimension values that share budgeted amounts. For more information, see “Define budget groups” in [Set up budget control](set-up-budget-control.md).

The following account structure is being used at a public sector agency: **Fund – Department – Cost center – Object**.

The following dimensions exist:

  - Fund:
    
      - 010
    
      - 100

  - Department:
    
      - Police

  - Cost center:
    
      - Patrol
    
      - Admin

  - Main account:
    
      - Vehicles
    
      - Bikes
    
      - Computers

Main account is defined as a dimension for budget control.

Your goal is to define the budget for all equipment for the Police department, Patrol cost center, and Fund 100, but also to allow for a secondary budget check at the department level only.

To specify that a budget check should be performed for a specific dimension, you define budget control rules that contain criteria that represent the dimension values that should be checked. For example:

  - Where **Department** is between and includes **Admin** and **Patrol**

  - Where **Cost center** is like **\***

  - Where **Fund** is **100**

For more information, see “Define budget control rules” in [Set up budget control](set-up-budget-control.md).

These criteria indicate that whenever the departments between Admin and Patrol are entered in combination with any cost center for fund 100, a budget check will occur.

To perform a budget check at a budget group level, you must define the criteria that represent the budget group in the budget control configuration. For example, to perform a budget check for the Police department, you would specify the following criteria:

  - Where **Department** is **Police**

For more information, see “Define budget groups” in [Set up budget control](set-up-budget-control.md).

The following table describes how these budget control rules and budget group checks would be applied, assuming that the following budget balances exist.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Dimension values</p></th>
<th><p>Balance</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>100-Police-Patrol</p></td>
<td><p>10,000.00</p></td>
</tr>
<tr class="even">
<td><p>100-Police-Admin</p></td>
<td><p>5,000.00</p></td>
</tr>
</tbody>
</table>


If a budget check was made on dimension values 100-Police-Patrol for an amount of 11,000.00, the entry would exceed the available budget funds for 100-Police-Patrol by 1,000.00. However, the entry would pass on a secondary budget check at the budget group level where the department is Police, because the budget amounts for the Police department would include the Patrol cost center and the Admin cost center.


> [!NOTE]
> <P>The user group budget permissions that are associated with budget control rules and budget groups can determine the over-budget options for users. For more information, see, <A href="set-up-budget-control.md">Set up budget control</A>.</P>



## See also

[Create budget register entries](create-budget-register-entries.md)

[View the status and history of budget registry entries](view-the-status-and-history-of-budget-registry-entries.md)

[Set up budget control](set-up-budget-control.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

