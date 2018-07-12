---
title: (IND) Calculate VAT for various sales order types
TOCTitle: (IND) Calculate VAT for various sales order types
ms:assetid: 85d7f503-2f83-485c-b5ec-81b4374e30ce
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677985(v=AX.60)
ms:contentKeyID: 49385949
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate VAT for various sales order types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  In the **All sales orders** list, on the **Action Pane**, on the **Sales order** tab, in the **New** group, click **Sales order**.

3.  In the **Create sales order** form, select a customer.
    
      - Click **Yes** to copy the delivery address, shipping location time zone, invoice account number, currency, mode of delivery, and language (if defined) to the sales order.
    
      - Click **No** to create the new form without previous customer sales information.

4.  Select an order type in the **Order type** field for the current transaction, and then click **OK**.

5.  In the lower pane, press CTRL+N to create a new sales order line

6.  Enter the required details.

7.  Click the **Setup** tab (lower pane) and select the item sales tax group for VAT for the item in the **Item sales tax group** field.

8.  Select the sales tax group for the transaction in the **Sales tax group** field.

9.  On the **Action Pane**, on the **Sell** tab, in the **Tax** group, click **Sales tax** to view the VAT calculated for the order line and order type in the **Temporary sales tax transactions** form.

10. Close the **Temporary sales tax transactions** form to return to the **Sales order** form.

11. Post the sales order. The VAT amount is calculated and posted to the VAT payable account.

## See also

[(IND) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj677998\(v=ax.60\))

[(IND) Temporary sales tax transactions (modified form)](https://technet.microsoft.com/en-us/library/jj664487\(v=ax.60\))

  


