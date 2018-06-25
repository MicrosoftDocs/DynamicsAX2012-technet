---
title: (IND) Set up tax ledger posting groups
TOCTitle: (IND) Set up tax ledger posting groups
ms:assetid: 493b22e1-45ff-4013-a5d1-fe6eaddb158a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664676(v=AX.60)
ms:contentKeyID: 49385749
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ledger posting group
- (IND)
- india
- posting group
- tax ledger posting group
---

# (IND) Set up tax ledger posting groups [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create and manage the tax groups that determine the sales tax and duty postings for indirect tax codes in India. The settings that you select for a tax group determine how the taxes in the tax group are posted to ledger accounts.

To track indirect taxes by incentive scheme, create a tax ledger posting group for each incentive scheme.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **India** \> **Tax ledger posting groups**.

2.  In the **Tax ledger posting groups** form, in the left pane, select a ledger posting group to modify, or click **New**.

3.  In the **Ledger posting group** field, enter a unique name for the ledger posting group.

4.  In the **Tax type** field, select the type of indirect tax for the group.

5.  Select an account code for the ledger posting. The following options are available:
    
      - **Table** – Define the ledger accounts for the registration number that is specified in the **Registration number** field.
    
      - **All** – Define the ledger accounts for all tax registration numbers.

6.  Enter the registration number and a brief description of the tax type.

7.  On the **Ledger accounts** FastTab, in the **Ledger accounts** section, select the type of ledger account that the tax amount for the tax component is posted to. The ledger accounts that you can select depend on the value that you selected in the **Tax type** field. For example, if you selected the **Customs** tax type, you can set up tax components to post to the **AA receivable account** and **DFIA receivable account** ledger accounts.

8.  In the **Tax component** field, select the tax component to define the posting account for.
    

    > [!NOTE]
    > <P>If you do not set up the tax component ledger accounts for the AA receivable account, validation results for posting accounts are displayed when you post a voucher for tax transactions in the Advance Authorization scheme.</P>



## See also

[(IND) Tax components (form)](https://technet.microsoft.com/en-us/library/jj664734\(v=ax.60\))

[(IND) Tax ledger posting groups (form)](https://technet.microsoft.com/en-us/library/jj664546\(v=ax.60\))

[(IND) Create tax ledger posting groups and attach an STC number](ind-create-tax-ledger-posting-groups-and-attach-an-stc-number.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

