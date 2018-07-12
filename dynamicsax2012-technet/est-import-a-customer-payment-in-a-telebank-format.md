---
title: (EST) Import a customer payment in a telebank format
TOCTitle: (EST) Import a customer payment in a telebank format
ms:assetid: bfbf4bf5-8873-4e97-a2ff-ee47cef44fc6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ713648(v=AX.60)
ms:contentKeyID: 49643142
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Estonia
---

# (EST) Import a customer payment in a telebank format 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you set up the import of telebank payments from customers, you can import a payment from a customer by using the telebank format.

For more information, see [(EST) Set up the import of telebank payments from customers](est-set-up-the-import-of-telebank-payments-from-customers.md).

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Click **New** to create a line, and then enter the required details.

3.  Click **Lines** to open the **Journal voucher** form.

4.  Click **Functions** \> **Import payments** to open the **Load diskette with payments** form.

5.  In the **Method of payment** field, select a method of payment that uses the Teleteenus or Telehansa import format.

6.  Click **OK** to open the **Import payments** form. Then, in the **Import file name** field, specify the location of the import file.

7.  Select the **Customer settlement** check box to link the imported payments to customer settlements.

8.  In the **Legal entity of the invoice** field, select a legal entity to search for all open payment transactions from that legal entity when the import is processed.
    
    To search for open payment transactions from all legal entities, select **All companies**.

9.  Click **OK** to process the import.

  


