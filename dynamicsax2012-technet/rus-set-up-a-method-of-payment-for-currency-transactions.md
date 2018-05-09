---
title: (RUS) Set up a method of payment for currency transactions
TOCTitle: (RUS) Set up a method of payment for currency transactions
ms:assetid: c65bf8d9-10f7-4a3b-b267-19c4c6f8fce2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ856192(v=AX.60)
ms:contentKeyID: 50407075
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a method of payment for currency transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Methods of payment - vendors** form to set up a method of payment for currency transactions.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a new method of payment.

3.  On the **General** FastTab, in the **Bank transaction type** field, select the type of bank transaction.
    

    > [!NOTE]
    > <P>This field is available only when you select <STRONG>Bank</STRONG> in the <STRONG>Account type</STRONG> field.</P>



4.  In the **Payment account** field, select the ID of the bank account.

5.  On the **File formats** FastTab, click **Setup** to open the **File formats for methods of payment** form.

6.  On the **Export** tab, in the **Available** list, select **Currency transfer order**.

7.  Click **\<** to move the selected export file format to the **Selected** list.

8.  Close the **File formats for methods of payment** form.

9.  In the **Methods of payment - vendors** form, in the **Export format** field, select **Currency transfer order** as the format for the export of payments.

## See also

[(RUS) Methods of payment - vendors (modified form)](https://technet.microsoft.com/en-us/library/jj711469\(v=ax.60\))

[(RUS) Create and post a payment journal for an exchanged currency](rus-create-and-post-a-payment-journal-for-an-exchanged-currency.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

