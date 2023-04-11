---
title: Set up reason codes for financial modules
TOCTitle: Set up reason codes for financial modules
ms:assetid: 8ab7ba27-88fe-4e4b-84b6-e111afec6fb5
ms:mtpsurl: https://technet.microsoft.com/library/Gg242861(v=AX.60)
ms:contentKeyID: 36058468
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reason codes
- accounts payable reasons
- accounts receivable reasons
- financial reasons
audience: Application User
ms.search.region: Global
---

# Set up reason codes for financial modules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A reason code is a code that users can select to record the reason for a change or transaction, such as a write-down adjustment or payment reversal. You can use the **Financial reasons** form in Organization administration to create reason codes for a variety of financial modules, or you can alternatively open a reasons form from a specific module to set up reason codes for only that module. For more information, see [Reasons (form)](https://technet.microsoft.com/library/hh209362\(v=ax.60\)).

You can also specify whether reason codes are required for a module. You specify reason code requirements in the parameters form for most modules.

## Organization administration

1.  Click **Organization administration** \> **Setup** \> **Financial reasons**.

2.  Click **New** to create a reason code.

3.  In the **Reason code** field, enter a code for the reason.

4.  In the **Default comment** field, enter a description for the code.

5.  Select the types of accounts that the reason code can be used with.

6.  Repeat steps 2 through 5 to create additional reason codes.

## Fixed assets

1.  Click **Fixed assets** \> **Setup** \> **Asset reasons**.

2.  Click **New** to create a reason code.

3.  In the **Reason code** field, enter a code for the reason.

4.  In the **Default comment** field, enter a description for the code.

5.  Click **Close**.

6.  Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**.

7.  Click **Fixed assets**. On the **Reason codes** FastTab, specify options for reason codes:
    
      - To require that users enter a reason for changes to the service life, depreciation periods, expected scrap value, or sales value for a fixed asset, select the **Require reasons for asset changes** check box.
    
      - To require that users enter a reason for a specific fixed asset transaction that is entered in a journal, select the transaction types and then click the arrow buttons to move the transaction types from the **Not required** list to the **Required** list.

## Accounts payable

1.  Click **Accounts payable** \> **Setup** \> **Vendors** \> **Vendor reasons**.

2.  Click **New** to create a reason code.

3.  In the **Reason code** field, enter a code for the reason.

4.  In the **Default comment** field, enter a description for the code.

## Accounts receivable

1.  Click **Accounts receivable** \> **Setup** \> **Customers** \> **Customer reasons**.

2.  Click **New** to create a reason code.

3.  In the **Reason code** field, enter a code for the reason.

4.  In the **Default comment** field, enter a description for the code.

5.  Click **Close**.

6.  To require reasons for changes in Accounts receivable, select the appropriate check boxes on the **Reason code requirements** FastTab in the **General** area of the **Accounts receivable parameters** form. (Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.)

## General ledger

1.  Click **General ledger** \> **Setup** \> **Ledger reasons**.

2.  Click **New** to create a reason code.

3.  In the **Reason code** field, enter a code for the reason.

4.  In the **Default comment** field, enter a description for the code.

## Cash and bank management

1.  Click **Cash and bank management** \> **Setup** \> **Bank reasons**.

2.  Click **New** to create a reason code.

3.  In the **Reason code** field, enter a code for the reason.

4.  In the **Default comment** field, enter a description for the code.

5.  Click **Close**.

6.  To require reasons for changes in Cash and bank management, select the appropriate reason code requirements check boxes in the **General** area of the **Cash and bank management parameters** form. (Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.)

## See also

[About financial reason codes](about-financial-reason-codes.md)

[Reasons (form)](https://technet.microsoft.com/library/hh209362\(v=ax.60\))

  


