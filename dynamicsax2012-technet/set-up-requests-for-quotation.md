---
title: Set up requests for quotation
TOCTitle: Set up requests for quotation
ms:assetid: 49d82a07-6f3a-4ee5-977f-5ca7f17de204
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231403(v=AX.60)
ms:contentKeyID: 36056947
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- setup
- IFB
- request for quote
- RFQ
- create RFQ
- set up RFQ
- procurement
- request for quotation
- requests for quotations
- ReqPlanSched
- ITB
- quote
- request for quotations
- requests for quotation
- RFQs
- PurchFormLetterParameters
- SrmParameters
- IFBs
- invitation for bid
- invitation to bid
- invitation for bids
---

# Set up requests for quotation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use these procedures to set up default request for quotation (RFQ) parameters, forms, and functionality. This saves you the work of setting up parameters for every RFQ that you create.

For more information about the prerequisites needed for creating RFQs, see [Create and use a solicitation type](create-and-use-a-solicitation-type.md) and [Create and use scoring criteria and methods](create-and-use-scoring-criteria-and-methods.md).


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8. For more information, see the section later in this topic.</P>



## Set up request for quotation parameters

Use this procedure to define default values for RFQs. The default values are copied to the **Request for quotation** form when you create a new RFQ.

1.  Click **Procurement and sourcing** \> **Setup** \> **Procurement and sourcing parameters**.

2.  In the **Procurement and sourcing parameters** form, click **Request for quotation**.

3.  In the **Set up default values for requests for quotations** area, specify default values for RFQs, such as purchase type, expiration date and time, delivery information, payment terms, and trade agreement journal. For more information about parameters, see [Procurement and sourcing parameters (form)](https://technet.microsoft.com/en-us/library/hh208706\(v=ax.60\)).
    

    > [!NOTE]
    > <P>Microsoft Dynamics AX 2012 R3 introduces an <STRONG>Expiration Time</STRONG> field, which is set to the default company-specific time of day. This setting, with expiration date, becomes the default for the RFQ case.</P>



4.  Click **Default request for quotation reply fields**, and then select the types of information that you want to receive from vendors when they bid on an RFQ. For more information, see [Define request for quotation replies](define-request-for-quotation-replies.md).

5.  Click **Update request for quotation lines** to specify how you want to update RFQ lines when you modify the RFQ header and RFQ reply header.

## Set up vendor reply status categories

Use this procedure to define default values that you can assign to vendor replies to your RFQ. Use vendor reply status categories when you compare bids.

1.  Click **Procurement and sourcing** \> **Setup** \> **Request for quotation** \> **Vendor reply status**.

2.  In the **Vendor reply status** form, click **New**.

3.  In the **Status** field, enter a vendor response category. For example, you could enter “Bid,” “No bid,” or “Non-responsible.”

4.  In the **Description** field, enter a brief explanation of the status.

## Set up reason codes

Use reason codes to explain why a bid was accepted or rejected. You set up reason codes in the [Reasons (form)](https://technet.microsoft.com/en-us/library/hh209362\(v=ax.60\)). For more information, see [Set up reason codes for financial modules](set-up-reason-codes-for-financial-modules.md).

## Define form setup for requests for quotation

Use this procedure to define the information that you want to display in documents that are related to RFQs.

1.  Click **Procurement and sourcing** \> **Setup** \> **Forms** \> **Form setup**.

2.  In the **Form setup** form, click **Request for quotation**, and in the **Set up formats for requests for quotations** area, specify the information that you want to display in RFQ documents.


> [!NOTE]
> <P>Print management is available for RFQs. For more information, see <A href="https://technet.microsoft.com/en-us/library/hh209383(v=ax.60)">Print management setup (form)</A>.</P>



## Set up a master plan to include requests for quotation

Use this procedure to set up a master plan so that it includes RFQs.


> [!NOTE]
> <P>When you create an RFQ for a purchase order, and add an inventory item to the RFQ, an inventory transaction is created that has a receipt status of <STRONG>Quotation receipt</STRONG>. Only RFQ lines of this kind are considered when you use a master plan to calculate supplies.</P>



1.  Click **Master planning** \> **Setup** \> **Plans** \> **Master plans**.

2.  In the **Master plans** form, select a master plan.

3.  On the **General** FastTab, under **Setup**, select the **Include requests for quotations** check box.

For more information about master plans, see [Master plans (form)](https://technet.microsoft.com/en-us/library/aa591284\(v=ax.60\)).

## Set up results views in AX 2012 R3 CU8

Use this procedure to define what information vendors will see when they view your RFQ on the **Closed requests for quotations** page on the Vendor portal.

1.  Click **Procurement and sourcing \> Setup \> Request for quotation \> Results views.**

2.  In the **Results view** form, click **New**.

3.  Do one of the following:
    
      - In the **Name** column, select a template, and then clear or select the check boxes to suit your needs.
    
      - In the Action strip, click **New**, enter a name and description, and then clear or select the check boxes to suit your needs.

4.  Click **Close**.

## See also

[About requests for quotation](about-requests-for-quotation.md)

[Create a request for quotation](create-a-request-for-quotation.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

