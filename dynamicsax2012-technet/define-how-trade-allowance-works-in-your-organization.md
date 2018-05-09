---
title: Define how trade allowance works in your organization
TOCTitle: Define how trade allowance works in your organization
ms:assetid: ebce4810-14d9-4d8e-bd16-66a84807aa0c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn727066(v=AX.60)
ms:contentKeyID: 62381663
ms.date: 05/27/2014
mtps_version: v=AX.60
---

# Define how trade allowance works in your organization 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Before you can create trade allowance funds or trade allowance agreements, you must define how trade allowance management works in your organization. You can enable or disable functionality and rules as appropriate, and you can set default values for activities such as billbacks and deductions. This topic explains how to set up trade allowance management for your organization.

To set up your configuration of trade allowance management, follow these steps:

1.  Click **Trade allowance management** \> **Setup** \> **Trade allowance management parameters**.

2.  In the **Trade allowance management parameters** form, in the left pane, click **Overview**.

3.  On the **General** FastTab, select or enter information in the following fields:
    
      - **End of period template** – Select the template to apply to automatically generate an end-of-period promotion from the **Deduction workbench**. Templates are created in the **Templates** form (**Trade allowance management** \> **Periodic** \> **Templates**).
    
      - **Planned status** – Select the status that must be applied to a promotion before it can be included in the analysis of planned promotion amounts.
    
      - **Customer hierarchy** – Select the customer hierarchy group to assign to all new promotions. When a new promotion is created, the customer hierarchy can be changed.

4.  On the **Lump sum** FastTab, enter information in the following fields:
    
      - **Expense account** – Select the expense account from which the lump sum payments are provided. Expenses that are related to a lump sum are tracked in this account after the lump sum is paid.
    
      - **Procurement category** – Select the procurement category to use when a lump sum is paid to a vendor. The category that the payment is posted against determines the expense account from which the payment is taken.

5.  On the **Deductions** FastTab, in the **Deduction journal name** field, select the journal where deductions will be posted.

6.  On the **Funds** FastTab, select the **Include closed** check box to include closed or completed promotions when trade allowance funds are analyzed.

7.  On the **Method was called incorrectly.** FastTab, in the **Default rebate program ID** field, select the rebate program that is automatically assigned to all promotions or marketing activities that include rebates.

## Related tasks

[Set up customer category hierarchies for trade allowance](set-up-customer-category-hierarchies-for-trade-allowance.md)

Set up rebates

[Set up customer category hierarchies for trade allowance](set-up-customer-category-hierarchies-for-trade-allowance.md)

Set up trade allowance agreements

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
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

