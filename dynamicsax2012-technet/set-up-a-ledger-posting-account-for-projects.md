---
title: Set up a ledger posting account for projects
TOCTitle: Set up a ledger posting account for projects
ms:assetid: 34f7545b-edcb-4285-bddb-c7c037c126a5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh450754(v=AX.60)
ms:contentKeyID: 36966712
ms.date: 10/06/2014
mtps_version: v=AX.60
f1_keywords:
- project
- projects
- ledger accounts
- ledger posting
- ledger
- post project
---

# Set up a ledger posting account for projects 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can specify the ledger accounts to which to post each type of project transaction in Microsoft Dynamics AX. When you set up a posting account, you can also do the following:

  - Create posting rules that apply to individual projects, project groups, or all projects.

  - Specify both a funding source and a category for transaction lines that you create for an individual project or a project group.

  - In Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2, assign a sales tax group to a main account. This process helps you to track transactions that are subject to a specific sales tax rate, and then report the total amount of transactions for the sales tax rate to a tax authority. For more information about how to assign a sales tax group to a main account for projects, see [Ledger posting setup (form)](https://technet.microsoft.com/en-us/library/aa599270\(v=ax.60\)).

Complete the following procedure to set up a posting account:

1.  Click **Project management and accounting** \> **Setup** \> **Posting** \> **Ledger posting setup**.

2.  In the **Ledger posting setup** form, on the **Cost accounts** or **Revenue accounts** tab, in the **Select** group, select the type of cost price account or sales price account that you want to set up. Then click **Add**.

3.  In the first **Valid for** field, specify whether the line that you are creating applies to an individual project, a project group, or all projects.
    
      - If the line applies to an individual project, select **Table**.
    
      - If the line applies to a project group, select **Group**.
    
      - If the line applies to all projects, select **All**.

4.  If you selected **Table** or **Group** in step 3, in the **Project relation** field, select the project ID or project group ID that this line applies to.

5.  Optional: If you selected **Table** or **Group** in step 3, in the **Funding source** field, select the funding source that will be invoiced for the cost transactions that are identified by this line.

6.  In the second **Valid for** field, specify whether the line that you are creating applies to an individual category, a category group, or all categories.
    
      - If the line applies to an individual project, select **Table**.
    
      - If the line applies to a project group, select **Group**.
    
      - If the line applies to all projects, select **All**.

7.  If you selected **Table** or **Group** in step 6, in the **Project relation** field, select the category ID or category group ID that this line applies to.

8.  Optional: In the **Sales tax group** field, select the applicable sales tax group for the transactions that are posted to the selected main account. By using this option, you can track sales amounts by sales tax rate, and then report the taxable sales to the tax authorities.

9.  In the **Main account** field, select the account to which transactions are posted for the combination of project, category, and sales tax group that you selected.

## See also

[Ledger posting setup (form)](https://technet.microsoft.com/en-us/library/aa599270\(v=ax.60\))

[Ledger posting groups (form)](https://technet.microsoft.com/en-us/library/aa598801\(v=ax.60\))

[Set up ledger posting groups for sales tax](set-up-ledger-posting-groups-for-sales-tax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

