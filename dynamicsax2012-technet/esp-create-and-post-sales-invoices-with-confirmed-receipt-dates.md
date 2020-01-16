---
title: (ESP) Create and post sales invoices with confirmed receipt dates
TOCTitle: (ESP) Create and post sales invoices with confirmed receipt dates
ms:assetid: 736b2be2-7fb5-4ea9-9a1a-0b3807a85027
ms:mtpsurl: https://technet.microsoft.com/library/JJ923604(v=AX.60)
ms:contentKeyID: 52075221
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Spain
---

# (ESP) Create and post sales invoices with confirmed receipt dates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Sales order** and **Posting invoice** forms to create and post sales invoices that have confirmed receipt dates to calculate invoice due dates. Specify a date in the **Confirmed receipt date** field on the **Sales order header** FastTab in the **Sales order** form. This date is used as the delivery date to calculate the invoice due date.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order and add sales order lines. For more information, see [Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\)).

3.  On the **Sales order header** FastTab, in the **Confirmed receipt date** field, select a date.

4.  Click **Sell** \> **Sales order confirmation** to confirm the sales order.

5.  Click **Invoice** \> **Invoice** to open the **Posting invoice** form.

6.  Select the posting criteria, and then click **OK** to post and generate the sales invoice. The invoice due date is calculated using the confirmed receipt date.
    

    > [!NOTE]
    > <P>If a due date limit is set up in the <STRONG>Item groups</STRONG> and <STRONG>Terms of payment</STRONG> forms, the calculated invoice due date is verified against the due date limit, and is adjusted to comply with the effective due date limit. For more information, see <A href="esp-about-using-delivery-dates-to-calculate-invoice-due-dates.md">(ESP) About using delivery dates to calculate invoice due dates</A>.</P>



## See also

[(ESP) Item group (modified form)](https://technet.microsoft.com/library/jj923620\(v=ax.60\))

[(ESP) Terms of payment (modified form)](https://technet.microsoft.com/library/jj910987\(v=ax.60\))

  


