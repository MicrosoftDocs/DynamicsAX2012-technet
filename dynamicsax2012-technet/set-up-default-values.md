---
title: Set up default values
TOCTitle: Set up default values
ms:assetid: f19d2130-cdf0-4dff-b6e1-73337d056faf
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551605(v=AX.60)
ms:contentKeyID: 36059952
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up default values 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In the **Default values** form, you can set up values that apply to a specific customer, a group of customers, or all customers. It is also possible to apply these values to one item, a group of items, or all items.


> [!NOTE]
> <P>This information applies only to Product builder.</P>



1.  Click **Product information management** \> **Setup** \> **Product builder** \> **Defaults** \> **Default values**.

2.  Press CTRL+N to create a new line.

3.  In the **Valid for** field, specify the type of customer relation that you want for the default value.
    
      - Select **Table** if you want the default value to be valid for one customer.
    
      - Select **Group** if you want the default value to be valid for a group of customers.
    
      - Select **All** for all customers.

4.  If you selected **Table** in the **Valid for** field, specify the necessary customer in the drop-down list.

5.  If you selected **Group**, specify the customer product-model group. Leave the **Customer relation** field blank if you want the default value to apply to all customers.

6.  In the second **Valid for** field and **Item relation** field, specify whether the default value will apply to a single item, a group of items, or all items. For a specific item or group, specify the item number or item product-model group. The procedure is the same as described in steps 3 and 4.

7.  In the lower pane, press CTRL+N to create a new line.

8.  In the **Variable** field, select the modeling variable that will have a default value for the specified customer and item combination.

9.  Type the desired default value in the **Value** field.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

