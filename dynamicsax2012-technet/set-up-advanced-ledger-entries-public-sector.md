---
title: Set up advanced ledger entries (Public sector)
TOCTitle: Set up advanced ledger entries (Public sector)
ms:assetid: a2007ba7-3a18-428f-9c61-afdff0ea5ee6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208561(v=AX.60)
ms:contentKeyID: 36056330
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advanced ledger entry
---

# Set up advanced ledger entries (Public sector) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If your organization is in the public sector, you can use advanced ledger entries to create, adjust, and reverse ledger entries. For example, you could use advanced ledger entries to reclassify expenditures if invoices had been mistakenly posted to the wrong account or project.

When you use advanced ledger entries, you must use General ledger posting definitions. Posting definitions can be set up to reclassify expenditures from one fund to another. On the **Advanced ledger entry** form, you can identify project information, use workflow approvals, perform budget checks, and preview the ledger entries before they are posted to the ledger.

## Set up advanced ledger entries

1.  Required: Verify that the **Advanced ledger entry** **License configuration** key is enabled. (**System administration** \> **Setup** \> **Licensing** \> **License configuration** \> **General ledger** \> **Advanced ledger entry**.)

2.  Required: In the **Number sequences** area of the **General ledger parameters** form, set up the **Advanced ledger entry** and **Advanced ledger entry voucher** number sequences. For more information, see [Number sequence overview](number-sequence-overview.md).

3.  Required: Set up posting definitions for the General ledger module on the **Posting definitions** form. For more information, see [About posting definitions](about-posting-definitions.md) and [Set up posting definitions](set-up-posting-definitions.md).

4.  Optional: Set up projects. For information, see [Project management and accounting](project-management-and-accounting.md) and [Create a project](create-a-project.md).

5.  Optional: Set up advanced ledger entry workflows. For more information, see [About advanced ledger entry workflows (Public sector)](about-advanced-ledger-entry-workflows-public-sector.md), [Set up General ledger workflows](set-up-general-ledger-workflows.md), and [Workflow for Microsoft Dynamics AX](workflow-for-microsoft-dynamics-ax.md).

6.  Optional: Set up budget control following the procedures outlined in [Set up budget control](set-up-budget-control.md).
    
    In the **Select source documents** area of the **Budget control configuration** form, select the **Advanced ledger entries** check box to enable budget control for advanced ledger entries. You can also select the **Enable budget control for line item on entry** check box to enable budget checks when an advanced ledger entry line is saved.

7.  Optional: In the **Ledger** area of the **General ledger parameters** form, under **Project**, you can select the **Allow the financial dimensions to be edited on the advanced ledger entry form** check box.
    

    > [!NOTE]
    > <P>With this check box selected, you can change the financial dimensions for a project in the <STRONG>Ledger account</STRONG> field in an advanced ledger entry line. If this check box is not selected, you can change the financial dimensions in the <STRONG>Ledger account</STRONG> field as long as the financial dimensions are not the default financial dimensions for a project.</P>



8.  Optional: In the **Batch transfer rules** area of **General ledger parameters** form, you can set up a batch transfer rule for advanced ledger entries.

## See also

[Create and post advanced ledger entries (Public sector)](create-and-post-advanced-ledger-entries-public-sector.md)

[Advanced ledger entry (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208579\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

