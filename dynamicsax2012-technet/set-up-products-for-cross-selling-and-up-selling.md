---
title: Set up products for cross-selling and up-selling
TOCTitle: Set up cross-sell and up-sell
ms:assetid: 13969b82-785b-4bfe-977f-5fe43751cf1f
ms:mtpsurl: https://technet.microsoft.com/library/Dn497716(v=AX.60)
ms:contentKeyID: 62279210
author: tonyafehr
ms.date: 05/07/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.EcoResProductPerCompanyListPage
audience: Application User
ms.search.region: Global
---

# Set up products for cross-selling and up-selling 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up products for cross-selling or up-selling. Cross-selling and up-selling are techniques in which a seller tries to sell a product either in addition to the current product or instead of the current product when an order is entered for a customer. You can create rules to indicate when a product should be suggested as a cross-sell or up-sell product.

## Define variables, conditions, and rules for cross-selling and up-selling products

Before you create a rule, you must create the variables and conditions that define what products the rule applies to and when the rule should be applied. For example, you want to create a rule to require that when a customer in customer group 491 orders product **009 – Full finger gloves**, which is priced at 12.00, the customer service representative must suggest product **016 – Premium full finger gloves**, which is priced at 15.00, as an alternative. This rule requires that every time product 009 is ordered by a customer in group 491, the customer service representative must attempt to sell product 016 instead.

In this example, the variables are customer group 491 and product numbers 009 and 016. The conditions are that the customer must be in customer group 491 and the sale must include product number 009. When these conditions are met, product 016 should be offered to the customer in place of product number 009.

Use the procedures in this section to set up the variables, conditions, and rules that will be applied to products that are eligible for cross-selling or up-selling.

## Define variables

1.  Click **Sales and marketing** \> **Setup** \> **Up-sell/cross-sell** \> **Variables**.

2.  In the **Up sell / cross sell rule details** form, click **Create a new record** and enter a name for the variable.

3.  In the **Variable table** field, select the table that contains the field variable, and then enter a brief description of the field.
    
    For the example above, you would select **CustGroup**, because that is the table that contains customer group numbers.

4.  In the **Field** field, select the field whose value will be used as the variable.
    
    For the example above, you would select **CustGroup**, because that is the field where the customer group number is stored.

## Define conditions

This procedure describes how to create conditions by using the **Conditions** form. You can also create conditions in the **Rules** form, and then apply a condition directly to a rule in the form.

1.  Click **Sales and marketing** \> **Setup** \> **Up-sell/cross-sell** \> **Conditions**.

2.  In the **Conditions** form, click **New**, and then enter a name and description for the condition.

3.  In the **Condition table** field, select the table on which the condition will be based.
    
    For the example above, you would select the **CustGroup** table.

4.  On the **Fields** FastTab, click **Add**, and then enter the elements of the condition.
    
    For example, to specify that a condition applies to members of the customer group 491, you enter the following values for the condition:
    
      - **Field type** – **Table field**
    
      - **Field** – **CustGroup**
    
      - **Value type** – **Value**
    
      - **Operand** – **=**
    
      - **Value** – **491**

## Define rules

Use this procedure to define an up-sell or cross-sell rule that uses the variables and conditions that you created in the previous procedures.

1.  Click **Sales and marketing** \> **Setup** \> **Up-sell/cross-sell** \> **Rules**.

2.  In the **Rules** form, click **New** and enter a name and description for the rule.

3.  On the **Conditions** FastTab, add the conditions for the rule.

4.  Click **Test rule** to verify that the rule works.

## Identify and set up products for cross-sell or up-sell

Use this procedure to identify and set up products that are eligible for cross-selling or up-selling.

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Select the product to which you will add an eligible cross-sell or up-sell product.

3.  On the **Action Pane**, on the **Setup** tab, click **Show up-sell/cross-sell items for an item**.

4.  In the **Up-sell/cross-sell items** form, in the **Linked item** field, select the products to be offered as cross-sell or up-sell items.

5.  In the **Priority** field, enter a number that identifies the priority of up-selling or cross-selling this product. For example, there might be two linked products that are eligible for either up-selling or cross-selling: item 1010 and item 1012. If you have twice as much of product 1010 in stock as you have of product 1012, you might indicate that cross-selling product 1010 is the highest priority, because you want to reduce the inventory count of that product.

6.  Select whether the product is a cross-sell or up-sell product.

7.  Optional: In the **Rule name** field, enter the rule that is associated with this product.

8.  On the **Script** tab, click **Add** to add a script or note that can be read or spoken during the sale.

9.  Select the **Active** check box to indicate that the script or note should be shown to the customer service representative during the sales process.

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
<td><p>Sales manager, Sales clerk, Retail catalog manager</p></td>
</tr>
</tbody>
</table>


## See also

Create a sales order in call center

  


