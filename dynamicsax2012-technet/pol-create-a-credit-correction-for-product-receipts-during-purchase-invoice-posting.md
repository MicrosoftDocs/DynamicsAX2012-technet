---
title: (POL) Create a credit correction for product receipts during purchase invoice posting
TOCTitle: (POL) Create a credit correction for product receipts during purchase invoice posting
ms:assetid: 96c763b7-d0cf-4abf-a337-13c4f239b110
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678303(v=AX.60)
ms:contentKeyID: 49387025
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (POL) Create a credit correction for product receipts during purchase invoice posting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

By using the **Posting product receipt** form, you can post a product receipt for credit correction for a purchase order. The posted product receipt is reversed when the invoice is posted as a correction transaction.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order**.

2.  In the **Create purchase order** form, enter the required details, and then click **OK**. For more information, see [Create purchase order (form)](https://technet.microsoft.com/en-us/library/aa570189\(v=ax.60\)).

3.  In the **Purchase order** form, enter the required details. For more information, see [Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\)).

4.  On the **Action Pane**, on the **Purchase** tab, in the **Generate** group, click **Confirm**.

5.  On the **Action Pane**, on the **Receive** tab, in the **Generate** group, click **Product receipt**.

6.  In the **Posting product receipt** form, on the **Overview** tab, in the **Product receipt** field, enter the product receipt number.

7.  Enter any additional information, and then click **OK** to post the product receipt and close the **Posting product receipt** form.

8.  In the **Purchase order** form, on the **Invoice** tab, in the **Generate** group, click **Invoice**.

9.  In the **Vendor invoice** form, enter the required details. For more information, see [Vendor invoice (form)](https://technet.microsoft.com/en-us/library/hh209644\(v=ax.60\)).

10. On the **Process** tab, click **Credit setup**.

11. In the **Select the credit settings for the invoice** form, select the **Credit correction** check box, and then click **OK**.

12. In the **Vendor invoice** form, on the **Vendor invoice** tab, in the **Actions** group, click **Post**.

13. In the **Select the posting settings** form, click **Print settings** to select print options, and then click **Post** to perform the following:
    
      - Reverse a debit transaction by adding a minus debit transaction to the ledger account for product receipts.
    
      - Reverse a credit transaction by adding a minus credit transaction to the offset account for product receipts.


> [!TIP]
> <P>To view the postings, on the <STRONG>Invoice</STRONG> tab, in the <STRONG>Journals</STRONG> group, click <STRONG>Invoice</STRONG>, and then, in the <STRONG>Invoice journal</STRONG> form, on the <STRONG>Overview</STRONG> tab, click <STRONG>Voucher</STRONG>.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

