---
title: Set up a trade allowance agreement for a promotion
TOCTitle: Set up a trade allowance agreement for a promotion
ms:assetid: 4d796809-0473-48cd-bc76-88fd37e37573
ms:mtpsurl: https://technet.microsoft.com/library/Dn497751(v=AX.60)
ms:contentKeyID: 62524057
author: Khairunj
ms.date: 06/24/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TAMPromotionParameters
audience: Application User
ms.search.region: Global
---

# Set up a trade allowance agreement for a promotion 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create a trade allowance agreement. A trade allowance is similar to a monetary reward where the customer is paid based on their performance during the promotion and sales of an agreed upon item or items. When your organization has contracted the funds to provide a promotion for one or more customers, you set up and define the promotion as a trade allowance agreement.

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
<td><p>Setting up trade allowances</p></td>
<td><p><a href="set-up-information-for-trade-allowance-agreements.md">Set up information for trade allowance agreements</a></p>
<p><a href="set-up-trade-allowance-funds.md">Set up trade allowance funds</a></p></td>
</tr>
</tbody>
</table>


## Create a trade allowance agreement

This procedure explains how to create a trade allowance agreement.

1.  Click **Trade allowance management** \> **Common** \> **Trade allowance agreements**.

2.  On the **Trade allowance agreements** list page, on the **Action Pane**, in the **New** group, click **Trade allowance**.

3.  In the **Trade allowance agreements** form, verify that **Header view** is selected on the **Action Pane**.

4.  On the **General** FastTab, enter the following information:
    
    1.  Enter a brief description and any additional details about the promotion.
    
    2.  Select the currency and the marketing objective, and, in the **Owner** field, enter the name of the worker who is responsible for the promotion.
    
    3.  In the **Dates** field group, select the trade allowance agreement period, or, in the **Order from** and **Order to** fields, enter the first and last dates that the trade allowance agreement is active.
    
    4.  Enter additional date information in the remaining date fields.
    
    5.  In the **Analysis** field group, enter the unit type of the item for the promotion. This is the unit type that will be used in the planned analysis of the promotion.
    
    6.  In the **Base units** field, enter the quantity that is typically ordered by the customer when there is no promotion.
    
    7.  In the **Lift percent** field, enter the planned net increase in sales that will result from the promotion.
    
    8.  In the **Promotional ship quantity** form, enter the total number of items that will be shipped throughout the duration of the promotion.

5.  On the **Customers** FastTab, in the **Hierarchy** filter, select a customer hierarchy group.

6.  In the list that is shown, select the customers that you want to add to the promotion, and then click **\>**.

7.  On the **Items** FastTab, click **Add products** to add one or more items to the promotion, and then enter or select the appropriate item information.

8.  On the **Funds** FastTab, click **Add line** to add a trade allowance fund. Select the fund for the promotion, and, in the **Event cost allocation %** field, enter the percentage of event costs that will be taken from the selected fund.
    

    > [!NOTE]
    > <P>You can use more than one fund to cover the costs of a promotion.</P>



9.  On the **Action Pane**, click **Line view** to add more detailed line information about the promotion.

10. On the **Merchandising event** FastTab, click **Add line**, and then enter a description of the merchandising event.

11. In the **Category** field, select the merchandising event category.
    
    The corresponding merchandising event type is automatically added in the **Default type** field.

12. Enter any additional information for the promotion.

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
<td><p><strong>Plan</strong></p>
<p><strong>Call center</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Marketing manager</p></td>
</tr>
</tbody>
</table>


## See also

[Manage trade allowance funds](manage-trade-allowance-funds.md)

[Set up information for trade allowance agreements](set-up-information-for-trade-allowance-agreements.md)

  


