---
title: (THA, SAU, GBR, IRL) Set up a ledger posting group and attach it to a withholding tax code
TOCTitle: (THA, SAU, GBR, IRL) Set up a ledger posting group and attach it to a withholding tax code
ms:assetid: 78274644-4b44-4c9d-aac5-c5cf6138a268
ms:mtpsurl: https://technet.microsoft.com/library/Hh209253(v=AX.60)
ms:contentKeyID: 36058221
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Thailand
- withholding tax
- ledger posting group
audience: Application User
ms.search.region: Ireland, Saudi Arabia,Thailand, United Kingdom
---

# (THA, SAU, GBR, IRL) Set up a ledger posting group and attach it to a withholding tax code 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create a ledger posting group, and then attach it to one or more withholding tax codes.

1.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Ledger posting groups**.

2.  Create a new ledger posting group.

3.  In the **Ledger posting group** field, enter a code to identify the group.

4.  In the **Description** field, enter a description for the group.

5.  In the **Withholding tax** field, select a ledger account to post withholding tax that is calculated for a purchase. You must select an account with a **Posting type** of **Withholding tax**.

6.  In the **Withholding tax offset** field, select an offset type ledger account to post the withholding tax that is deducted from a customer’s purchase or sales order. You must select an account with a **Posting type** of **Withholding tax**.

7.  In the **Settlement account** field, select a ledger account to post the withholding tax settlement amount.

8.  Close the form.

9.  Click **General ledger** \> **Setup** \> **Withholding tax** \> **Withholding tax codes**.

10. Select the withholding tax code that you want to attach a ledger posting group to, and then click the **General** FastTab.

11. In the **Ledger posting group** field, select the ledger posting group for the withholding tax code.

12. Close the form.

## See also

[(THA, SAU, GBR, IRL) Withholding tax ledger posting groups (form)](https://technet.microsoft.com/library/hh208625\(v=ax.60\))

  


