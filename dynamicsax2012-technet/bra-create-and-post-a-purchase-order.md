---
title: (BRA) Create and post a purchase order
TOCTitle: (BRA) Create and post a purchase order
ms:assetid: 51833cc7-1ec8-4aab-9646-6e6a93a70350
ms:mtpsurl: https://technet.microsoft.com/library/JJ911250(v=AX.60)
ms:contentKeyID: 52075249
author: tfehr
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- post purchase order
- Brazil
- (BRA)
- Create purchase order
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a purchase order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a purchase order by specifying the operation type, presence type of the fiscal operation, and Código Fiscal de Operações e Prestações (CFOP) code. The presence type of a fiscal operation in a purchase order is used to record fiscal information for receipts, packing slips, and invoices during posting.

You must assign a fiscal establishment to a site before you can create and post a purchase order. For more information, see [(BRA) Create sites](bra-create-sites.md).

Use the following procedures to create and post a purchase order.

## Create a purchase order

Use the **Create purchase order** form to create a purchase order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order**, and then in the **Vendor account** field, select a vendor account.

3.  On the **General** FastTab, in the **Purchase type** field, select **Purchase order**.

4.  Click **OK**.

5.  In the **Purchase order** form, on the **Action Pane**, click **Header view**, and then click the **Fiscal information** FastTab.

6.  In the **Operation type** field, select the operation type for the purchase order that determines whether the vendor invoice generates accounting entries or inventory movement, or creates vendor transactions.

7.  In the **Presence type** field, modify the presence type of the fiscal operation that you specified for the vendor on the **Fiscal information** FastTab in the **Vendor** form, if required. If you create a new purchase order for a vendor by copying an existing purchase order, the presence type of the original purchase order is applied to the new copied purchase order.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



8.  On the **Action Pane**, click **Line view**, and then create a purchase order line. At a minimum, you must specify an item, a purchase quantity, a unit, and a unit price.

9.  On the **Line details** FastTab, on the **Product** tab, in the **Site** field, select a site.

10. On the **Action Pane**, click **Fiscal document texts** to attach fiscal document texts to the purchase order. For more information, see [(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md).

## Post a purchase order

Use the **Vendor invoice** form to post a purchase order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order that has a status of **Approved** or **Confirmed**.

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  In the **Vendor invoice** form, enter values in the **Number**, **Invoice description**, and **Series** fields. For more information, see [(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\)).

5.  In the **Document model** field, select the document model for the vendor invoice.

6.  In the **Access key** field, enter the access key for the electronic fiscal document (NF-e).
    

    > [!NOTE]
    > <P>This field is available only if you select a document model in the <STRONG>Document model</STRONG> field, and if the <STRONG>Is for NF-e (federal)</STRONG> check box is selected for the document model in the <STRONG>Document model</STRONG> form.</P>



7.  In the **Number** field, enter the invoice number for the vendor invoice. In the **Series** field, enter the fiscal document series for the vendor invoice.
    

    > [!NOTE]
    > <P>These fields are available only if you select a document model in the <STRONG>Document model</STRONG> field, and if the <STRONG>Is for NF-e (federal)</STRONG> check box is cleared for the document model in the <STRONG>Document model</STRONG> form.</P>



8.  In the **Specie** field, select the specie for the vendor invoice.

9.  On the **Action Pane**, click **Add shipping specifications**, and then create a shipment specification.

10. Enter values in the **Volume type**, **Volume quantity**, **Gross weight**, and **Net weight** fields. For more information, see [(BRA) Shipments (form)](https://technet.microsoft.com/library/jj683240\(v=ax.60\)).

11. Click **Header view**.

12. On the **Fiscal information** FastTab, select the **Electronic fiscal document for services** check box.

13. In the **Presence type** field, modify the presence type of the fiscal operation that was specified for the purchase order, if required.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



14. On the **Action Pane**, click **Review** \> **Matching details** to validate the invoice.

15. Click **Vendor invoice** \> **Totals** to verify the total invoice amount for sales tax codes and charges.

16. Click **Post** \> **Post** to post the invoice.

## See also

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

[(BRA) Create and post a return purchase order](bra-create-and-post-a-return-purchase-order.md)

[(BRA) Create and post a purchase order for a foreign vendor](bra-create-and-post-a-purchase-order-for-a-foreign-vendor.md)

[Summary update sales and purchase orders](https://technet.microsoft.com/library/aa553732\(v=ax.60\))

  


