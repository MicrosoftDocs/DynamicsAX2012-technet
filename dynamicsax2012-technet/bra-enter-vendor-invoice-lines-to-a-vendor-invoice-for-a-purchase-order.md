---
title: (BRA) Enter vendor invoice lines to a vendor invoice for a purchase order
TOCTitle: (BRA) Enter vendor invoice lines to a vendor invoice for a purchase order
ms:assetid: 329a9814-ff09-4205-8521-523bfefeb0a6
ms:mtpsurl: https://technet.microsoft.com/library/JJ910977(v=AX.60)
ms:contentKeyID: 52075244
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Enter vendor invoice lines to a vendor invoice for a purchase order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to add invoice lines to a vendor invoice that is associated with a purchase order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, click **Purchase order** to create a new purchase order, or double-click an existing purchase order.

2.  On the **Action Pane**, on the **Invoice** tab, click **Invoice** to open the **Vendor invoice** form.

3.  In the **Invoice account** field, select a vendor account.

4.  In the **Document model** field, select a fiscal document model.

5.  In the **Access key** field, enter the access key for the fiscal document.
    

    > [!NOTE]
    > <P>This field is available only if you select a document model in the <STRONG>Document model</STRONG> field, and if the <STRONG>Is for NF-e (federal)</STRONG> check box is selected for the document model in the <STRONG>Document model</STRONG> form.</P>



6.  In the **Number** field, enter an invoice number. In the **Series** field, enter an invoice series number.
    

    > [!NOTE]
    > <P>These fields are available only if you select a document model in the <STRONG>Document model</STRONG> field, and if the <STRONG>Is for NF-e (federal)</STRONG> check box is cleared for the document model in the <STRONG>Document model</STRONG> form.</P>



7.  In the **Specie** field, select an invoice specie.

8.  On the **Lines** FastTab, click **Add line** to create a new invoice line. Enter the required line details. For more information, see [(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\)).

9.  On the **Line details** FastTab, on the **Fiscal information** tab, in the **CFOP** field, select a Código Fiscal de Operações e Prestações (CFOP) code. You must specify a CFOP code for a purchase order, returned item, or item that has a product type of **Item**.

10. In the **Service code** field, select the fiscal classification that is applied to the service. You must specify a service code for a purchase order, returned item, or item that has a product type of **Service**.

11. Click **Post** \> **Post** to post the vendor invoice.

## See also

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

  


