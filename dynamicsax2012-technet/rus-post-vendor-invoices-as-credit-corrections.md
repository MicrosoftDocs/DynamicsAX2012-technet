---
title: (RUS) Post vendor invoices as credit corrections
TOCTitle: (RUS) Post vendor invoices as credit corrections
ms:assetid: 6071c514-6ee4-4a40-9bd2-187c6c41e5e5
ms:mtpsurl: https://technet.microsoft.com/library/JJ733236(v=AX.60)
ms:contentKeyID: 49685203
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Post vendor invoices as credit corrections 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post vendor invoices as credit corrections for return item transactions. Use the following procedure to correct vendor invoices that have both positive and negative invoice amounts.


> [!NOTE]
> <P>Before you post a vendor invoice, you must select the <STRONG>Correction</STRONG> parameter in the <STRONG>General ledger parameters</STRONG> form and the <STRONG>Credit note as correction</STRONG> parameter in the <STRONG>Accounts payable parameters</STRONG> form.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click an existing purchase order for an item that was returned. Alternatively, click **Purchase order** to create a new purchase order, and then enter the required details. For more information, see [Create a purchase order](create-a-purchase-order.md).

3.  Click **Add line** to add a new purchase order line that has either a positive or negative invoice amount, depending on the type of correction.

4.  Click **Purchase** \> **Confirm** to confirm the purchase order.

5.  Click **Invoice** \> **Invoice** to generate a vendor invoice for the purchase order.

6.  In the **Default quantity for lines** field, select **Ordered quantity**.

7.  Click the **Process** FastTab, and then click **Credit setup** to open the **Select the credit settings for the invoice** form.

8.  Select **Credit correction** to mark the transaction as a correction, and then click **OK**.

9.  Click the **Vendor invoice** tab, and then, in the **Number** field, enter the invoice number.

10. Click **Post** to post the invoice that has either a positive or negative sign to indicate the direction of the correction. If the invoice amount is positive, you receive a message that indicates that the credit correction parameter is activated.

11. Click **Yes** to open the **Select the posting settings** form.

12. Click **Post** to post the invoice.

13. In the **Purchase order** form, in the **Journals** group, click **Invoice** to open the **Invoice journal** form. Confirm that the transaction is generated as a correction.

14. Click **Voucher** to open the **Voucher transactions** form, and confirm that the transaction is posted as a correction.

## See also

[(RUS) Post free text invoices as credit corrections](rus-post-free-text-invoices-as-credit-corrections.md)

[(RUS) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj733265\(v=ax.60\))

  


