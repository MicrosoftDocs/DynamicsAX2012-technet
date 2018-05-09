---
title: About project groups
TOCTitle: About project groups
ms:assetid: a144781b-de98-43ce-9bbb-4c889ed33cfb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh450757(v=AX.60)
ms:contentKeyID: 36966736
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About project groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can use project groups to specify the type of accounts that project transactions are posted to.

For hour, expense, item, and on-account transactions, you can choose to post transactions to either Profit and loss or Balance accounts. In certain cases, you can also choose not to post hour transactions.

Every project must belong to a project group. Therefore, you must set up at least one project group when you set up **Project management and accounting**.

A project must be assigned to a project group that was created for that type of project. If you move a project from one project group to another, and the new project group was created for a different project type, the project is automatically changed to the new type.

After you set up a project group in the **Project groups** form and select its project type, you can specify several default settings for it. These settings include transaction line properties, on-account invoice posting, journalizing, and cost and revenue accounts.

  - **Invoicing** – Determine whether on-account invoices for Time and material and Fixed-price projects are posted to revenue accounts or work-in-process (WIP) accounts.

  - **Journalizing** – Indicate whether hour costs, expense costs, and item costs should be posted to Profit and loss accounts or Balance accounts, or not posted. When transactions are updated in the respective journals, the system performs a check to ensure that a ledger account is available, and that the account is the appropriate type.

  - **Cost accounts** and **Revenue accounts** – Specify whether a specific ledger account applies in every situation and to every project in this group. If more flexibility is required, you can set up ledger posting at the category level or project level.

After a project is assigned to a project group, the options that have been defined for ledger updates in the project groups cannot be changed.


> [!NOTE]
> <P>Instead of using the project group settings to specify the type of accounts that project transactions are posted to, you can post transactions according to rules that are defined for transaction categories. To do so, in the <STRONG>Project groups</STRONG> form, on the <STRONG>General</STRONG> FastTab, in the <STRONG>Search priority</STRONG> field, select <STRONG>Category</STRONG>. For more information about specifying accounts for a project category, see <A href="create-categories-and-category-groups-for-projects.md">Create categories and category groups for projects</A>.</P>



## See also

[Create a project group](create-a-project-group.md)

[About changing the project group](about-changing-the-project-group.md)

[Change the project group](change-the-project-group.md)

[Project groups (form)](https://technet.microsoft.com/en-us/library/aa590435\(v=ax.60\))

[About project category groups](about-project-category-groups.md)

[Project categories (form)](https://technet.microsoft.com/en-us/library/aa582118\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

