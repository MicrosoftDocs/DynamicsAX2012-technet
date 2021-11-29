---
title: Create a purchase inquiry
TOCTitle: Create a purchase inquiry
ms:assetid: ce0948cf-d59b-4db4-b84f-b22b82443ad4
ms:mtpsurl: https://technet.microsoft.com/library/Dn528955(v=AX.60)
ms:contentKeyID: 59641344
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- external review
- validate with vendor
- Purchase inquiry
audience: Application User
ms.search.region: Global
---

# Create a purchase inquiry 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

Use this procedure to validate a purchase with the vendor and generate a purchase inquiry before the purchase order is confirmed. For example, you can validate a vendor purchase with regard to product quality or delivery dates.

## Create and print a purchase inquiry

A purchase inquiry lets you print the contents of a purchase order before the purchase order is confirmed.

To create and print a purchase inquiry, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order.

3.  On the **Navigation Pane**, under **Purchase**, in the **Generate** group, select **Purchase inquiry**.

4.  Select **Print purchase inquiry**, click **Printer setup**, and then click **Purchase inquiry**.

5.  In the **Print destination settings** form, select a print destination, and then click **OK**.

## Define printing options for purchase inquiries

You can print purchase in a report format, so you must define the printing options for the purchase inquiry reports.

To define printing options for purchase inquiries, follow these steps:

1.  Click **Procurement and sourcing** \> **Setup** \> **Forms** \> **Form setup**.

2.  Click the **Purchase inquiry** link.

3.  Select the format for the report.

4.  Click the **General** link, and then click **Print management**.

5.  Click the **Purchase order purchase inquiry** folder, and then select **Original** or **Copy**. If this is the first time that you print a purchase inquiry, right-click **Purchase order purchase inquiry**, and then select **New**. In the **Original / copy** field, select **Original** or **Copy**.

6.  In the **Report format** field, select **PurchPurchaseOrder.Report**.

## View the approval status of purchase orders and identify orders with a purchase inquiry

When you create a purchase inquiry for a purchase order, the purchase order shows the **In external review** approval status. You can either view the approval status of a single purchase order, or you can use a filter to view a list of purchase orders with a particular status.

To view the approval status of a single purchase order, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order, and on the **Action Pane**, under **Purchase order**, in the **Maintain** group, click **Edit**.

3.  On the **Action Pane**, in the **Show** group, click the button to open the header view.

4.  On the **General** tab, view the approval status in the **Approval status** field. Purchase orders with a purchase inquiry have the **In external review** approval status.

To view a list of orders with a particular approval status, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Click Ctrl+G, or click the **Filter By Grid** button.

3.  In the **Approval status** field, type the approval status that you want to filter by. To filter by the **In external review** approval status, type In external review.

## Track version history or compare versions of the purchase inquiry

You can track changes that have been recorded on the purchase order or compare different versions of the purchase inquiry.

To track version history or compare versions of the purchase inquiry, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, under **Manage**, in the **History** group, select **View purchase order versions**.

3.  Select the two purchase order versions that you want to compare, and then click **Compare purchase order versions**.

## View or reprint purchase inquiries

To get an overview of existing purchase inquiries or reprint a purchase inquiry, you can use the purchase inquiry journal.

To view or reprint purchase inquiries, follow these steps:

1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order.

3.  On the **Navigation Pane**, under **Purchase**, in the **Journals** group, select **Purchase inquiry**.

4.  Select **Preview/Print**, and then click **Use print management** to print the journal.

## See also

[Create a purchase order](create-a-purchase-order.md)

[View purchase order confirmations](view-purchase-order-confirmations.md)

  


