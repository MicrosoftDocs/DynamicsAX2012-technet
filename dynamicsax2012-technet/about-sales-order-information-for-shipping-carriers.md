---
title: About sales order information for shipping carriers
TOCTitle: About sales order information for shipping carriers
ms:assetid: cd76ebc5-eae4-4b09-9015-892f2e72a4ef
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213673(v=AX.60)
ms:contentKeyID: 36931881
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About sales order information for shipping carriers 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If a shipping carrier interface is set up, information about the sales order is transferred to the shipping carrier software. This transfer is based on the mode of delivery, carrier code, and other parameters that are specified for the sales order.

If the order is paid by credit card, the credit card was not preauthorized when the order was taken, and preauthorizations are enabled, the credit card is preauthorized for the amount of the order plus the estimated shipping charges that are specified on the **Credit card** tab in the **Accounts receivable parameters** form.

When you post customer invoices, the following information is updated in Microsoft Dynamics AX 2012:

  - If you charge your customer for the shipping charges, the shipping charges are added as miscellaneous charges to the invoice.

  - If your customer pays the shipping charges to the shipping carrier, miscellaneous charges are not updated.

  - If you pay the shipping charges on behalf of your customer, miscellaneous charges are not updated.
    

    > [!NOTE]
    > <P>If you offer free shipping to some of your customers, there is a difference between the revenue collected for shipping charges and the invoice that you receive from the shipping carrier.</P>



If you are using warehouse management and the Kewill ClipperShip software interface, the following additional information is updated in Microsoft Dynamics AX 2012:

  - If the order is COD, the invoice is posted and printed so that it can be included with the packing slip.

  - Any COD amounts are applied to each package.

## See also

[Post packing slips and update information for shipping carriers](post-packing-slips-and-update-information-for-shipping-carriers.md)

  


