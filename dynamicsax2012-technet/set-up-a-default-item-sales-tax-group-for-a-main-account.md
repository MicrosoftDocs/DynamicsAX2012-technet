---
title: Set up a default item sales tax group for a main account
TOCTitle: Set up a default item sales tax group for a main account
ms:assetid: b0552b6b-5391-417d-bb85-0339c6efac05
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa498640(v=AX.60)
ms:contentKeyID: 44081027
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up a default item sales tax group for a main account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To make sure that sales tax is calculated on all journal transactions that are posted to main accounts, you can set up a default item sales tax group for all main accounts. You can also set up default item sales tax groups for specific main accounts. This setting overrides the default item sales tax group that is set up for all main accounts.


> [!NOTE]
> <P>In sales journals, purchase journals, and other journals where you enter an item number, the item sales tax group that is attached to the item is displayed automatically on the journal lines. Before you post a transaction, you can change the default item sale tax group that is displayed on a journal line.</P>



## Select a default item sales tax group for all main accounts

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Sales tax**.

3.  In the **Item sales tax group** field, select the default item sales tax group.
    
    The item sales tax group that you select is entered automatically on journal lines when the lines are created. However, if you specify a different default item sales tax group for a specific main account, that setting overrides the default item sales tax group that is selected in the **General ledger parameters** form. The item sales tax group for the specific account is then displayed on the line. You can change the item sales tax group on each line, if you have to.

## Set up a default item sales tax group for a specific main account

1.  Click **General ledger** \> **Setup** \> **Chart of accounts** \> **Chart of accounts**.

2.  Select a chart of accounts.

3.  On the **Main accounts** FastTab, select a main account, and then click **Edit**.

4.  In the **Main accounts - chart of accounts: %1** form, in the **Select the level of main account to display** field, select **Companies**.

5.  In the **Companies** field, select a legal entity. If this field is blank, click the **Add** icon, and then double-click a legal entity.

6.  On the **Setup** FastTab, in the **Item sales tax group** field, select the default item sales tax group.
    

    > [!NOTE]
    > <P>If you select the <STRONG>Exempt</STRONG> check box for the selected main account, the default item sales tax group is not entered automatically on journal lines.</P>


  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

