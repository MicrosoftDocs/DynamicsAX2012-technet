---
title: (JPN) Create, confirm, reopen, and print a consolidated vendor invoice
TOCTitle: (JPN) Create, confirm, reopen, and print a consolidated vendor invoice
ms:assetid: 4e1feda3-0e27-41b8-802c-ecd587a1bfe4
ms:mtpsurl: https://technet.microsoft.com/library/JJ711045(v=AX.60)
ms:contentKeyID: 49386457
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Japan
---

# (JPN) Create, confirm, reopen, and print a consolidated vendor invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Consolidated invoice** form to create, confirm, reopen, and print a consolidated invoice for a vendor. Before you can create a consolidated invoice, you must create a purchase order that has an updated consolidation date. You can create a consolidated invoice for a vendor based on the actual consolidation date. The actual consolidation date is the date on which the consolidated invoice is processed, and you cannot change this date. This date must be later than the date of the most recent consolidated invoice for that vendor. For more information, see [(JPN) Mark purchase invoices for consolidation and calculate due dates](jpn-mark-purchase-invoices-for-consolidation-and-calculate-due-dates.md).

When you create a new consolidated invoice, the status is updated to **Unconfirmed**. Confirm the new consolidated invoice before you settle it. Because a vendor can have several open consolidated invoices, you should confirm their consolidated invoices for the previous period before you create new consolidated invoices. Confirm consolidated invoices in chronological order, but reopen the confirmations in reverse chronological order. You can also create and settle two or more consolidated invoices for a vendor on the same day.

1.  Click **Accounts payable** \> **Periodic** \> **Consolidated invoice**.

2.  Click **New** \> **Consolidated invoice**.

3.  Enter the selection criteria, and then click **OK**. The open transactions are marked for consolidation, and the transactions that are not yet consolidated are displayed with a status of **Unconfirmed**.

4.  Select a consolidated invoice, and then click **Confirm**. After confirmation, the sum of the consolidated invoices is displayed in the **Invoice amount during consolidation period** field. The status is updated to **Confirmed**.
    
    –or–
    
    Select a confirmed consolidated invoice, and then click **Reopen**. After you have reopened the invoice, the status is updated to **Confirmed**.
    

    > [!NOTE]
    > <P>You can modify or delete a consolidated invoice only when its status is <STRONG>Unconfirmed</STRONG>.</P>

    
    You can view the amounts for the consolidated invoice in the **Previous invoice amount**, **Previously paid amount**, **Adjustment amount**, **Outstanding amount**, **Invoice amount**, and **Total invoice amount** fields.

5.  Click **Print** \> **Consolidated invoice** to generate the monthly consolidated invoice report.
    

    > [!NOTE]
    > <P>You cannot delete a consolidated invoice after it has been confirmed or settled.</P>



6.  Close the forms.

## See also

[(JPN) Consolidated invoice (form)](https://technet.microsoft.com/library/jj711205\(v=ax.60\))

  


