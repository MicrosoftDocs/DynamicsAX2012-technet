---
title: (IND) Create an import order and apply the AA incentive scheme to the import order
TOCTitle: (IND) Create an import order and apply the AA incentive scheme to the import order
ms:assetid: 3a08c5de-f850-4690-bcb1-c8f611abc00b
ms:mtpsurl: https://technet.microsoft.com/library/JJ664624(v=AX.60)
ms:contentKeyID: 49385701
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- AA
- Advanced Authorization
- incentive scheme
- AA incentive scheme
- import order
audience: Application User
ms.search.region: India
---

# (IND) Create an import order and apply the AA incentive scheme to the import order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Purchase order** form to create an import purchase order. For more information, see [Create a purchase order](create-a-purchase-order.md) and [(IND) Create import purchase orders](ind-create-import-purchase-orders.md).

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, in the **New** group, click **Purchase order** to create a new purchase order.

3.  On the **Excise balance** FastTab, on the **Tax information** tab, in the **Incentive scheme group** field, select the incentive scheme group.

4.  In the **Port ID** field, select the port for the import order. This field is updated with the port ID that has been attached to the incentive scheme group in the **Incentive scheme groups** form.

5.  In the **Product group** field, select the product group for the import purchase order. This field is updated with the product group that has been attached to the selected item on the **Foreign trade** FastTab of the **Released product details** form.

6.  On the **Purchase order lines** FastTab, click **Purchase order line**, and then click **Incentive scheme group** to open the **Incentive scheme groups** form. View the incentive scheme group for the item line.

7.  Close the **Incentive scheme groups** form.

8.  On the **Purchase order lines** FastTab, click **Purchase order line**, and then click **EXIM - AA** to open the **Import details** form. View information about the balance importable quantity and the balance importable value according to the authorization number.

9.  Close the **Import details** form and the **Purchase order** form.

## See also

[(IND) Manage purchase orders](ind-manage-purchase-orders.md)

[(IND) About the EXIM Advance Authorization (AA) incentive scheme](ind-about-the-exim-advance-authorization-aa-incentive-scheme.md)

[Create a purchase order](create-a-purchase-order.md)

[(IND) Create import purchase orders](ind-create-import-purchase-orders.md)

  


