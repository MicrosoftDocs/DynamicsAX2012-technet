---
title: Set up sales tax authorities
TOCTitle: Set up sales tax authorities
ms:assetid: 821bebd9-013d-4f3e-aa03-a107ec93e63f
ms:mtpsurl: https://technet.microsoft.com/library/Aa571557(v=AX.60)
ms:contentKeyID: 36058362
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales tax authorities
audience: Application User
ms.search.region: Global
---

# Set up sales tax authorities 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create as many sales tax authorities as you need, and each can have specific address and contact information and a report layout. Your organization can pay sales taxes to the authority directly or through a vendor account that you create for the sales tax authority.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax authorities**.

2.  Click **New** to create a sales tax authority.

3.  In the **Authority** field, enter a unique identifier for the sales tax authority.

4.  In the **Name** field, enter the full name or a description of the sales tax authority.

5.  Optional: If you set up the tax authority as a vendor, your organization can use its usual payment routines to pay the sales tax authority on time. For more information, see [Set up a sales tax authority as a vendor](set-up-a-sales-tax-authority-as-a-vendor.md).
    

    > [!NOTE]
    > <P>If you do not set up the tax authority as a vendor, a user must prepare a manual payment to the tax authority on the appropriate due date.</P>



6.  If one is available, select the report layout for your country/region in the **Report layout** field. If the report layouts do not correspond to the requirements of the sales tax authority, print a report that contains the information that the tax authority requires. Then complete the reporting forms that are supplied by the tax authority.

7.  Specify values in the **Rounding form** and **Round-off** fields for the posting of gains and losses that occur during rounding.

8.  If you did not set up the sales tax authority as a vendor in step 5, fill in the relevant fields on the **Address** and **Contact information** FastTabs.

## See also

[Example: Rounding payments made to sales tax authorities](example-rounding-payments-made-to-sales-tax-authorities.md)

  


