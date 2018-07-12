---
title: Set up sales tax on prepayments
TOCTitle: Set up sales tax on prepayments
ms:assetid: 35de1531-7859-444c-9097-c48554abb27c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa570122(v=AX.60)
ms:contentKeyID: 36056569
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up sales tax on prepayments 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A tax authority can require that an organization must record sales taxes on prepayments from customers, even when a sale has not been made. Use the following procedure to set up sales tax on prepayments.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Ledger and sales tax**.

3.  Click the **Payment** FastTab. Select the **Sales tax on prepayment journal voucher** check box. Sales tax is calculated and posted whenever a prepayment journal voucher is posted.

4.  In the **Posting profile with prepayment journal voucher** field, select a posting profile that defines the ledger account to which the sales tax transactions on prepayments are posted temporarily.
    

    > [!NOTE]
    > <P>You create a posting profile for this purpose in the <STRONG>Customer posting profiles</STRONG> form. Specify the appropriate ledger account on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Sales tax prepayments</STRONG> field.</P>



5.  When you post a prepayment journal voucher through a journal, select the **Amounts include sales tax** check box in the **Journal** form.
    

    > [!IMPORTANT]
    > <P>If you omit this step, the sales tax is not posted correctly.</P>



When a sales invoice is created and the prepayment journal voucher is settled, an automatic transaction on the sales tax prepayments account offsets the first temporary sales tax transaction.

  


