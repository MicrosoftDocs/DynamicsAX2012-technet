---
title: (NOR) Export an eInvoice for a customer
TOCTitle: (NOR) Export an eInvoice for a customer
ms:assetid: 8ca7037c-afa2-4800-a260-ef421df55a23
ms:mtpsurl: https://technet.microsoft.com/library/Gg242872(v=AX.60)
ms:contentKeyID: 36058482
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Norway
---

# (NOR) Export an eInvoice for a customer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order for the customer for whom the eInvoice service is approved, and post the sales invoice.

3.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

4.  Create a payment journal, and then click the **Lines** button to open the **Journal voucher** form.

5.  In the **Account** field, select the customer account to export the eInvoice for.

6.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

7.  In the **Settle open transactions** form, mark the invoices that are to be exported, and close the form.

8.  Click **Payment proposal** \> **Create payment proposal** and create a payment proposal for the journal.

9.  Click **OK** to close the form.

10. Click **Functions** \> **Generate payments** to open the **Generate payments** form.

11. Select the **Export format** option. Select the **BBS eFaktura, AG, DirRem (NO)** export format for the eInvoice in the **Export format** field.

12. Click the **Dialog** to open the **BBS export (AvtaleGiro, DirRem, eFaktura)** form. Select the file in the **File name** field to export the eInvoice.

13. Click **OK** to export the eInvoice to the file.

  


