---
title: (LTU) Post a purchase invoice with VAT paid by the vendor
TOCTitle: (LTU) Post a purchase invoice with VAT paid by the vendor
ms:assetid: b1c5df6d-e734-4c2b-b2cb-cb46dd5cddd6
ms:mtpsurl: https://technet.microsoft.com/library/JJ665166(v=AX.60)
ms:contentKeyID: 49386746
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Post a purchase invoice with VAT paid by the vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Under certain conditions, purchase VAT is calculated and paid by the vendor if the vendor is registered in Lithuania as a VAT payer. These conditions include:

  - The company is selling wood and woodenwares, such as logs, planks, or beams.

  - The company is selling ferrous/non-ferrous items or products, including waste or debris.

  - The company is bankrupt.

The purchase documents issued by United VAT companies are marked in the purchase order to indicate that the VAT is paid by the United VAT company.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Press CTRL+N to create a new purchase order.
    

    > [!NOTE]
    > <P>For more information, see "Create a purchase order" in the Applications and Business Processes Help.</P>



3.  Click **Header view**, click the **Setup** FastTab.

4.  Select the **United VAT invoice** check box to indicate that the VAT is paid by the United VAT company for the vendor.
    

    > [!NOTE]
    > <P>The check box is selected by default if the <STRONG>United VAT invoice</STRONG> check box is activated for the vendor in the <STRONG>Vendors</STRONG> form.</P>



5.  Click the **Setup** tab in the lower pane.

6.  In the **Item sales tax group** field, select the item sales tax group that has a negative sales tax code percentage.

7.  In the **Sales tax group** field, select the sales tax group that has a negative sales tax code percentage.

8.  Click **Invoice** \> **Invoice** to open the **Vendor invoice** form. Click **Post** to post the purchase invoice.

  


