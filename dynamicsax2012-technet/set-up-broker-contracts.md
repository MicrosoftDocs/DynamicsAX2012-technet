---
title: Set up broker contracts
TOCTitle: Set up broker contracts
ms:assetid: 8932fd35-1f4a-40f6-a953-97c848a9edd5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497798(v=AX.60)
ms:contentKeyID: 62500053
ms.date: 06/11/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.CustParameters
- Forms.RetailMCRChannelListPage
---

# Set up broker contracts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up a broker contract that specifies the commission that a broker vendor receives for the sale of items or groups of items. For example, you might have a contract with a broker that states that every time a specific model of television is sold, the broker receives a percentage of the sales price. Commissions can be calculated based on a fixed amount, a percentage, or an amount per unit.

## Prerequisites

Before you set up a broker contract, you must enable price details in sales orders and purchase orders. For more information, see [Enable price details on orders](enable-price-details-on-orders.md).

## 1\. Set up a broker contract

Use this procedure to set up a broker contract. You can define a contract based on a single item, an item group, or all items. When a worker creates a sales order, a broker contract can be assigned to the sales order as necessary.

1.  Click **Accounts payable** \> **Common** \> **Broker** \> **Broker contracts**.

2.  In the **Broker contracts** form, click **Create a new record**, and in the **Broker contract ID** field, enter a contract ID.

3.  In the **Description** field, enter a brief description of the contract and then, in the **Broker vendor account** field, select the account number for the broker.

4.  Select the start date and end date of the broker contract, and then, in the **Charges code** field, select the charge code to be applied to the contract.

5.  In the **Category** field, select whether the contact is based on a per-unit amount, a percentage of the sales price, or a fixed amount.

6.  In the **Charges value** field, enter the percentage or amount that the broker will receive and then, in the **Charges currency code** field, select the currency in which the broker is paid.

## 2\. Add lines to a broker contract

Use this procedure to add items to a broker contract.

1.  Click **Accounts payable** \> **Common** \> **Broker** \> **Broker contracts**.

2.  In the **Broker contracts** form, select the contract to add lines to, and in the **Contract details** pane, click **Add line**.

3.  In the **Item code** field, select how items are added to the broker contract:
    
      - **Table** – The broker contract applies to a single item.
    
      - **Group** – The broker contract applies to an item group.
    
      - **All** – The broker contract applies to all items.

4.  If you selected **Table** or **Group** in the **Item relation** field, select the appropriate item or item group.

5.  In the **Account code** field, select the customer groups to which this contract will be applied, and then select the appropriate customer information in the **Account selection** field.

6.  In the **Charges code** field, select the charge code to be applied and then, in the **Break type** field, select whether the agreement is based on unit quantity or unit cost.

7.  In the **Break** field, enter the agreement amount or quantity for the selected break type.

8.  In the **Category** field, select the value that will be used to calculate the fee and then, in the **Charges value** field enter the percentage or amount that the broker will receive.

9.  In the **Sales tax group** field, select the appropriate sales tax group, and then, in the **Charges currency code** field, select the currency for the contract line.

10. In the **Broker contracts** pane, in the **Status** field, select **Approved**.

## Related tasks

[Set up margin alerts](set-up-margin-alerts.md)

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
<td><p><strong>Call center</strong>, <strong>Broker</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Retail catalog manager, retail operations manager and retail sales manager</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

