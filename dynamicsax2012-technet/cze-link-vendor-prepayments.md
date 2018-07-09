---
title: (CZE) Link vendor prepayments
TOCTitle: (CZE) Link vendor prepayments
ms:assetid: 8525f065-8af0-4141-b94a-978289771f43
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677593(v=AX.60)
ms:contentKeyID: 49384896
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (CZE) Link vendor prepayments [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can link prepayments paid to vendors to advance invoices, either before or after posting. You can link one prepayment to several advance invoices, or you can link one advance invoice to several prepayments. A warning is displayed if the advance invoice or the prepayment is already linked. You can select the **Prohibit in journals** check box in the **Accounts payable parameters** form to prevent value-added tax (VAT) posting in vendor journals. You can use one of the following methods to link a prepayment to an advance invoice.

## For advance invoices that have not been closed

1.  Click **Accounts receivable** \> **Common** \> **Advance invoices** \> **All advance invoices**. To open an existing advance invoice, double-click the advance invoice. To create a new advance invoice, on the **Action Pane**, on the **Advance invoice** tab, click **Advance invoice**.

2.  On the **Action Pane**, in the **Actions** group, click **Post** to post the advance invoice.

3.  On the **Action Pane**, in the **Related information** group, click **Prepayment** to open the **Linking prepayments to advance invoices** form.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

4.  Select a payment journal, and then click **Lines**.

5.  In the **Journal voucher** form, click **Functions** \> **Link to advance invoices**.

## For open customer transactions

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select a customer account. On the **Action Pane**, click **Transactions**.

2.  Click **Link to advance invoices**.
    

    > [!NOTE]
    > <P>Before linking prepayments to an advance invoice, click <STRONG>Post</STRONG> in the <STRONG>Advance invoice</STRONG> form to post the advance invoice.</P>



## See also

[(CZE) Payment proposal from advance purchase invoice](cze-payment-proposal-from-advance-purchase-invoice.md)

[(CZE) Create a vendor advance invoice](cze-create-a-vendor-advance-invoice.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

