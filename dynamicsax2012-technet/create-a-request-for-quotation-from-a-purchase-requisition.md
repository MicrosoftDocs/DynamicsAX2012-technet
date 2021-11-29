---
title: Create a request for quotation from a purchase requisition
TOCTitle: Create a request for quotation from a purchase requisition
ms:assetid: 9691cc43-d2a7-481a-adc7-7623a8342c5d
ms:mtpsurl: https://technet.microsoft.com/library/Gg232234(v=AX.60)
ms:contentKeyID: 36058635
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- quotes
- Classes.PurchRFQTableMap2LineParametersForm
- Forms.PurchReqCopyRFQ
- Forms.PurchRFQCaseLineCopy
- RFQ
- Forms.PurchCreateRFQCase
- procurement
- purchase requisition
- request for quotation
- purchase requisitions
- requests for quotations
- Forms.PurchRFQCaseTableListPage
- Forms.PurchCopying
- Forms.PurchReqTableListPage
- Forms.PurchRFQReplyFields
- Menu_Items.Display.PurchRFQEditLines
- quote
- request for quotations
- requests for quotation
- RFQs
audience: Application User
ms.search.region: Global
---

# Create a request for quotation from a purchase requisition 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create an RFQ from a purchase requisition only when the status of the purchase requisition is **Pending approval**, because the lines in the purchase requisition are updated automatically as you accept lines from RFQ replies (bids) from vendors.

You cannot complete, reject, approve, or perform any other actions on the purchase requisition while the RFQ is in progress.

When you accept an RFQ reply that has a type of **Purchase requisition**, the RFQ reply lines update the purchase requisition lines with the following information:

  - Unit price

  - Discount percentage

  - Discount amount

  - Purchase charges

  - Line charges

  - Vendor

  - External number

  - External description

Use this procedure to create a request for quotation (RFQ) from a purchase requisition or a project purchase requisition.

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase requisitions** \> **All purchase requisitions**.
    
    –or–
    
    Click Click **Project management and accounting** \> **Common** \> **Item tasks** \> **Project purchase requisitions**.

2.  Select the purchase requisition to copy to an RFQ.

3.  On the **Action Pane**, on the **Purchase requisition** tab, in the **Actions** group, click **Create request for quotation**.

4.  In the **Select the lines to copy to the request for quotation** form, select the check boxes next to the lines to copy to the RFQ.

5.  Click **OK** to create an RFQ that has a type of **Purchase requisition**. The information from the selected purchase requisition lines is copied to the RFQ. All vendors from the purchase requisition become vendors for the RFQ.
    
    The status of the purchase requisition changes to **Pending request for quotation**. You cannot perform any action on the purchase requisition until the RFQ process is completed.

## See also

[About requests for quotation](about-requests-for-quotation.md)

  


