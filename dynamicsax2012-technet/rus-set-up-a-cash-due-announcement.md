---
title: (RUS) Set up a cash due announcement
TOCTitle: (RUS) Set up a cash due announcement
ms:assetid: 5a73a01b-1e0d-4f30-af55-29342b9e889b
ms:mtpsurl: https://technet.microsoft.com/library/JJ665413(v=AX.60)
ms:contentKeyID: 49387501
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up a cash due announcement 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The cash due announcement report is the cash-in-hand acceptance by the bank. The Cash due announcement allows you to export the unified report (0402001.xlt) to the registered bank when updating the journal. To activate the cash due announcement function, select the **Use confirm status** checkbox in the **Bank parameters** form.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Set up a number sequence for a cash due announcement

1.  Click **Cash and bank management** \> **Setup** \> **Cash and bank management parameters**.

2.  Click the **Number sequence** tab.

3.  In the **Number sequence code** field, select the number sequence code for the **Reference** type **Cash due announcement**.

4.  Press CTRL+S or close the form.

## Set up a cash due announcement for a ledger account

1.  Click **Cash and bank management** \> **Setup** \> **Bank transaction types**.

2.  Click CTRL+N to create a new line.

3.  In the **Bank transaction type** field, enter the bank transaction type code.

4.  In the **Name** field, enter the description for the bank transaction type.

5.  In the **Ledger account** field, select the ledger account number for posting the bank transaction.

6.  Select the **Allow cash due announcement** check box to allow creation of a cash due announcement for bank transactions.

7.  Press CTRL+S or close the form.

## See also

[(RUS) Cash accounts (form)](https://technet.microsoft.com/library/jj665230\(v=ax.60\))

  


