---
title: (HUN) Create and post a purchase order invoice with a specific VAT register date
TOCTitle: (HUN) Create and post a purchase order invoice with a specific VAT register date
ms:assetid: d213fdc0-51f0-4bbf-96c0-57eda34ec91e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664382(v=AX.60)
ms:contentKeyID: 49385471
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- VAT register date
---

# (HUN) Create and post a purchase order invoice with a specific VAT register date 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you post a vendor invoice, you can select a date for reporting value-added tax (VAT) that differs from the date of the transaction. Use this procedure to create and post a purchase order that has a specific VAT register date.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

2.  In the **Create purchase order** form, enter the required information, and then click **OK**.

3.  In the **Purchase order** form, enter the purchase order lines. For more information, see [(HUN) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj714544\(v=ax.60\)) and [Create a purchase order](create-a-purchase-order.md).

4.  On the **Action Pane**, on the **Purchase** tab, in the **Generate** group, click **Confirm**.

5.  After you receive the items, on the **Action Pane**, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

6.  In the **Vendor invoice** form, on the **Vendor invoice header** FastTab, in the **Invoice dates** field group, in the **Date of VAT register** field, select the transaction date for the VAT register.

7.  Enter any additional information, and then, on the **Action Pane**, on the **Vendor invoice** tab, in the **Actions** group, click **Post**.

8.  In the **Select the posting settings** form, select posting options, and then click **Post**.

When you post an invoice that has a VAT register date that occurs in the future, the amount of VAT is posted to a temporary account, and is later posted to the VAT account on the selected register date.

## See also

[(EEUR) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj710700\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

