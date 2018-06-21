---
title: Set up automatic sales tax group assignments
TOCTitle: Set up automatic sales tax group assignments
ms:assetid: c42be51c-6781-4145-8417-b10f1c19b879
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497824(v=AX.60)
ms:contentKeyID: 62200153
ms.date: 06/10/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxGroup
- tax group
- call center
- Forms.MCRAutoTaxRules
- default customer
- default customer tax group
---

# Set up automatic sales tax group assignments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to automatically assign sales tax groups to customer address records based on address information. When you set up the sales tax assignment based on default rules, you can determine a matching priority for address elements. For example, you can specify that matching a sales tax group by ZIP Code or postal code is a higher priority than matching a sales tax group by state. As you enter new customer address records, the sales tax group is automatically assigned based on how the customer’s address matches with the default rules and priority matching that you defined.

## Enable automatic assignment of sales tax groups

Use this procedure to allow sales tax groups to be automatically assigned to customer address records, follow these steps:

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  On the **Sales tax** tab, select the **Auto sales tax search** check box.

## Set up default rules for sales tax groups

Use this procedure to set up and define the rules that are used to automatically assign a sales tax group to a customer record based on the customer’s address. The rules determine the order in which to match address elements, for example city or state, to sales tax groups.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Tax group default rules**.

2.  If you want to display a warning message when a sales tax group isn’t automatically found for an address record, select the **Display warnings** check box.

3.  Click **New** to add a new rule.

4.  In the **Priority** field, enter a number to indicate the priority for matching the address elements, and then select a check box for each address element that will be included in the matching criteria.
    
    For example, if you enter **1** in the **Priority** field, and then select **City** and **ZIP/postal code**, these address elements will be reviewed first for matching a new address record to a sales tax group. You might then add a second line and enter **2** in the **Priority** field, and then select **County**. When Microsoft Dynamics AX compares the address elements, the priority one fields will be reviewed for a match. If there is no match, Microsoft Dynamics AX will look for a priority two match. The sales tax group will be assigned based on these priority matches.

5.  Repeat steps 3 and 4 to add more sales tax group default rules.

## Update information about sales tax groups

Use this procedure to update an existing sales tax group by adding default sales tax information that will be applied to customers who are assigned to the sales tax group based on their address. For information about how to create a new sales tax group, see [Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**. Select a sales tax group to update.

2.  On the **General** FastTab, in the **Designate default criteria** field group, select the address elements to use to determine what sales tax group is assigned to a customer address.
    
    For example, if you select the sales tax group **Denver1** that has a description of **Denver-80214**, the following selections might be made in the **Designate default criteria** field group:
    
      - **City**: Denver
    
      - **State**: Colorado
    
      - **County**: Jefferson
    
      - **ZIP/postal code**: 80214
    
      - **Country/region**: United States
    
    After you add this information to the sales tax group, the next time that a customer address is entered and the address matches the default criteria, the **Denver1** sales tax group will be automatically assigned to the customer address record.

## See also

[Set up and use a sales tax group](set-up-and-use-a-sales-tax-group.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

