---
title: (BRA) Process electronic payment returns
TOCTitle: (BRA) Process electronic payment returns
ms:assetid: f081271e-fcd2-4ea0-9a71-d330ceb5cb35
ms:mtpsurl: https://technet.microsoft.com/library/JJ730979(v=AX.60)
ms:contentKeyID: 49675209
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- approved payment
- import a return file
- BR - 00008
audience: Application User
ms.search.region: Brazil
---

# (BRA) Process electronic payment returns 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can make electronic payments by transferring files between a legal entity and a bank:

  - You can generate and send an electronic remittance file to a bank. The export file contains information about invoices that must be received or paid, requests for return invoices, or changes to customer or vendor addresses. For more information, see [(BRA) Process electronic payment remittances](bra-process-electronic-payment-remittances.md).

  - You can import a return file from a bank. The return file contains information about the acceptance of an invoice together with the payment number that is provided by the bank. Alternatively, the return file contains information about the payments that are received from a customer or paid to a vendor.

Use this procedure to import a return file into Microsoft Dynamics AX. When you import a return file, the status of the payments is updated in the **Payment status** field in the **Payment transfers** form. The new status is based on the relationship between the bank return occurrence codes in the return file and the return occurrence codes in Microsoft Dynamics AX. For more information, see [(BRA) Return occurrence codes (form)](https://technet.microsoft.com/library/jj730966\(v=ax.60\)). When you post the payments that the return file is imported for, only payments that have a status of **Approved** are posted to the payment journal.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment transfer**.
    
    –or–
    
    Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment transfers**.

2.  Click **Return file - vendor** or **Return file - customer** to open the **Load diskette with payments** form.

3.  In the **Method of payment** field, select the electronic method of payment to use to import the return file. For more information, see [(BRA) Set up an electronic method of payment](bra-set-up-an-electronic-method-of-payment.md).

4.  Click **OK** to open the **Configurable layout file** form.

5.  In the **File name** field, enter a path and a file name for the return file.

6.  Click **OK** to import the return file. The status of the payments is updated in the **Payment status** field in the **Payment transfers** form. The new status is based on the status of the payment in the return file.

7.  In the **Payment transfers** form, click **Post** to open the **Post payments** form.

8.  In the **New journal name** field, enter a journal name.

9.  Click **OK** to post the payments to the payment journal. The payments that are posted have a status of **Approved**.

## See also

[(BRA) Examples: Journals generated during the electronic payment return process](bra-examples-journals-generated-during-the-electronic-payment-return-process.md)

[(BRA) Set up an electronic payment](bra-set-up-an-electronic-payment.md)

  


