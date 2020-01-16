---
title: About creating intercompany purchase orders or sales orders in several companies
TOCTitle: About creating intercompany purchase orders or sales orders in several companies
ms:assetid: 221768ad-3fc7-4fe3-8fa9-991ac67f60cd
ms:mtpsurl: https://technet.microsoft.com/library/Aa496795(v=AX.60)
ms:contentKeyID: 36056171
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About creating intercompany purchase orders or sales orders in several companies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX is not limited to handling only one production company and several sales companies. All companies that are set up for intercompany can be trading companies as well as production companies.

If more companies can deliver the same item, you can freely choose whom to buy from, and updates are processed even if one sales order becomes several purchase orders.

In the same way that you automatically create one intercompany purchase order, you can create an original sales order in your company and then have several intercompany vendor companies fulfill the order by creating more than one intercompany purchase order. Microsoft Dynamics AX automatically creates intercompany sales orders in the vendor companies.

To do this, all the companies must be set up as trading relationships. The vendor companies must be set up in Microsoft Dynamics AX as intercompany vendors, and they must be the primary vendor for the relevant item. On the sales order, in **Header view**, you must select the **Autocreate intercompany orders** field and the **Direct delivery** field on the **Intercompany settings** FastTab. This is the default setting.

You create the sales lines in the usual way. When you leave the record, an Infolog appears informing you that intercompany purchase orders and intercompany sales orders have been created. The Infolog contains links to the new orders. To view the intercompany sales orders created in your vendor companies, open the original sales order and on the **General** tab, in the **Related information** group, click **References**.

If you open the intercompany purchase orders for the vendors, you see that Microsoft Dynamics AX automatically fills in the original sales order number and the intercompany sales order number for each vendor.

Similarly, if you open the intercompany sales orders for the vendors, you see that Microsoft Dynamics AX automatically fills in the original sales order number and the intercompany purchase order number for each vendor.


> [!NOTE]
> <P>If the items on order exist in one of your intercompany vendor companies but not in the other, Microsoft Dynamics AX creates the intercompany orders for the vendor company where the items exist but stops the order creation for the other company. A notification message is displayed when this happens.</P>


  


