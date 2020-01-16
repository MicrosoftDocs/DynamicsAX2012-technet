---
title: Compare bids and award a contract
TOCTitle: Compare bids and award a contract
ms:assetid: 5f287f09-4dc9-4a09-bef3-125665e27cbb
ms:mtpsurl: https://technet.microsoft.com/library/Dn621055(v=AX.60)
ms:contentKeyID: 62200078
author: Khairunj
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- comparisons
- rank
- Forms.PurchRFQCompare
- RFQ reply
- procurement
- contract
- contracts
- Forms.PurchRFQReplyTable
- score
- Class.PurchRFQFormLetter_Accept
- Class.PurchRFQFormLetter_Reject
- Class.PurchRFQFormLetter_ReSend
- bid
- bids
- MsDynAx060.Forms.PurchRFQReplyTable
- award
- scores
- awards
- comparison
audience: Application User
ms.search.region: Global
---

# Compare bids and award a contract 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to evaluate bids and award a contract after vendors respond to your request for quotation (RFQ).

If you are running a version of Microsoft Dynamics AX earlier than Microsoft Dynamics AX 2012 R3, go to step 5.

The following illustration shows the process of receiving bids from vendors, evaluating each bid, and then accepting a bid. This procedure covers the five numbered steps. After you have accepted a bid for the RFQ, you transfer the information to a purchase order.


> [!NOTE]
> <P>As you review individual bids, you might find bids that you want to reject, or you might want to reject specific lines, before you score and compare the remaining bids. In this case, see step 5 first.</P>



![Process of compare and accept a bid](images/Dn621055.Compare_and_accept(AX.60).jpg "Process of compare and accept a bid")

## 1\. Optional: Open sealed bids

This section applies if you are running AX 2012 R3 and are working with sealed bids.

When RFQs are sealed, bid line amounts and quantities are hidden from anyone viewing the RFQ except the bidding vendor. You can unseal a sealed RFQ only after the specified expiration date and time. Until you unseal it, you cannot accept or reject the bid. For more information, see [About sealed bids](about-sealed-bids.md).


> [!IMPORTANT]
> <P>After you unseal an RFQ, everyone will be able to view the bid information, and you cannot seal the RFQ again. Be aware that sealed bid functionality works only with the Vendor portal, and not Sites Services for Microsoft Dynamics ERP.</P>



To open a sealed bid (RFQ), follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Use the filter options to find the RFQ that you want to work with, and then open it.

3.  On the **Request for quotation reply** form, if the bid type is **Sealed** and the expiration date has been met, then on the **Reply** tab, click **Unseal bids**.

## 2\. Optional: Enter scores for bids

This section applies if you are running AX 2012 R3 and want to score bids.

If the RFQ has a scoring method associated with it, you can evaluate the bid based on the scoring criteria. This is based on an overall level for the bid. For more information, see [Create and use scoring criteria and methods](create-and-use-scoring-criteria-and-methods.md).

To score a bid, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Use the filter options to find the RFQ that you want to score, and then open it.

3.  On the **Request for quotation reply** form, click the **Bid scoring** FastTab.

4.  Enter a score in the range for each criterion.

5.  To see the total scores for the bidding vendors, open the **All requests for quotations** list page, click the **Vendor** FastTab, and then review the **Score** column.

6.  You can filter the bids by using the **Show** list. For example, you could display the lines with the lowest price. You can also exclude or include rejected lines, declined lines, accepted lines, and lines that the vendor has not responded to.

## 3\. Compare bids

This section applies if you are running AX 2012 R3 and want to compare the information between bids, regardless of whether you’ve scored them.

To compare bids, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Click the RFQ for which you want to compare bids.

3.  On the **Action Pane**, on the **Quotation** tab, click **Compare replies**.

4.  In the **Compare request for quotation replies** form, compare the lines in vendor bids. Use the **Show** list and check boxes to filter the results. By default, the following information is displayed in the list:
    
      - **Quantity** – The quantity quoted by a vendor. This might not equal the quantity specified in the RFQ.
    
      - **Net amount** – The price quoted by a vendor, after subtracting any discounts, for the items on the line.
    
      - **Deviation** – The number of days that the delivery date in the bid header or line deviates from the requested delivery date in the RFQ header or RFQ line.

5.  If you want to add columns for information in other fields in the RFQ, such as color or serial number, click **Dimensions display**.

6.  Click a line in the list to select it.

7.  In the pane on the rightmost side of the form, expand the **Line prices** section to view the unit price and other details about the line.

8.  On the **Bid scoring** FastTab, under **Scoring rationale**, you can provide a status to the vendor’s reply and provide a comment.
    

    > [!NOTE]
    > <P>To create the status categories, see <A href="set-up-requests-for-quotation.md">Set up requests for quotation</A>.</P>



9.  Optional: You can accept and reject bids in the **Compare request for quotation replies** form, or as a separate task. For information about how to accept and reject bids, see step 5, ”Accept, reject, or return bids.”

## 4\. Optional: Rank bids

This section applies if you are running AX 2012 R3 and want to rank bids against each other.

When you compare the quotations from the qualified bids, you can rank the bids at the header level. To do this, filter and sort on the information that is most relevant, such as price or score.

To rank bids, follow these steps for each bid:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Use the filter options to find the bid that you want to rank, and then open it.

3.  On the **Request for quotation reply** form, open the **Bid scoring** FastTab.

4.  Enter a number in the **Rank** field.

To compare the ranked bids, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Use the filter options to find the RFQ case whose ranked bids you want to compare, and then click one of the bids.

3.  On the **Action Pane**, on the **General** tab, click **Compare replies**.

4.  Sort the list as you need.

## 5\. Accept, reject, or return bids

You can accept or reject an entire bid or individual lines in a bid, and you can return a bid to the vendor for more information.


> [!NOTE]
> <P>If you are running AX 2012 R3, you can also accept or reject bids directly in the <STRONG>Compare request for quotation replies</STRONG> form (see step 3). When you use that form, the actions are basically the same as in the following steps.</P>



To accept lines in an individual bid from a vendor, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Open the bid that you want to work with.

3.  On the **Request for quotation reply** form, do one of the following:
    
      - If you want to accept all lines in a bid, on the **Action Pane**, on the **Reply** tab, click **Accept**. For a purchase type of **Purchase requisition**, if alternate lines are present, you can only accept either the original bid line or its alternate, but not both.
    
      - If you want to accept only some of the lines in a bid, on the **Action Pane**, click **Edit**. Select the **Mark** check box for the lines that you want, and on the **Action Pane**, click **Accept**.
        

        > [!NOTE]
        > <P>You can accept one vendor’s bid on some lines of an RFQ but award other RFQ lines to a different vendor.</P>



4.  The **Posting request for quotation acceptance** form appears and displays the selected lines.

5.  Click **Parameters**, and then, in the **Reason accept** field, enter a reason code. Click **OK**.

6.  Click **Print**, and then select the **Print request for quotation acceptance** check box to print the RFQ acceptance sheet. Click **OK**.

7.  In the **Posting request for quotation acceptance** form, click **OK** to update the status of the bid lines and to print the RFQ acceptance sheet. An RFQ journal and a purchase order are created automatically based on the accepted lines in the bid. Click **OK** again in the message that appears.

8.  Optional: The **Posting request for quotation rejection** form appears and displays the remaining bids, and any remaining unaccepted lines on the current bid, for you to reject. If you want to continue without explicitly rejecting bids, click **Cancel**. If you want to reject the bids, click **OK**.
    

    > [!NOTE]
    > <P>It is not necessary to select the <STRONG>Mark</STRONG> check box for the lines that you want to reject.</P>



Typically you don’t have to explicitly reject bids, because accepting a bid for a line item automatically rejects the line in competing bids. However, if you want, you can use the following procedure if, for example, a bid doesn’t meet requirements and you want to notify the vendor. You might do this before or during the initial scoring or comparing of bids.

To reject lines in a bid, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Open the bid that you want to work with.

3.  On the **Request for quotation reply** form, do one of the following:
    
      - If you want to reject all lines in the bid, on the **Action Pane**, on the **Reply** tab, click **Reject**. The **Posting request for quotation rejection** form appears and displays the selected bid. Click **OK**.
    
      - If you want to reject only some of the lines in a bid, on the **Action Pane**, click **Edit**. Select the **Mark** check box for each line that you want to reject. On the **Action Pane**, on the **Reply** tab, click **Reject**. The **Posting request for quotation rejection** form appears and displays the lines that you selected.

4.  Click **Parameters**, and then, in the **Reason reject** field, enter a reason code.

5.  Click **Print**, and then select the **Print request for quotation rejection** check box to print the RFQ rejection sheet.

6.  In the **Posting request for quotation rejection** form, click **OK** to update the status of the rejected lines in the bid and to print the RFQ rejection sheet. An RFQ journal is created.

To return a bid to a vendor for more information, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Open the bid that you want to work with.

3.  In the **Request for quotation reply** form, on the **Action Pane**, on the **Reply** tab, click **Return**.

4.  In the **Resending request for quotation** form, in the lower pane, select the lines in the bid that you want to resend.

5.  Click **Parameters**, and then in the **Reason ID** field, enter a reason code.

6.  Click **Print**, and then select the **Print return request for quotation reply** check box to print the RFQ return sheet.

7.  Click **OK** to update the bid and to print the return bid sheet that you will send to the vendor.

## Next step

Next, you transfer the information from the awarded RFQ to a purchase order that you send to the winning vendors. For more information, see [Create a purchase order](create-a-purchase-order.md).

## Related tasks

[Create and use scoring criteria and methods](create-and-use-scoring-criteria-and-methods.md)

[Add an alternate line to a request for quotation](add-an-alternate-line-to-a-request-for-quotation.md)

[Create a reply to a request for quotation](create-a-reply-to-a-request-for-quotation.md)

[Modify a request for quotation](modify-a-request-for-quotation.md)

[About sealed bids](about-sealed-bids.md)

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
<td><p>No configuration key is required for this task.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>

  


