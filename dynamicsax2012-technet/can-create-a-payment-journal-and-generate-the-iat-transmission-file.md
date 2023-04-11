---
title: (CAN) Create a payment journal and generate the IAT transmission file
TOCTitle: (CAN) Create a payment journal and generate the IAT transmission file
ms:assetid: 5f87dd16-e48c-4f49-9835-2fb3bcd4a967
ms:mtpsurl: https://technet.microsoft.com/library/Hh209132(v=AX.60)
ms:contentKeyID: 36057592
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Canada
- payment journal
- IAT transmission file
audience: Application User
ms.search.region: Canada
---

# (CAN) Create a payment journal and generate the IAT transmission file 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To comply with the National Automated Clearing House Association (NACHA) operating rules, the RBC Electronic Fund Transfer (EFT) format includes new address records for both the originator of a payment and the customer or recipient of the payment. If the payment transaction originates from or is transmitted to a financial agency outside the territorial jurisdiction of the U.S., it is classified as an International ACH Transaction (IAT) by the RBC.

To generate an RBC transmission file, first create a payment journal for a customer or vendor.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.
    
    \-or-
    
    Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a payment journal, and then click **Lines**.

3.  Select a customer or vendor transaction with a U.S bank account.

4.  In the **Method of payment** field, select the method of payment for the RBC EFT format.

5.  Click **Functions** \> **Generate payments**.

6.  In the **Export format** field, select the **RBC Pre-Authorized Debits \[PADS\] Service (CA)** export format for a customer payment or **RBC Payment Distribution Service (CA)** for a vendor payment.

7.  Click **Dialog**.

8.  In the **File name** field, specify the name of the RBC transmission file and the path to store the file.

9.  In the **Currency** field, select either **Canadian currency** or **USD**.

10. Click **OK** to return to the **Generate payments** form.

11. Click **OK** to generate an RBC transmission file with the IAT ACH records.

## See also

[Journal voucher - Customer payment journal (form)](https://technet.microsoft.com/library/aa556141\(v=ax.60\))

[Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/library/aa599011\(v=ax.60\))

  


