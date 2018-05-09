---
title: Set up ledger posting groups for sales tax
TOCTitle: Set up ledger posting groups for sales tax
ms:assetid: d3235eac-961a-4412-9b28-75eae8105278
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551052(v=AX.60)
ms:contentKeyID: 36059508
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up ledger posting groups for sales tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When transactions are posted, sales taxes are calculated and posted automatically to main accounts. The default ledger posting groups are defined when you attach a ledger posting group to each sales tax code, or to each sales tax jurisdiction, if the organization operates in the United States and uses this functionality.

Set up the sales tax ledger posting groups to fit the needs of the organization. You can set up individual ledger posting groups for each sales tax code. You can use one ledger posting group for all sales tax codes or assign multiple ledger posting groups to the sales tax codes.


> [!NOTE]
> <P>Before you can set up the ledger posting groups, the main accounts that are used for sales taxes in the <STRONG>Main accounts - chart of accounts: %1</STRONG> form must be created.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Ledger posting groups**.

2.  Click **New** to create a line for the ledger posting group.

3.  In the **Ledger posting group** field, enter a unique code for the ledger posting group.

4.  In the **Description** field, enter the name or description of the ledger posting group.

5.  On the **General** tab, select the ledger accounts that are used to record various types of sales taxes.

Depending on whether the **Apply U.S. taxation rules** check box is selected in the **Sales tax** area of the **General ledger parameters** form, various fields for ledger posting groups are available. For more information about these fields, see [Ledger posting groups (form)](https://technet.microsoft.com/en-us/library/aa598801\(v=ax.60\)).

If the **Apply U.S. taxation rules** check box is selected, the following fields are available:

  - **Sales tax payable**

  - **Use tax payable**

  - **Settlement account**

If the **Apply U.S. taxation rules** check box is not selected, the following fields are available:

  - **Sales tax payable**

  - **Sales tax receivable**

  - **Use tax expense**

  - **Use tax payable**

  - **Settlement account**

## See also

[Ledger posting groups (form)](https://technet.microsoft.com/en-us/library/aa598801\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

