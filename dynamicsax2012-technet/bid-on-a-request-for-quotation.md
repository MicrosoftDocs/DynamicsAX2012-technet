---
title: Bid on a request for quotation
TOCTitle: Bid on a request for quotation
ms:assetid: 26733b99-b082-421a-bb85-8255da608a81
ms:mtpsurl: https://technet.microsoft.com/library/Dn518242(v=AX.60)
ms:contentKeyID: 62200021
author: Khairunj
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendors
- replies
- RFQ
- request for quotation
- reply
- PurchRFQVendorClose
- PurchRFQVendorOpen
- request for quotations
- bid
- bids
audience: Application User
ms.search.region: Global
---

# Bid on a request for quotation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for <STRONG>Public sector</STRONG> in Microsoft Dynamics AX 2012 R3.</P>



As a public sector vendor, you can use the Vendor portal section of Enterprise Portal for Microsoft Dynamics AX to view published requests for quotation (RFQ) that you might want to bid on.


> [!NOTE]
> <P>To use the following steps, you must have the Vendor (External) – Public Sector role, and the <STRONG>Public Sector</STRONG> configuration key must be enabled. For information about the basic functionality for the Vendor portal, see <A href="view-and-reply-to-a-request-for-quotation.md">View and reply to a request for quotation</A>.</P>



As a public sector vendor, you can view:

  - Open RFQs that have been sent to you and can be bid on.

  - Open RFQs that have not been sent to you but you can request to bid on.

  - Closed RFQs, regardless of which vendor has won the bid.

## View and reply to (bid on) an RFQ

Use this procedure to view bid on an RFQ.

1.  In the Vendor portal, do one of the following:
    
      - To view only RFQs that have been sent to you and are currently open, click **Requests for quotations** on the Quick Launch, under **My documents**.
    
      - To view all currently open RFQs, click **Open requests for quotations**.
    
      - To view published RFQs and their bids, either already declined or accepted, click **Closed requests for quotations**.
    
    On these pages, you can view detailed information, including line details and any amendments and attachments to the RFQs.

2.  Sort and filter the list to display RFQs, such as by requested delivery date, expiration date and time, document title, or currency. You can also enter the identification number in the filter to locate a specific RFQ. New RFQs have a status of **New** **: Action required**.

3.  In the **Requests for quotations** form:
    
      - To see more information about the RFQ line, on the **Lines** FastTab, select a line, and then click the **Details** button.
    
      - If there is a document attached to the RFQ, click the icon in the document field to open the attachment.
    
      - If one or more questionnaires are attached to the RFQ, they appear on the **Questionnaire** FastTab. You can complete a questionnaire only when you have decided to bid on the RFQ.
    
      - If a requester has changed or updated an RFQ, you can view those changes on the **Amendments** FastTab. The requester may also decide to send you an alert when amending an RFQ.

4.  If you do not want to bid on any of the products in the RFQ, on the **Requests for quotations** page, on the **Action Pane**, click **Decline**. The status of the RFQ becomes **Declined** **: No action required**.

5.  If you want to bid on any of the products in the RFQ, do the following:
    
    1.  On the **Requests for quotations** page, on the **Action Pane**, click **Reply**.
    
    2.  On the **Reply to request for quotation** page, on the **Action Pane**, click **Reset bid data** to transfer the information in the associated RFQ to this **Reply to request for quotation** page. You can modify the copied information in the new bid.
    
    3.  Verify the dates and other information in the heading.
    
    4.  Delete the lines that you do not want to bid on.
    
    5.  Update the unit price, delivery date, lead time, terms of delivery, discounts, and charges for each line in your bid.
    
    6.  If the RFQ allows for alternate lines, you can add them by selecting a line and then clicking **Add alternate**. Only one alternate per category line is allowed.
    
    7.  If one or more questionnaires are attached to the RFQ, click **Complete questionnaire**, and answer the questions for each questionnaire. All questionnaires must be completed before you send the RFQ bid.
    
    8.  To attach a document to the bid, on the **Lines** FastTab, click **Attachments**. Upload the attachment, and then click **OK**.
    
    9.  Click **Send**. The status of the RFQ changes to **Submitted** **: No action required**.

The customer is notified that you have bid on the RFQ.


> [!NOTE]
> <P>If an RFQ is sealed, only you, the bidding vendor, can view the unit price and net amount on bid lines; others can only see this information when the RFQ is unsealed, after the RFQ expiration date and time. Note that sealed bid functionality is only available in the Vendor portal, not Sites Services for Microsoft Dynamics ERP.</P>



You can view the status of your bid on the **Requests for quotations** list page as the customer processes the bid:

  - If the customer accepts all lines on your bid, the RFQ status is **Approved** **: No action required**.

  - If the customer declines all lines in your bid, the status is **Rejected** **: No action required**.

  - If at least one bid line has a status of **New**, the RFQ status is **Multiple** **: Action required**.

  - If the customer accepts at least one bid line, and there are no new lines, the RFQ status is **Multiple** **: No action required**.

  - If the customer requires more information from you about your bid, the status of the RFQ reverts to **New** **: Action required**.

  - If the expiration date and time have passed, the status of the RFQ is **Expired**.

## Recall a bid

Use this procedure to recall a bid. You can do this if the RFQ has not expired and if your bid has not already been accepted or rejected.

1.  In the Vendor portal, click **Requests for quotations** on the Quick Launch, under **My documents**.

2.  On the **Action Pane**, click **Recall**.

3.  In the confirmation dialog box, click **Yes**.

  


