---
title: Set up rebates
TOCTitle: Set up rebates
ms:assetid: 05700e30-e843-4288-912d-f533e3b53a8d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497709(v=AX.60)
ms:contentKeyID: 62500052
ms.date: 06/10/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TAMBillBackListPage
---

# Set up rebates [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up parameters, types, and groups for customer rebates. A rebate is a partial refund of a payment that a customer previously paid for an item or service. Rebates are usually given as part of a promotion or marketing activity. A customer can use a rebate as a deduction on an outstanding balance or take the amount of the rebate as a credit. Rebates are configured so that the appropriate department and promotional category in your organization is billed appropriately for the credit that is returned to the customer.

## 1\. Configure rebate parameters

Use this procedure to configure the default journal information for rebates that are offered by your organization.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  In the **Accounts receivable parameters** form, in the left pane, click **Rebate program**.

3.  To create a customer rebate when the customer order is invoiced, select the **At invoicing** check box.

4.  In the **AR consumption journal** field, select the journal that will be used to post a credit note for the rebate amount in the name of the customer who will receive the rebate.

5.  In the **AP invoice journal** field, select the accounts payable journal to which rebates will be posted, and in the **Terms of payment** field, select the payment code that represents how rebates will be paid to vendors. In this situation, the customer is a vendor who is receiving the rebate. A vendor account must be created for the customer so that they can receive rebate payments.

6.  In the **Rebate accrual journal** field, select the journal to post accruals to when a rebate claim is processed. When the rebate is transferred to a customer or vendor account, the interim account to which the rebate was posted is cleared.

7.  In the **Trade spending journal** field, select the journal to use when posting trade allowance management type rebates.

8.  In the **Freight journal** field, select the journal to use when posting freight type rebates.

9.  If rebates are cumulated on a weekly basis, in the **Starting day of week** field, select the day of the week on which rebates should be cumulated.

## 2\. Set up rebate types

Use the procedure to set up types of rebates that can then be applied to a rebate program.

1.  Click **Sales and marketing** \> **Setup** \> **Rebate program** \> **Rebate program types**.

2.  In the **Rebate program types** form, click **New**.

3.  Enter the ID and a brief description of the rebate type.

4.  In the **Rebate program type** field, select the rebate type.

5.  In the **Default accrual account** field, select the main account to which accrued rebate amounts will be posted.

6.  In the **Default expense account** field, select the main account to which the expenses that are related to rebate claims will be posted.

7.  Repeat steps 2 through 6 to set up more rebate types.

## 3\. Set up customer rebate groups

Use this procedure to create customer rebate groups. After you set up the customer rebate groups, customers can be associated with a group. Next, you can define the rebate agreements for these groups.

1.  Click **Sales and marketing** \> **Setup** \> **Rebate program** \> **Customer** \> **Customer rebate groups**.

2.  In the **Customer rebate groups** form, click **New**.

3.  Enter a name and a brief description for the customer rebate group.

## 4\. Set up item rebate groups

Use this procedure to create item rebate groups. After you set up the rebate groups, items can be associated with a group. Next, you can define the rebate agreements for these groups.

1.  Click **Sales and marketing** \> **Setup** \> **Rebate program** \> **Item** \> **Item rebate groups**.

2.  In the **Item rebate groups** form, click **New**.

3.  Enter a name and a brief description for the item rebate group.

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
<td><p>Retail</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Marketing Manager, Accounts Receivable Administrator</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

