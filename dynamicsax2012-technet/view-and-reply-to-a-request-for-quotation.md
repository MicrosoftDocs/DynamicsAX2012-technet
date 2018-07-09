---
title: View and reply to a request for quotation
TOCTitle: View and reply to a request for quotation
ms:assetid: 2ca952d7-8748-48a5-8f70-025171e2fbad
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271486(v=AX.60)
ms:contentKeyID: 36384118
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- replies
- RFQ
- request for quotation
- PurchRFQreplyDecline
- PurchRFQVendItemDetail
- PurchRFQVendItemDetailEdit
- PurchRFQVendItemDetailView
- PurchRFQVendReplySend
- PurchRFQVendReplyTableEdit
- PurchRFQVendReplyTableListPage
- PurchRFQVendReplyTableView
- reply
- request for quotations
- bid
- bids
---

# View and reply to a request for quotation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

As a vendor, you receive requests for quotation (RFQ) from a customer.


> [!NOTE]
> <P>If you are a public sector vendor (the <STRONG>Public Sector</STRONG> configuration key is enabled, and the Vendor [External] – Public Sector role is enabled), see <A href="bid-on-a-request-for-quotation.md">Bid on a request for quotation</A>.</P>
> <P>If you are not a registered user of the Vendor portal section of Enterprise Portal for Microsoft Dynamics AX, you can see open and closed RFQs listed on a public version of the site. In order to bid on an RFQ, you can request to be added to the RFQ. You must register, be approved as a vendor, be approved as a vendor user, and provide contact information. For more information, see <A href="maintain-your-company-profile.md">Maintain your company profile</A>.</P>



After you register, you can view or respond to RFQs in the Vendor portal. You can also view the status of your replies to see whether your bid was accepted or rejected, or if the customer has requested additional information from you.

## View and reply to (bid on) an RFQ

Use this procedure to view and bid on an RFQ.

1.  In the Vendor portal, click **Requests for quotations** on the Quick Launch, under **My documents**.

2.  On the **Requests for quotations** list page, you can sort and filter the list to display RFQs by requested delivery date, expiration date/time, solicitation and bid type, document title, or currency. You can also enter the identification number in the filter to locate a specific RFQ. New RFQs have a status of **New: Action required**.

3.  On the **Requests for quotations** list page, you can reply or decline to reply to an RFQ. If you want to view all the lines in an RFQ before you decide, select the RFQ, and then click **View**. You can also click a request for quotation ID to view the RFQ details.

4.  To view more information about the RFQ line, on the **Lines** FastTab, select a line, and then click **Details**.

5.  If one or more questionnaires are attached to the RFQ, they appear on the **Questionnaire** FastTab. You can complete a questionnaire only when you have decided to bid on the RFQ.

6.  If there is a document attached to the RFQ, click the icon in the document field to open the attachment.

7.  If a requester has changed or updated an RFQ, you can view those changes on the **Amendments** FastTab. The requester may also decide to send you an alert when amending an RFQ.

8.  If you do not want to bid on any of the products in the RFQ, on the **Action Pane**, click **Decline** on the **Requests for quotations** page. The status of the RFQ is **Declined** **: No action required**.

9.  If you want to bid on any of the products in the RFQ, do the following:
    
    1.  On the **Requests for quotations** page, on the **Action Pane**, click **Reply**.
    
    2.  On the **Reply to request for quotation** page, on the **Action Pane**, click **Reset bid data** to transfer the heading and line information in the associated RFQ to the **Reply to request for quotation** page. You can modify the copied information in the new reply.
    
    3.  On the **Reply to request for quotation** page, verify the dates and other information in the heading, and then delete any lines that you do not want to bid on. Update the unit price, delivery date, lead time, terms of delivery, discounts, and charges for each line in your reply.
    
    4.  If the RFQ allows for alternate lines, you can add them by selecting a line and then clicking **Add alternate**. Only one alternate is allowed per category line.
    
    5.  If one or more questionnaires are attached to the RFQ, click **Complete questionnaire**, and then answer the questions for each questionnaire. All questionnaires must be completed before you send the RFQ bid.
    
    6.  To attach a document to the reply, on the **Lines** FastTab, click **Attachments**. Upload the attachment, and then click **OK**.
    
    7.  Click **Send**. The status of the RFQ changes to **Submitted** **: No action required**.

The customer is notified that you have replied to the RFQ.


> [!NOTE]
> <P>If you are submitting a sealed bid, the unit price and net amount on all the RFQ reply lines are masked or hidden to everyone except you, until the RFQ responses are unsealed after the RFQ expiration date and time.</P>



You can view the status of your bid on the **Requests for quotations** list page as the customer processes the bid:

  - If the customer accepts all lines on your bid, the RFQ status is **Approved** **: No action required**.

  - If the customer declines all lines in your bid, the status is **Rejected** **: No action required**.

  - If at least one bid line has a status of **New**, the RFQ status will be **Multiple** **: Action required**.

  - If the customer accepts at least one bid line, and there are no new lines, the RFQ status is **Multiple** **: No action required**.

  - If the customer requires more information from you about your bid, the status of the RFQ reverts to **New** **: Action required**.

  - If the expiration date and time have passed, the status of the RFQ is **Expired**.

## Recall a bid

Use this procedure to recall a bid. You can do this if the RFQ has not expired and if your bid has not already been accepted or rejected.

1.  In the Vendor portal, click **Requests for quotations** on the Quick Launch, under **My documents**.

2.  Click the request for quotation for the bid that you want to recall.

3.  On the **Action Pane**, click **Recall**.

4.  In the confirmation dialog box, click **Yes**.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

