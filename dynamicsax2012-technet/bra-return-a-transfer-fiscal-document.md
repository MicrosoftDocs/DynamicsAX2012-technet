---
title: (BRA) Return a transfer fiscal document
TOCTitle: (BRA) Return a transfer fiscal document
ms:assetid: e3d0201b-f676-4e19-baff-586eabbbae30
ms:mtpsurl: https://technet.microsoft.com/library/JJ933535(v=AX.60)
ms:contentKeyID: 50935149
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- Transfer fiscal documents
- Return transfer orders
audience: Application User
ms.search.region: Brazil
---

# (BRA) Return a transfer fiscal document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to return a transfer fiscal document.

1.  Click **Inventory management** \> **Periodic** \> **Transfer orders**.

2.  In the upper pane, select a transfer order to return.

3.  Click **Functions**, and then click **Return order**.

4.  In the **Return order** form, in the left pane, select the fiscal establishment to return the transfer fiscal document for.

5.  In the right pane, select the transfer orders to return to the fiscal establishment that issued them.

6.  Click **OK** to create a return transfer order in the **Transfer orders** form. The status of the return fiscal document that is created is updated to **Created** in the **Transfer status** field. The type of order is updated to **Fiscal establishment return** or **Third party return** in the **Order type** field. The lower pane of the **Transfer orders** form is updated with the transfer order line to return.

7.  In **Transfer orders** form, in the lower pane, in the **CFOP** field, select the Código Fiscal de Operações e Prestações (CFOP) code.

8.  In the upper pane, on the **Fiscal information** tab, in the **Carrier name** field, select the name of the carrier that transports the items.

9.  Click **Posting**, and then click **Ship transfer order** to open the **Ship transfer order** form.

10. In the **Update** field, select **All** to ship the remaining quantity of items for each line. For more information, see [Transfer order shipment (form)](https://technet.microsoft.com/library/aa577094\(v=ax.60\)).

11. Select the **Edit lines** check box to update the transfer order lines based on the option that you selected in the **Update** field.

12. Select the **Print transfer shipment** check box to generate a transfer fiscal document for the return shipment.

13. Click **OK** to ship the return transfer order. The status of the transfer order is updated from **Created** to **Shipped** in the **Transfer status** field in the **Transfer orders** form.

## See also

[(BRA) Return order (form)](https://technet.microsoft.com/library/jj911254\(v=ax.60\))

[(BRA) About transfer orders](bra-about-transfer-orders.md)

[(BRA) Transfer orders (modified form)](https://technet.microsoft.com/library/jj910973\(v=ax.60\))

  


