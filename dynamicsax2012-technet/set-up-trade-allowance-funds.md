---
title: Set up trade allowance funds
TOCTitle: Set up trade allowance funds
ms:assetid: daad2d1f-d1c6-4fc7-ae42-d04fbbb7c8a4
ms:mtpsurl: https://technet.microsoft.com/library/Dn497835(v=AX.60)
ms:contentKeyID: 62500054
author: tonyafehr
ms.date: 06/10/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TAMPromotionParameters
- Forms.TAMPromotionPeriod
audience: Application User
ms.search.region: Global
---

# Set up trade allowance funds 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Funds for a trade allowances must be allotted before the trade allowance agreement can be finalized. This topic explains how to set up trade allowance funds.

## 1\. Set up fund usage records

Use this procedure to set up categorized reasons for using funds for trade allowance.

1.  Click **Trade allowance management** \> **Setup** \> **Fund usage**.

2.  In the **Usage** form, click **New**.

3.  In the **Usage** field, enter the name of the cost center that is providing the funds and then enter a brief description of the cost center. For example, you might enter the name **Marketing** with the description **Marketing share**.

## 2\. Set up funds for trade allowances

Use this procedure to set up funds for trade allowances.

1.  Click **Trade allowance management** \> **Periodic** \> **Funds**.

2.  In the **Funds** form, click **Create a new record**.

3.  In the **Description** field, enter a description of the fund.

4.  In the **Type** field, select whether the fund is discretionary and then, in the **Status** field, select the status of the fund.

5.  In the **From date** and **To date** fields, enter the start date and end date of which the fund is available.

6.  In the **Fund budgeted** field, enter the amount that has been budgeted for the fund, and in the **Notes** field, enter any additional information about the budgeted funds.

7.  In the **Usage** field, select the cost center that is providing the funds, and in the **Fund budgeted** field, enter the maximum amount allowed for the fund.

8.  On the **Customers** FastTab, in the hierarchy field, select a customer group or individual customers in the group, and then click **\>**.

9.  If you want to distribute the budgeted funds across the customer hierarchies that you selected, select the customer hierarchy to distribute funds to, and then, under **Current hierarchy level**, in the **Budgeted** field, enter the amount to distribute.

10. On the **Items** FastTab, click **Add products**.

11. In the **Add products** form, in the **Filters** pane, use the **Hierarchy** filter to select a hierarchy.

12. In the tree, select a product group that contains available products, and then, in the **Available products** pane, select one or more products to add. Click **Add**.

13. Click **OK**, and in the **Funds** form, in the **Status** field, select **Approved**.

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
<td><p><strong>Call center</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>System administrator for basic setup and Marketing manager to create the allowance</p></td>
</tr>
</tbody>
</table>

  


