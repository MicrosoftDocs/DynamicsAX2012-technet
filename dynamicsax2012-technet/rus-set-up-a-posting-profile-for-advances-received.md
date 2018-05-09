---
title: (RUS) Set up a posting profile for advances received
TOCTitle: (RUS) Set up a posting profile for advances received
ms:assetid: eb6eddd0-206b-4324-b250-d3d24f204075
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711733(v=AX.60)
ms:contentKeyID: 49388056
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a posting profile for advances received 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In accordance with Russian accounting requirements, advance payments from customers are processed in a particular manner. After you register an advance payment from a customer, the amount is allocated to the Advances received subaccount of Account 62. At the same time, the VAT is allocated from the amount due to be paid into the budget. When the goods are shipped, the VAT accrual and payment from the facture amount are made. After settlement of the advance with the facture, the payment amount is carried over from the Advances received subaccount of Account 62 to the debtor debts subaccount of Account 62. The amount that is accrued from VAT is reversed and the reversed advance is reflected in the purchase book.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Press CTRL+N to create a new line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see "Customer posting profile (form)" in the Applications and Business Processes Help.</P>



3.  In the **Posting profile** field, enter a posting profile code for advance payments.

4.  In the **Description** field, enter a brief description of the posting profile.

5.  Click the **Setup** tab.

6.  In the **Summary account** field, select the ledger account to be used as the summary account for the customer.
    

    > [!NOTE]
    > <P>The accounts are posted to the Account 62, Advances received subaccount.</P>



7.  In the **Sales tax prepayments** field, select the account number for the sales tax portion of the advance payment.

8.  Press CTRL+S or close the form.

## See also

[(RUS) Set up customer parameters for advance payment](rus-set-up-customer-parameters-for-advance-payment.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

