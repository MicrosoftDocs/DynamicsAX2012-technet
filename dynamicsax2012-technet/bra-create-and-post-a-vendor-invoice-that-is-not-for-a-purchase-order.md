---
title: (BRA) Create and post a vendor invoice that is not for a purchase order
TOCTitle: (BRA) Create and post a vendor invoice that is not for a purchase order
ms:assetid: c0c38c6b-ca94-4440-98a0-045a490226a2
ms:mtpsurl: https://technet.microsoft.com/library/JJ933528(v=AX.60)
ms:contentKeyID: 50935141
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00023
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a vendor invoice that is not for a purchase order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to create and post a vendor invoice that is not associated with a purchase order.

1.  Click **Accounts payable** \> **Common** \> **Vendor invoices** \> **Open vendor invoices**. On the **Action Pane**, click **Invoice** \> **Vendor invoice** to create a new vendor invoice, or double-click an existing vendor invoice.

2.  In the **Invoice account** field, select a vendor account.

3.  In the **Document model** field, select a fiscal document model.

4.  In the **Number** field, enter the fiscal document number.

5.  In the **Series** field, enter the fiscal document series number.

6.  In the **Specie** field, select the fiscal document specie.

7.  On the **Lines** FastTab, click **Add line** to create a new invoice line. Enter the required line details. For more information, see [(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\)).

8.  Click the **Line details** FastTab, and then click the **Fiscal information** tab.

9.  In the **CFOP** field, select a Código Fiscal de Operações e Prestações (CFOP) code. You must specify a CFOP code for a purchase order, returned item, or item that has a **Product type** of **Item**.

10. Click **Post** \> **Post** to post the vendor invoice.

## See also

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

[(BRA) Enter vendor invoice lines to a vendor invoice for a purchase order](bra-enter-vendor-invoice-lines-to-a-vendor-invoice-for-a-purchase-order.md)

  


