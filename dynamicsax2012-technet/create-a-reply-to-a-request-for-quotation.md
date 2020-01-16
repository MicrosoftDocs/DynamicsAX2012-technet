---
title: Create a reply to a request for quotation
TOCTitle: Create a reply to a request for quotation
ms:assetid: 52ec2199-7177-4bea-92c1-386ee9ccd10f
ms:mtpsurl: https://technet.microsoft.com/library/Gg212791(v=AX.60)
ms:contentKeyID: 36057291
author: Khairunj
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- replies
- RFQ
- procurement
- request for quotation
- Forms.PurchRFQReplyTableListPage
- requests for quotations
- Forms.PurchRFQReplyTable
- Forms.PurchRFQCaseTable
- reply
- quote
- request for quotations
- requests for quotation
- RFQs
- MsDynAx060.Forms.PurchRFQCaseTable
- MsDynAx060.Forms.PurchRFQReplyTable
- MsDynAx060.Forms.PurchRFQReplyTableListPage
- request for quotation reply
audience: Application User
ms.search.region: Global
---

# Create a reply to a request for quotation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When you send an RFQ, a reply sheet is automatically created. Typically vendors reply to a request for quotation (RFQ) in the Vendor portal, but if they use another method, such as postal mail, you can use the following procedures to transfer that information to the RFQ reply sheet.


> [!NOTE]
> <P>If you want to modify requested items, you can use the <STRONG>Enter reply</STRONG> button in the RFQ list pages and RFQ details form. For more information, see <A href="modify-a-request-for-quotation.md">Modify a request for quotation</A>.</P>



## Create an RFQ reply

Use this procedure to manually add a vendor’s reply information to the RFQ reply sheet.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  Open the RFQ reply sheet that you want to work with.

3.  In the **Request for quotation reply** form, on the **Action Pane**, on the **Reply** tab, click **Edit**, and then enter the information for the vendor account on the **Purchase quotation header** FastTab. For information about how to enter vendor information, see the “Enter vendor reply information” section later in this topic.

4.  To verify or change charges, such as freight, on the **Action Pane**, on the **Reply** tab, in the **Financials** group, click **Manage charges**. For more information, see [Charges transactions (form)](https://technet.microsoft.com/library/aa633876\(v=ax.60\)).

5.  To create or update trade agreements for the vendor, on the **Action Pane**, on the **General** tab, in the **Trade agreements** group, click **Create price agreement journal**. For more information, see [Trade agreements (form)](https://technet.microsoft.com/library/aa499393\(v=ax.60\)).

6.  Save the form.

When you save the RFQ reply, the lowest status on the RFQ reply header changes to **Received** and the highest status changes to **Received**. When all replies to the RFQ are registered, the lowest status of the related RFQ itself changes to **Sent**.

## Enter vendor reply information

Use this procedure to enter the specific bid information from a vendor reply to an RFQ.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **Request for quotation replies**.

2.  On the **Request for quotation replies** list page, open the RFQ reply that you want to work with.

3.  In the **Request for quotation reply** form, on the **Action Pane**, on the **Reply** tab, click **Edit**.

4.  Enter reply information by using one of the following methods:
    
      - Copy information from the **Request for quotation details** form to the vendor reply sections in the RFQ reply you created. In the **Request for quotation reply** form, on the **Action Pane**, on the **Reply** tab, in the **Process** group, click **Copy data to reply**. You can modify the information that was copied to the reply.
    
      - Manually enter vendor reply information.
        

        > [!NOTE]
        > <P>If you selected the <STRONG>Use vendor for recalculating prices</STRONG> and the <STRONG>Use vendor specific item information</STRONG> check boxes in the <STRONG>Sending request for quotation</STRONG> form when you sent the request to vendors, some vendor-specific information is automatically entered. In the <STRONG>Request for quotation reply</STRONG> form, you can modify the RFQ information that is automatically entered.</P>



5.  If you need to enter alternate lines, open the **Purchase quotation lines** FastTab, and then click **Add line**. Enter the product information, such as item number or procurement category, quantity, price, and discount.
    

    > [!NOTE]
    > <P>To add alternates, you must have selected the <STRONG>Allow alternates on response lines</STRONG> check box in the <STRONG>Request for quotation header</STRONG>.</P>



When you save the RFQ reply, you can then accept or reject lines in the reply. You can also return it to a vendor for additional information. For more information, see [Compare bids and award a contract](compare-bids-and-award-a-contract.md).

## See also

[About requests for quotation](about-requests-for-quotation.md)

[About request for quotation statuses](about-request-for-quotation-statuses.md)

[Create a request for quotation](create-a-request-for-quotation.md)

[Add an alternate line to a request for quotation](add-an-alternate-line-to-a-request-for-quotation.md)

[Modify a request for quotation](modify-a-request-for-quotation.md)

  


