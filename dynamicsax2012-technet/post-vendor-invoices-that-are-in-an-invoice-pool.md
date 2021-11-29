---
title: Post vendor invoices that are in an invoice pool
TOCTitle: Post vendor invoices that are in an invoice pool
ms:assetid: 95e2a149-79c0-495c-89ca-9c9a6de9f181
ms:mtpsurl: https://technet.microsoft.com/library/Aa498424(v=AX.60)
ms:contentKeyID: 36058625
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Post vendor invoices that are in an invoice pool 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these steps to transfer the invoices from the **Invoice pool excl. posting** form to the invoice journal, and then post the invoices.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Create a journal. For more information, see the first steps in [Create and validate journals and journal lines](create-and-validate-journals-and-journal-lines.md).

3.  Click **Lines**, and then click **Functions** \> **Invoice pool excl. posting**.

4.  Select the lines to transfer to the invoice journal and then click **Accept**. The lines are displayed in the **Journal voucher** form.

5.  On each line, enter or modify the following information that is required for posting:
    
      - **Date** – The date that appears on the posted invoice.
    
      - **Account** – The vendor account number.
    
      - **Invoice** – The vendor invoice number.
    
      - **Credit** or **Debit** – Enter the invoice amount. **Credit** is used for vendor purchases and **Debit** is used for credit notes.
    
      - **Offset account** – The offset account must have the same currency as the **Currency** field.
    
      - **Approved by** – The identifier of the user who approved the invoice line.

6.  Enter information in other fields as required.

7.  Click **Validate** \> **Validate** to verify that the lines are ready for posting.

8.  Click **Post** \> **Post** to post the journal lines.
    
    The posted lines can be settled in a payment journal.

## See also

[Enter vendor invoices in an invoice pool](enter-vendor-invoices-in-an-invoice-pool.md)

[Vendor invoice pool excluding posting details (form)](https://technet.microsoft.com/library/bb314782\(v=ax.60\))

  


