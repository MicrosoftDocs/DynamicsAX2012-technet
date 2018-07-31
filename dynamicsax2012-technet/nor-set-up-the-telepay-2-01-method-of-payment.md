---
title: (NOR) Set up the Telepay 2.01 method of payment
TOCTitle: (NOR) Set up the Telepay 2.01 method of payment
ms:assetid: ec0806e1-0f5c-45d5-9983-fde5bb4e8999
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243252(v=AX.60)
ms:contentKeyID: 36059891
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Norway
---

# (NOR) Set up the Telepay 2.01 method of payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use electronic payment methods to make payments to vendors. When the bank processes a payment, you receive a file from the bank. You must import the file and post the journal to post the transactions to the ledger. One of the formats that you can use to make electronic payments to vendors is Telepay 2.01.

You can create a payment proposal and export the file by using an available export format. You can send the file to the bank by using the bank’s software, and then import the return file that you receive from the bank to approve or reject the transactions and identify any errors.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a method of payment for Telepay 2.01.

3.  Click the **File formats** FastTab, and then select **Telepay 2.01** as the export file format and return file format.

4.  Click the **Payment control** FastTab, and then select the additional validation criterion that is used when you post the journal by using the Telepay 2.01 method of payment.

5.  Close the form to save your changes.
    

    > [!NOTE]
    > <P>When you define the method of payment, it is attached to the vendor records and automatically becomes the current method of payment to record incoming invoices. You can also change the method of payment for the record before you settle the invoice.</P>



## See also

[Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\))

  


