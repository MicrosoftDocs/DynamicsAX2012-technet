---
title: (RUS) About product receipt corrections
TOCTitle: (RUS) About product receipt corrections
ms:assetid: bda4bee9-197b-4216-95ca-2070113ee02a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733278(v=AX.60)
ms:contentKeyID: 49685245
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (RUS)
- About product receipt corrections
---

# (RUS) About product receipt corrections 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can correct a product receipt that is already posted for a purchase order. The corrected product receipt contains information about the deviation from the original purchase order in terms of the quantity of items that were ordered. For example, you purchased 10 items from a vendor. When the items are delivered, you find that three of them are damaged. You can post a product receipt to reflect the correct number of items that you received, and the number of items that were damaged, or the deviation in the item quantity that was ordered. When you post a corrected product receipt, the original product receipt is canceled, and a new version of an M-4, M-7, TORG-1, TORG-2, or TORG-3 receipt statement report is created. The new version of the receipt statement report is created only if the corrected receipt contains a minimum of one line with a non-zero received quantity. You can also print the new version of the receipt statement report. You can retain the receipt statement document type and the number of the original product receipt for the corrected product receipt.

The batch number, serial number, inventory owner, and customs cargo declaration (GTD) number are collectively referred to as the tracking dimensions for the items. When you correct a product receipt, the tracking dimensions for the items in the original product receipt are applied to the corrected product receipt.

## See also

[(RUS) Post a product receipt for a purchase order](rus-post-a-product-receipt-for-a-purchase-order.md)

[(RUS) Correct a product receipt and print the receipt statement report](rus-correct-a-product-receipt-and-print-the-receipt-statement-report.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

