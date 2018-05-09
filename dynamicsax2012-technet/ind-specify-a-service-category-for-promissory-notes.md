---
title: (IND) Specify a service category for promissory notes
TOCTitle: (IND) Specify a service category for promissory notes
ms:assetid: db234d26-9558-445a-84b9-9b8c769fa296
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn344875(v=AX.60)
ms:contentKeyID: 56117707
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.LedgerJournalTransVendPromissoryNote
- Forms.LedgerJournalTable
---

# (IND) Specify a service category for promissory notes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012_

Use this procedure to specify the service category for promissory notes.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Draw promissory note journal**. Select or create a journal, and then click **Lines**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Redraw promissory note journal**. Select or create a journal, and then click **Lines**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Remittance journal**. Select or create a journal, and then click **Lines**.
    
    –or–
    
    Click **Accounts payable** \> **Journals** \> **Promissory notes** \> **Settle promissory note journal**. Select or create a journal, and then click **Lines**.

2.  On the **Overview** tab, enter the details about the promissory note. For more information, see [Draw a promissory note](draw-a-promissory-note.md), [Redraw a promissory note](redraw-a-promissory-note.md), [Remit a promissory note](remit-a-promissory-note.md), and [Settle a promissory note](settle-a-promissory-note.md).

3.  In the **Service category** field, select one of the following options to indicate the service category for the journal line:
    
      - **Inward** – Select this option when you purchase goods from a vendor.
    
      - **Inter unit or input** – Select this option either when you transfer goods between two units within your legal entity, or when you transfer goods from the legal entity to a subcontractor for additional processing. For example, you can select this option when the goods are manufactured in one unit and then transferred to the packing unit of your legal entity.
    
      - **Others** – Select this option for other service categories for which input tax is paid. The input tax amount for this category is posted to the expense account instead of the recoverable account or the interim recoverable account.

## See also

[Draw vendor payments through promissory notes](draw-vendor-payments-through-promissory-notes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

