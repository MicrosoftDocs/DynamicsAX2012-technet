---
title: (RUS) Post taxes in a sales order
TOCTitle: (RUS) Post taxes in a sales order
ms:assetid: 5ca7f69f-a180-46cb-af4d-e7f77f035afc
ms:mtpsurl: https://technet.microsoft.com/library/JJ665422(v=AX.60)
ms:contentKeyID: 49387510
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Post taxes in a sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Press CTRL+N to create a sales order, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Create a sales order" and "Sales orders (form)" in the Applications and Business Processes Help.</P>



3.  If the item price includes sales tax, click the **Setup** tab (upper pane) and select the **Prices incl. sales tax** check box.

4.  Click the **Setup** tab (lower pane). In the **Item sales tax group** field, select the item sales tax group to determine the tax.
    

    > [!NOTE]
    > <P>If the item sales tax group code is already specified for the item, then the item sales tax group will be updated automatically.</P>



5.  In the **Sales tax group** field, select the sales tax group to determine the tax.
    

    > [!NOTE]
    > <P>If the tax group code is already specified for the customer, then the tax group code will be updated automatically.</P>



6.  Click **Setup** (upper pane) \> **Sales tax** to view the calculated taxes for the sales order.

7.  In the **Sales order** form, click **Setup** (lower pane) \> **Sales tax** to view the calculated taxes for each line.

8.  Click **Posting** \> **Invoice** to open the **Posting invoice** form.

9.  In the **Invoice date** field, select the invoice posting date.
    

    > [!NOTE]
    > <P>The invoice is sequentially numbered according to the number sequences set up in the <STRONG>Accounts receivable parameters</STRONG> form.</P>



10. Click **OK** to post the invoice.

## See also

[(RUS) Set up sales tax groups for tax calculation](rus-set-up-sales-tax-groups-for-tax-calculation.md)

[(RUS) Set up item sales tax groups for tax calculation](rus-set-up-item-sales-tax-groups-for-tax-calculation.md)

  


