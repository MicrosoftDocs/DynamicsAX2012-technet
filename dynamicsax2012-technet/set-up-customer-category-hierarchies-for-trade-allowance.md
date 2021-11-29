---
title: Set up customer category hierarchies for trade allowance
TOCTitle: Set up customer category hierarchies for trade allowance
ms:assetid: 633b9605-eb89-444a-96eb-60fc2f37b99c
ms:mtpsurl: https://technet.microsoft.com/library/Dn497780(v=AX.60)
ms:contentKeyID: 62200083
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.MCRCustCategoryHierarchy
audience: Application User
ms.search.region: Global
---

# Set up customer category hierarchies for trade allowance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create customer category hierarchies for trade allowance. You can use customer category hierarchies to group customers that have similar characteristics, such as region or line of business. Before you can add a customer to a fund, trade allowance agreement, or trade allowance template, you must create customer category hierarchies and add customers to those hierarchies.

## Create customer category hierarchies

Use this procedure to create a customer category hierarchy.

1.  Click **Trade allowance management** \> **Setup** \> **Customer category hierarchy**.

2.  In the **Category hierarchy** form, click **New**, and in the **Name** field, enter a name for the category hierarchy. For example, if you were creating a category hierarchy for regions in a geographical location, you might call it **Customer by region**.

3.  On the **Categories** FastTab, select the category node, and in the **Name** field, enter the name of the parent category. Following the example from step 1, you might call the parent category **Regions**.

4.  Click **New category node**, select the new category node, and then, in the **Name** field, enter the name for the subcategory.

5.  Repeat step 4 until you have added all of the required subcategories.

6.  Optional: If the subcategories require their own subcategories, select the appropriate subcategory, click **New category node**, and enter the new category name.

## Add customers to a customer category hierarchy

Use this procedure to add one or more customers to a category hierarchy.

1.  Click **Trade allowance management** \> **Setup** \> **Customer category hierarchy**.

2.  In the **Category hierarchy** form, click **Add / remove customer**.

3.  In the **Customer category** form, in the left pane, select the category that you are adding customers to.

4.  On the **Customers** FastTab, click **New**.

5.  In the **Add customers** form, in the **Customers** list, select the customers that should be added to the category, and then click **Select -\>**.
    
    To remove a customer, in the lower-right pane of the form, select the customer records that you want to remove, and then click **Remove**.

6.  After you have added the appropriate customers to the category, click **OK**.

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
<td><p>TAMPromotionsManagement</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales representative</p>
<p>Sales manager</p></td>
</tr>
</tbody>
</table>


## See also

Set up a trade allowance template

Set up trade allowance agreements

[Working with trade allowance](working-with-trade-allowance.md)

  


