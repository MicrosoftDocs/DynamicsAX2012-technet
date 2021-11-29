---
title: Create a request for quotation
TOCTitle: Create a request for quotation
ms:assetid: 904b96bd-f35c-4278-8fc3-1bd957c94f4a
ms:mtpsurl: https://technet.microsoft.com/library/Dn621059(v=AX.60)
ms:contentKeyID: 62200116
author: Khairunj
ms.date: 11/19/2014
mtps_version: v=AX.60
f1_keywords:
- RFQ
- procurement
- request for quotation
- requests for quotations
- Forms.PurchRFQCaseTableListPage
- Forms.PurchRFQReplyFields
- Forms.PurchRFQCaseTable
- Forms.PurchRFQEditLines
- quote
- request for quotations
- requests for quotation
- RFQs
- Menu_items.Display.PurchRFQTotals_Action
- MsDynAx060.Forms.PurchRFQEditLines
- MsDynAx060.Forms.PurchRFQCaseTable
- MsDynAx060.Forms.PurchRFQReplyFields
- MsDynAx060.Forms.PurchRFQCaseTableListPage
audience: Application User
ms.search.region: Global
---

# Create a request for quotation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to create a request for quotation (RFQ).


> [!NOTE]
> <P>The topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R3 Cumulative Update 8.</P>



## This task is part of a bigger process

The following illustration shows the end-to-end process for creating an RFQ, making it available to vendors, and evaluating bids returned by vendors. This procedure covers the numbered steps.

![End-to-end create RFQ-Send RFQ process](images/Dn621059.Create_an_RFQ-Eprocurement_Help(AX.60).jpg "End-to-end create RFQ-Send RFQ process")

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 with Procurement and Sourcing</p></td>
</tr>
<tr class="even">
<td><p>Related configuration tasks</p></td>
<td><p><a href="set-up-requests-for-quotation.md">Set up requests for quotation</a></p>
<p><a href="create-and-use-a-solicitation-type.md">Create and use a solicitation type</a></p>
<p><a href="create-and-use-scoring-criteria-and-methods.md">Create and use scoring criteria and methods</a></p></td>
</tr>
</tbody>
</table>


## 1\. Prepare the initial fields in an RFQ

In addition to information about the goods or services that you’re requesting bids on, an RFQ includes information about the order itself. For example, you specify delivery requirements and invite specific vendors to place bids. You enter this information in the **New request for quotation** form.

To prepare the initial fields in the RFQ, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  On the **Action Pane**, on the **Quotation** tab, click **Request for quotation**.

3.  In the **New request for quotation** form, select a **Purchase type** from the following options:
    
      - **Purchase order** - An agreement to purchase a specific quantity or value of product from a vendor.
    
      - **Purchase agreement** – An agreement to purchase a specific quantity or value of product over time. If you select this kind of purchase, you must select the date range that applies to the purchase agreement and the name of the person who manages the purchase agreement.
        

        > [!NOTE]
        > <P><STRONG>Purchase requisition</STRONG> – This type is automatically selected if you create an RFQ directly from a purchase requisition. If you manually select this type, an error message appears. For more information, see <A href="create-a-request-for-quotation-from-a-purchase-requisition.md">Create a request for quotation from a purchase requisition</A>.</P>



4.  In the **Currency** field, select the currency. The default is the currency of the legal entity.

5.  In the **Delivery date** field, select the date by which you want to receive the items.

6.  In the **Expiration date and time** field, specify the date and time by which vendors must respond to the RFQ.

7.  In the **Project ID** field, select a project if the items in the RFQ are for a project.

8.  If the delivery address differs from the legal entity address, click **Delivery address**, and then specify a delivery address.

9.  If there is a buyer group for the requester of the items, select it in the **Buyer group** field.

10. In the **Language** field, select the language in which you want to receive bids. A vendor can change the language in the bid.

11. In the **Document title** field, type a friendly description for the RFQ.
    

    > [!NOTE]
    > <P>Steps 11-13 apply if you are running AX 2012 R3.</P>



12. In the **Solicitation type** list, select the type that you want, such as RFQ. For more information, see [Create and use a solicitation type](create-and-use-a-solicitation-type.md).
    
    If a scoring method is associated with the type, then that will be the default for the RFQ you’re creating. You can change the scoring method later, if you want. For more information, see [Create and use scoring criteria and methods](create-and-use-scoring-criteria-and-methods.md).

13. If a specific department is making the request, specify it in the **Requesting department** field.

14. Click **OK** to create the RFQ. The information is transferred to the **Request for quotation header**. The highest and lowest status of the RFQ is **Created**.

## 2\. Specify the details of your requested good or services

After you’ve specified the basic information about your RFQ, you specify the goods or services that you want vendors to bid on.

To provide the specifics of your request, follow these steps:

1.  In the **Request for quotation details** form, on the **Request for quotation lines** FastTab, select a line type:
    
      - **Item** – An item that is tracked as inventory in Microsoft Dynamics AX and has an item number. **Item** is the default line type.
    
      - **Category** – A non-inventory good or service, which you enter manually from a hierarchy of procurement categories.

2.  This step applies if you are running AX 2012 R3. To enable vendors to submit sealed bids, in the **Request for quotation header**, in the **Bid type** list, select **Sealed**. Bids that you receive are then encrypted and inaccessible until bid tabulation starts, after the RFQ’s closing date.
    

    > [!NOTE]
    > <P>Vendors can use sealed bid functionality only with the Vendor portal on Enterprise Portal for Microsoft Dynamics AX. This functionality is not available with Sites Services for Microsoft Dynamics ERP.</P>



3.  This step applies if you are running AX 2012 R3. If you want the vendor to be able to provide substitutes or alternates, on the **General** FastTab, select the **Allow alternates on response lines** check box. One alternate is allowed per category line.

4.  Enter information for the line, such as inventory dimensions, quantity, unit, price, and discount information. If you want the vendor to provide the information, leave the fields blank.
    
    The RFQ expiration date and requested delivery date are copied from the RFQ header. You can change the dates for each line.

5.  Click **Add line** as many times as required. Each line is assigned a number, which appears on all RFQ-related documents.
    

    > [!NOTE]
    > <P>If you are running AX 2012 R3, you can use the line number to sort and filter in all the related documents. The numbers increment by 10. If you add a new line between two existing lines, it is assigned a number between the two lines. For example, if your original solicitation has three lines, they are numbered 10, 20, and 30. If you add a line between lines 10 and 20, it is assigned the number 15.</P>
    > <P>You can also renumber the list, which reassigns the lines incremented by 10. Until you publish or send the solicitation, you can add more lines and renumber the list. However, after you issue a purchase confirmation, you cannot renumber the list.</P>



6.  To add vendors, use one of the following methods:
    
      - If you are running AX 2012 R3, you can add vendors to the RFQ automatically, based on the procurement category of the items requested. On the **Vendor** FastTab, click **Auto-add vendors**.
    
      - Alternatively, on the **Vendor** FastTab, select a vendor in the **Vendor account** field. The contact information is added to the RFQ. The status is **Created**. This means that the vendor information has been saved in the RFQ, but you have not sent the RFQ to the vendor or published it on the Vendor portal. You can add a vendor to an RFQ regardless of the vendor status.
        

        > [!NOTE]
        > <P>Vendor-specific information, such as payment terms and currency, is not included in the RFQ.</P>



7.  You can attach documents to an RFQ header and lines.
    
      - To attach a document to an RFQ header, on the **Action Pane**, click **Attachments**.
    
      - To attach a document to an RFQ line, on the **Request for quotation lines** FastTab, click the **Documents** icon on the line.

8.  This step applies if you are running AX 2012 R3. If there is a questionnaire that you want vendors to complete as part of the bid, you can attach it to the RFQ by clicking the **Questionnaire** tab and then clicking **Add**. For more information about questionnaires in AX 2012 R3, see [Using questionnaires](using-questionnaires.md).

## 3\. Define request for quotation replies

You can specify the information that you want to receive from vendors when they bid on an RFQ. The fields that you select in the **Default request for quotation reply fields** form are printed on the reply sheet that you send to vendors.

You can also define the default fields that apply to all RFQ replies (bids). For more information, see [Define request for quotation replies](define-request-for-quotation-replies.md).


> [!NOTE]
> <P>In some cases, you might want to create an actual RFQ reply for a vendor. For more information, see <A href="create-a-reply-to-a-request-for-quotation.md">Create a reply to a request for quotation</A>.</P>



To change a specific RFQ’s reply fields from the default settings, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select the RFQ that you want to work with.

3.  On the **Action Pane**, on the **Quotation** tab, click **Configure request for quotation reply**.

4.  In the **Default request for quotation reply fields** form, select or clear the check boxes that correspond to the information that you want to receive.

## 4\. Send the RFQ and RFQ reply sheet


> [!NOTE]
> <P>If the <STRONG>Public Sector</STRONG> configuration key is installed, use step 6, “Publish the RFQ,” instead.</P>



After you’ve specified all the details, you have to let vendors view the RFQ.

Reply sheets contain fields to be filled in by the vendors to whom you send the RFQ. One RFQ and reply sheet is created for each vendor, and an RFQ journal is created. The RFQ journal contains both the RFQ and the reply sheet. To make your RFQ available to the vendors selected on the RFQ case, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select the RFQ that you want to work with. The lowest status of the RFQ must be **Created** or **Sent**.
    
    If a line’s lowest status is **Created**, there is at least one vendor that it has not been sent to. If a line’s lowest status is **Sent**, at least one vendor has not responded, and you can resend the RFQ to them.

3.  On the **Action Pane**, click **Send**.

4.  In the **Sending request for quotation** form, verify that the vendors in the list are the ones that you want to receive the RFQ. To remove any vendors, select the vendor, and then click **Delete**.
    

    > [!NOTE]
    > <P>The vendors that you delete by using the <STRONG>Sending request for quotation</STRONG> form are not removed from the RFQ, and they can see the RFQ on the <STRONG>All requests for quotations</STRONG> and <STRONG>Closed requests for quotations</STRONG> lists on the Vendor portal.</P>



5.  In the lower pane, select the RFQ lines to send, and delete any lines that you do not want to send.

6.  If you want to print the RFQ and reply sheet, proceed to step 5, Print the RFQ and RFQ reply sheet. Otherwise, in the **Sending request for quotation** form, click **OK** to send the RFQ to the selected vendors.
    

    > [!NOTE]
    > <P>If AX 2012 R3 CU8 is installed, and RFQ locking is enabled in <STRONG>Procurement and sourcing parameters</STRONG>, only certain fields will be editable. The RFQ will remain in this locked state unless you create an amendment. For more information, see <A href="modify-a-request-for-quotation.md">Modify a request for quotation</A>.</P>



## 5\. \[Optional\] Print the RFQ and RFQ reply sheet

If you print the RFQ when you send it, one RFQ and reply sheet is printed for each vendor, and an RFQ journal is created. The RFQ journal contains both the RFQ and the reply sheet. RFQ journals are created every time that an RFQ is updated by using the **Sending request for quotation** form.

To print your RFQ, follow these steps:

1.  In the lower pane, after you select the RFQ lines to send and delete any lines that you do not want to send, click **Print**.

2.  Select the **Print request for quotation** check box to print the selected RFQ, and select the **Print request for quotation reply sheet** check box to print an RFQ reply sheet. For more information about how to define fields in the RFQ reply sheet, see [Define request for quotation replies](define-request-for-quotation-replies.md).

3.  Select the **Print request for quotation prices/amounts** check box to print prices and amounts on the RFQ.
    
    To choose how to print reply sheets, click **Advanced printing options**.

4.  Click **OK** to print the RFQ and the RFQ reply sheet.
    
    One RFQ for each vendor will be printed where the lines have the lowest status of **Created** or **Sent** and the highest status of **Created** or **Sent**. Canceled lines and lines with registered replies will not be printed. RFQ journals are created every time that an RFQ is updated by using the **Sending request for quotation** form.

5.  In the **Sending request for quotation** form, click **OK** to send the RFQ to the selected vendors.

## 6\. Publish the RFQ (Public sector)

For Public sector in Microsoft Dynamics AX 2012 R3, you can make your RFQ available to any vendor visiting the Vendor portal, and at the same time send it to the vendors selected on the RFQ case, by following these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select the RFQ that you want to work with.

3.  On the **Action Pane**, in the **Process** group, click **Send and publish to Vendor portal**.

4.  In the **Sending and publishing request for quotation** form, click **OK**, and then click **OK** in the Infolog that appears.

The RFQ will appear in the **Open requests for quotations** list. All vendors that have access to the portal can view the RFQ. RFQ journals are created every time that you update an RFQ by using the **Sending and publishing request for quotation** form.


> [!NOTE]
> <P>If AX 2012 R3 CU8 is installed, and RFQ locking is enabled in <STRONG>Procurement and sourcing parameters</STRONG>, the RFQ will now remain locked. Only certain fields will be editable unless you create an amendment. For more information, see <A href="modify-a-request-for-quotation.md">Modify a request for quotation</A>.</P>



## Next step

You can modify an RFQ that has already been sent to vendors, and resend them. If you are in the public sector, and the RFQ has been published on the Vendor portal, you can republish the amended version. For more information, see [Modify a request for quotation](modify-a-request-for-quotation.md).

Typically, however, your next step is to compare and evaluate the bids that are returned to you. This can involve scoring and ranking the bids. You can then reject or accept lines in bids from one or more vendors. You can also return bids to vendors for more information. To learn more about these steps, see [Compare bids and award a contract](compare-bids-and-award-a-contract.md). For information about the steps that vendors take to reply to the RFQ, see [About vendor bids](about-vendor-bids.md).

## Related tasks

[About requests for quotation](about-requests-for-quotation.md)

[About sealed bids](about-sealed-bids.md)

[Set up requests for quotation](set-up-requests-for-quotation.md)

[Create and use a solicitation type](create-and-use-a-solicitation-type.md)

[Create and use scoring criteria and methods](create-and-use-scoring-criteria-and-methods.md)

[Create a request for quotation from a purchase requisition](create-a-request-for-quotation-from-a-purchase-requisition.md)

[Define request for quotation replies](define-request-for-quotation-replies.md)

[Create a reply to a request for quotation](create-a-reply-to-a-request-for-quotation.md)

[Modify a request for quotation](modify-a-request-for-quotation.md)

[Compare bids and award a contract](compare-bids-and-award-a-contract.md)

[About vendor bids](about-vendor-bids.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>The <strong>Public Sector</strong> configuration key must be enabled in order to publish RFQs.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To view published RFQs, you must be a member of a security role that includes the Vendor (External) – Public Sector duty.</p></td>
</tr>
</tbody>
</table>

  


