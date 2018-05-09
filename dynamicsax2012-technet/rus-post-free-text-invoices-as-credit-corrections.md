---
title: (RUS) Post free text invoices as credit corrections
TOCTitle: (RUS) Post free text invoices as credit corrections
ms:assetid: 00827eed-188a-4543-b3bc-42ed5ad5f9e4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ682108(v=AX.60)
ms:contentKeyID: 49655690
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Post free text invoices as credit corrections 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post free text invoices as credit corrections for return item transactions. Use the following procedure to correct a free text invoice that has both positive and negative invoice amounts.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select an existing free text invoice for an item that was returned.

3.  Click the **Invoice lines** FastTab, and then add an invoice line that has a positive or negative invoice amount, depending on the type of correction. For more information about negative invoices, see [About credit notes](about-credit-notes.md).

4.  Click **Post** to open the **Post free text invoice** form.

5.  Select the **Credit correction** check box, and then click **OK** to post the invoice, which has either a positive sign or a negative sign depending on the direction of the correction. If the invoice amount is positive, you receive a message that indicates that the parameter for credit correction is activated.

6.  Click **Yes** to post the invoice.

7.  Click **Related information** \> **Invoice journal** to open the **Invoice journal** form.

8.  Click **Transactions** to open the **Customer transactions** form. Confirm that the transaction is generated as a correction for the return item transaction.

9.  Click **Voucher** to open the **Voucher transactions** form. Confirm that the transaction is posted as a correction.
    

    > [!NOTE]
    > <P>By default, the <STRONG>Correction</STRONG> check box is selected in the <STRONG>Customer transactions</STRONG> and <STRONG>Voucher transactions</STRONG> forms.</P>



## See also

[Free text invoice (form)](https://technet.microsoft.com/en-us/library/aa556897\(v=ax.60\))

[(RUS) Post vendor invoices as credit corrections](rus-post-vendor-invoices-as-credit-corrections.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

