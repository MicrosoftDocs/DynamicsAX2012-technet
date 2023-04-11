---
title: Create and post advanced ledger entries (Public sector)
TOCTitle: Create and post advanced ledger entries (Public sector)
ms:assetid: 94f492f9-b129-4325-8dac-5622f6e7b97d
ms:mtpsurl: https://technet.microsoft.com/library/Hh208554(v=AX.60)
ms:contentKeyID: 36056316
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advanced ledger entry
audience: Application User
ms.search.region: Denmark, France
---

# Create and post advanced ledger entries (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you create advanced ledger entries, you must set up number sequences and General ledger posting definitions for advanced ledger entries. You must also set up workflows and budget control if you plan to use those features. For more information, see [Set up advanced ledger entries (Public sector)](set-up-advanced-ledger-entries-public-sector.md).

## Create and post advanced ledger entries

1.  Click **General ledger** \> **Common** \> **Advanced ledger entries**.

2.  On the **Advanced ledger entries** list page, click **Advanced ledger entry** on the **Action Pane** and do the following:
    
    1.  Verify the **Transaction number**.
    
    2.  Verify or enter a new **Accounting date**.
    
    3.  Enter or select **Transaction text** that identifies the purpose for the transaction. For more information, see [Journal descriptions (form)](https://technet.microsoft.com/library/aa587702\(v=ax.60\)).
    
    4.  Select a **Posting definition** that has been configured for the General ledger module. For more information, see [Posting definitions (form)](https://technet.microsoft.com/library/hh227607\(v=ax.60\)).
    
    5.  Verify the **Currency**, which is the company currency used to display the amounts. For more information, see [Currencies (form)](https://technet.microsoft.com/library/aa582902\(v=ax.60\)).
    
    6.  Select a **Reason code** and enter a **Reason comment**. For more information, see [Reasons (form)](https://technet.microsoft.com/library/hh209362\(v=ax.60\)).
    
    7.  To create a reversing advanced ledger entry, select the **Reversing entry** check box and enter a **Reversing date**.
        
        A reversing advanced ledger entry is created when the advanced ledger entry is posted. The reversing advanced ledger entry will have a new transaction number and a status of **Draft**. The reversing date will be used as the accounting date and the debit or credit amount on each line of the original entry will be reversed. The same posting definition will be used. The transaction text for the header and lines will contain the words “Reversing entry from,” the transaction number of the original advanced ledger entry, and the transaction text of the original advanced ledger entry.
    
    8.  Click **Continue** to open the **Advanced ledger entry** detail form.

3.  In the **Advanced ledger entry lines** area, click **Add line**.

4.  Enter project information. For information about projects, see [Project management and accounting](project-management-and-accounting.md).

5.  Enter the ledger account and the debit or credit amount.

6.  Click **Subledger journal** to preview the subledger journal for the line, or select **Subledger journal entries** from the **Action pane** to preview all the lines.

7.  Click **Post** \> **Advanced ledger entry**. When the document status changes to posted, you can click **Voucher** to view the voucher transactions.


> [!NOTE]
> <P>If workflows are enabled, additional controls are displayed at the top of the <STRONG>Advanced ledger entry</STRONG> form when the first line is saved. You can continue to enter additional lines, but after you click <STRONG>Submit</STRONG> and the advanced ledger entry is submitted to the workflow, you can no longer add or remove lines. After the workflow status changes to <STRONG>Approved</STRONG>, you can post the advanced ledger entry.</P>
> <P>With workflows enabled, a yellow information bar and a <STRONG>Submit</STRONG> button or an <STRONG>Actions</STRONG> menu appear at the top of the <STRONG>Advanced ledger entry</STRONG> form. If you are the originator of the advanced ledger entry, you might see a <STRONG>Submit</STRONG> button. If you are an approver of the advanced ledger entry, you might see an <STRONG>Actions</STRONG> menu with options to approve or reject the advanced ledger entry. For more information, see <A href="submit-a-document.md">Submit a document</A> and <A href="workflow-actions.md">Workflow actions</A>.</P>
> <P>Some buttons in the <STRONG>Advanced ledger entry</STRONG> form are not available when an advanced ledger entry has been submitted for workflow approval. When the advanced ledger entry is approved, the <STRONG>Post</STRONG> option becomes available. If you modify an approved advanced ledger entry, it must be resubmitted for approval.</P>



## See also

[About advanced ledger entry workflows (Public sector)](about-advanced-ledger-entry-workflows-public-sector.md)

[Workflow for Microsoft Dynamics AX](workflow-for-microsoft-dynamics-ax.md)

  


