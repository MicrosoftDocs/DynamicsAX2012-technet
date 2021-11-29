---
title: (IND) Process purchase orders at year end
TOCTitle: (IND) Process purchase orders at year end
ms:assetid: ad13bc32-e4b1-497e-97bf-3ce2dcf52164
ms:mtpsurl: https://technet.microsoft.com/library/JJ664767(v=AX.60)
ms:contentKeyID: 49386106
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Process
- purchase orders
- (IND)
- India
audience: Application User
ms.search.region: India
---

# (IND) Process purchase orders at year end 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

If you record encumbrances for purchase orders in the general ledger, including purchase orders for projects, you can generate closing entries to the general ledger and against budget reservations at the end of each fiscal year. At the start of the new fiscal year, you can create opening entries to correctly record the encumbrances and budget reservations. These entries help make sure that the reservations for purchase order encumbrances are correctly recorded on the year-end financial statements and in budget control.


> [!NOTE]
> <P>For projects, the account that distributions are assigned to in the new fiscal year is the account that is defined in the <STRONG>Purchase order year-end process</STRONG> form in General ledger. It is not the account that is defined in the <STRONG>Ledger posting setup</STRONG> form in Project management and accounting.</P>



In the case of a partially invoiced purchase order, only the amount that has not been invoiced is closed and then reopened in the next fiscal year.

Closing purchase order encumbrances is a separate process from closing a fiscal year, and is usually performed before a fiscal year is closed. For information about closing a fiscal year, see [Fiscal year closing checklist](fiscal-year-closing-checklist.md).


> [!NOTE]
> <P>Year-end transactions are posted for open purchase orders based on the ledger entries that are displayed in the <STRONG>Subledger journal</STRONG> form for the purchase order lines. The withholding tax, Tax collected at source (TCS) and Tax deducted at source (TDS), ledger entries are not considered during the purchase order year end closing entries or the purchase order year end opening entries.</P>


  


