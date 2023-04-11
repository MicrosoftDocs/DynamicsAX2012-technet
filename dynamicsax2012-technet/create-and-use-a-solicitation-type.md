---
title: Create and use a solicitation type
TOCTitle: Create and use a solicitation type
ms:assetid: 010b066e-f9f1-4739-8479-8614fc2b671c
ms:mtpsurl: https://technet.microsoft.com/library/Dn621047(v=AX.60)
ms:contentKeyID: 62200029
author: tonyafehr
ms.date: 11/14/2014
mtps_version: v=AX.60
f1_keywords:
- type
- types
- procurement
- PurchRFQCaseTableListPage
- Forms.PurchRFQSolicitationType
- solicitation
- solicitation type
- solicitation types
- solicitations
audience: Application User
ms.search.region: Global
---

# Create and use a solicitation type 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

As a purchasing manager or agent, you can create and maintain solicitation types to match the procurement requirements for your organization.

This feature is available only if **eProcurement** in Microsoft Dynamics AX 2012 R3 is installed.

This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8.

## Create a solicitation type

Use this procedure to create one or more new solicitation types that you can use when you are creating RFQs. For example, common types are request for quotation (RFQ), request for proposal (RFP), and invitation to bid (ITB).

1.  Click **Procurement and sourcing** \> **Setup** \> **Request for quotation** \> **Solicitation type**.

2.  In the **Solicitation type** form, click **New**.

3.  Enter a **Document title** and **Description** for the solicitation type.

4.  (Optional) In the **Scoring method** list, select a method. Now whenever you create an RFQ of this type, this scoring method will be associated with it.
    

    > [!NOTE]
    > <P>If there are no scoring methods, you can create one. For more information, see <A href="create-and-use-scoring-criteria-and-methods.md">Create and use scoring criteria and methods</A>.</P>



5.  (Optional) If you want to use a sealed bid process, in the **Bid type** list, select **Sealed**. For more information, see [About sealed bids](about-sealed-bids.md).

6.  (Optional) For public sector users, if you want only invited vendors to bid on this type of RFQ, select the **Bidding by invitation only** check box. This becomes the default setting for this solicitation type. If the check box is not selected, all Vendor portal users can bid on the RFQ. You can override this setting on a case-by-case basis.
    

    > [!NOTE]
    > <P>This control is available only if AX 2012 R3 CU8 is installed, and if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



7.  Click **Close**.

## Assign a solicitation type to a new RFQ

Use this procedure to specify the type of solicitation you are currently creating.

1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  On the **Action Pane**, on the **Quotation** tab, click **New**.

3.  In the **New request for quotation** form, in the **Solicitation type** list, select the type you want.
    

    > [!NOTE]
    > <P>There might already be a type assigned by default.</P>



4.  Continue creating the RFQ. For more information, see [Create a request for quotation](create-a-request-for-quotation.md).

## Assign a new type to an existing RFQ

Use this procedure if you want to change the solicitation type of an existing RFQ.


> [!NOTE]
> <P>The RFQ cannot have already been sent to vendors.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Requests for quotations** \> **All requests for quotations**.

2.  Select the RFQ whose solicitation type you want to change.

3.  On the **Action Pane**, in the **Maintain** group, click **Edit**

4.  In the **Request for quotation details** form, in the **Solicitation type** list, click the type you want.
    

    > [!IMPORTANT]
    > <P>This changes the scoring method for the RFQ to the method that is assigned to the new solicitation type.</P>



## See also

[Set up requests for quotation](set-up-requests-for-quotation.md)

[Create a request for quotation](create-a-request-for-quotation.md)

  


