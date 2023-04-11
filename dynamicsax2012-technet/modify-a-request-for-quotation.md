---
title: Modify a request for quotation
TOCTitle: Modify a request for quotation
ms:assetid: 77b0b7b8-4718-465c-9f25-ba5a60937b09
ms:mtpsurl: https://technet.microsoft.com/library/Gg212993(v=AX.60)
ms:contentKeyID: 36676393
author: tonyafehr
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- edit
- change
- RFQ
- procurement
- request for quotation
- requests for quotations
- PurchRFQCaseTable
- PurchRFQReplyTable
- Request for quote
- amendment
- quote
- request for quotations
- requests for quotation
- RFQs
- PurchRFQCaseTableListPage
- addenda
- amendments
- modifications
- modification
- edits
- changes
audience: Application User
ms.search.region: Global
---

# Modify a request for quotation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can add attachments to a request for quotation (RFQ), add or remove vendors, change RFQ line information, and amend and resend an RFQ that has already been sent to vendors.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3. It also includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



## Attach a document

Use this procedure to add one or more attachments to an RFQ that you have not sent to vendors yet. If the RFQ has been sent to vendors, see “Add or modify information in a sent RFQ” later in this topic.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select or open the RFQ you want to modify.

3.  On the **Action Pane**, click **Attachments**.

4.  On the Action strip, click **New**.

5.  Select the type of attachment that you want, and then select the item.

6.  Click **Close**.

## Add or modify information in a sent RFQ

Use this procedure to amend and resend requests for quotation (RFQ) that have already been sent to vendors.

Changes to RFQs and RFQ replies (bids) are limited by the lowest and highest statuses on an RFQ header. When you change the information on an RFQ line or an RFQ reply line, the change is automatically reflected in the status of the RFQ header or RFQ reply header.


> [!IMPORTANT]
> <P>In AX 2012 R3 CU8, if the <STRONG>Lock RFQs when they are sent</STRONG> check box is selected in the <STRONG>Procurement and sourcing parameters</STRONG> form, see “Amend an RFQ in AX 2012 R3 CU8” later in this topic.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select or open the RFQ you want to amend.

3.  On the **Action Pane**, click **Edit**.

4.  Modify the lines in the RFQ and/or header as needed.

5.  (Optional) To add an attachment, on the **Attachments** FastTab, click **Attachments**. Click **New**, select the type of attachment that you want, and then select the item. Click **Close**. Click **Add**, and then type a name and description of the attachment.
    

    > [!NOTE]
    > <P>Vendors that are not using the Vendor portal are unable to view attachments to the amendment.</P>



6.  To resend the amended RFQ, on the **Action Pane**, click **Send**.

## Amend an RFQ in AX 2012 R3 CU8

In AX 2012 R3 CU8, if the **Lock RFQs when they are sent** check box is selected in the **Procurement and sourcing parameters** form, use this procedure to amend RFQs that you want to resend or republish. If **Lock RFQs when they are sent** is not selected, you can follow the steps in “Add or modify information in a sent RFQ” earlier in this topic.


> [!NOTE]
> <P>This procedure uses a wizard and treats the RFQ as a whole. All lines on document are affected, and you can’t send specific lines to specific vendors.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select or open the RFQ you want to modify.

3.  On the **Action Pane**, in the **Amendment** group, click **Create**.

4.  Modify the lines in the RFQ or the header as needed.
    

    > [!IMPORTANT]
    > <P>You can add more line items to the RFQ. However, if there have already been bids on the RFQ, you first have to use the steps in this procedure to cancel the RFQ and return the bid, and then create a second amendment to add the line items.</P>



5.  (Optional) To add an attachment, on the **Attachments** FastTab, click **Attachments**. Select the row representing the current amendment, select the type of attachment that you want, and then select the item. Click **Close**. Type a name and description of the attachment.
    

    > [!NOTE]
    > <P>This attachment relates specifically to the amendment. The <STRONG>Attachments</STRONG> button on the <STRONG>Action Pane</STRONG> is still available but typically applies to the base RFQ.</P>



6.  To cancel your changes and revert the RFQ to its previous state, on the **Action Pane**, click **Cancel**.

7.  When you’re done with your changes, on the **Action Pane**, click **Finalize**.

8.  Follow the instructions in the **Finalize amendment (%1) - Case ID: %2, Document title: %3** wizard.
    
    This wizard finalizes the changes, invalidates any previous bids, and sends the amended RFQ to any invited vendors.
    

    > [!NOTE]
    > <UL>
    > <LI>
    > <P>Vendors that are not using the Vendor portal are unable to view attachments to the amendment.</P>
    > <LI>
    > <P>If the <STRONG>Public Sector</STRONG> configuration key is selected, any RFQ that was originally published on the Vendor portal will be published in its amended state, visible to all vendors who use the portal, and a notification email will be sent to vendors who are included on the RFQ. If the <STRONG>Public Sector</STRONG> configuration key is not selected, you have the choice of sending the email notification.</P>
    > <LI>
    > <P>You can create an email template. Click <STRONG>Organization administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>E-mail templates</STRONG>. For more information, see <A href="set-up-alert-email-templates-in-html.md">Set up alert email templates in HTML</A>.</P></LI></UL>



## Add a vendor to an RFQ

Use this procedure to add a vendor to an RFQ. You cannot add vendors to an RFQ if you have accepted or rejected bids for all lines in the RFQ. If you have rejected all the lines from the existing vendors, you must create a new RFQ to send to a new vendor.

If you add a vendor to an RFQ where the lowest status is **Received** and the highest status is **Accepted**, the lowest status on the header changes to **Created**.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Use the filter options to find the RFQ that you want to modify, and then open it.

3.  In the **Request for quotation details** form, on the **Action Pane**, on the **Quotation** tab, click **Edit**.

4.  On the **Vendor** FastTab, click **Add**.

5.  In the **Vendor account** field, select a vendor.
    
    The vendor contact information is copied to the RFQ line. The lowest status for the RFQ changes to **Created**.

6.  On the **Action Pane**, click **Send**. The RFQ is sent to the vendors that are specified.
    

    > [!NOTE]
    > <P>In AX 2012 R3 CU8, if the <STRONG>Public Sector</STRONG> key is selected, click <STRONG>Publish to Vendor portal</STRONG>. The RFQ will be sent to the specified vendors and appear in the <STRONG>Open requests for quotations</STRONG> list on the Vendor portal.</P>



## Remove a vendor from an RFQ

Use this procedure to remove a vendor from an RFQ. You can remove a vendor from an RFQ only when the status for the vendor is **Created**. You cannot remove a vendor after you have sent the RFQ to the vendor.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select or open the RFQ that you want to modify.

3.  In the **Request for quotation details** form, on the **Action Pane**, on the **Quotation** tab, click **Edit**.

4.  On the **Vendor** FastTab, select a vendor line where the highest status is **Created**, and then click **Remove**.

## Delete an RFQ line

Use this procedure to delete specific lines from an RFQ. You can delete lines only when the lowest status and highest status of the RFQ line are **Created** (that is, you have not sent or published the RFQ).


> [!WARNING]
> <P>If you delete the whole RFQ, all lines are deleted regardless of their status. For more information, see <A href="delete-requests-for-quotation.md">Delete requests for quotation</A>.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select or open the RFQ that you want to modify.

3.  In the **Request for quotation details** form, on the **Action Pane**, on the **Quotation** tab, click **Edit**.

4.  On the **Request for quotation lines** FastTab, select the check box for the line that you want to delete, and then click **Remove**.

## Change the requested delivery date

Use this procedure to change the requested delivery date on an RFQ header, which applies to the RFQ or on an individual RFQ line. You can change the delivery date on an RFQ header at any time. You can change the delivery date on an individual RFQ line only if you have not registered replies to the RFQ.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select or open the RFQ that you want to modify.

3.  In the **Request for quotation details** form, on the **Action Pane**, on the **Quotation** tab, click **Edit**.

4.  Follow one of these steps:
    
      - On the **Request for quotation header** FastTab, in the **Delivery date** field, change the date. Depending on how you configure the RFQ form and lines, the delivery date is copied to the RFQ lines. For more information, see [Update request for quotation lines (form)](https://technet.microsoft.com/library/hh227525\(v=ax.60\)).
    
      - On the **Request for quotation lines** FastTab, select the line, and then, in the **Delivery date** field, change the date.

5.  On the **Action Pane**, click **Send**. The RFQ is sent to the vendors that are specified.
    

    > [!NOTE]
    > <P>In AX 2012 R3 CU8, if the <STRONG>Public Sector</STRONG> key is selected, click <STRONG>Publish to Vendor portal</STRONG>. The RFQ will be sent to the specified vendors and appear in the <STRONG>Open requests for quotations</STRONG> list on the Vendor portal.</P>



## Return a bid to a vendor

Use this procedure to request additional items or information from the vendor or modify items that have already been bid on.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Open the bid that you want to work with.

3.  In the **Request for quotation reply** form, on the **Action Pane**, click **Enter reply**.

4.  Modify the lines in the RFQ or header as needed.

5.  (Optional) To add an attachment, on the **Action Pane**, click **Attachments**. On the Action strip, click **New**, select the type of attachment that you want, and then select the item. Click **Close**.

6.  To resend the RFQ to the vendor, on the **Action Pane**, click **Return**.

7.  In the **Resending request for quotation** form, in the lower pane, select the lines in the bid that you want to resend.

8.  Click **Parameters**, and then in the **Reason ID** field, enter a reason code.

9.  To print the RFQ return sheet, click **Print**, and then select the **Print return request for quotation reply** check box.

10. Click **OK** to update the bid and to print the return bid sheet to send the vendor.

## See also

[About requests for quotation](about-requests-for-quotation.md)

[About request for quotation statuses](about-request-for-quotation-statuses.md)

[Request for quotation details (form)](https://technet.microsoft.com/library/hh209669\(v=ax.60\))

  


