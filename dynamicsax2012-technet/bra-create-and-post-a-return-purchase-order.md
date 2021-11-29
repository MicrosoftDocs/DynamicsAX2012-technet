---
title: (BRA) Create and post a return purchase order
TOCTitle: (BRA) Create and post a return purchase order
ms:assetid: cd55f3c7-c387-44bd-88d6-a71b59adc8a2
ms:mtpsurl: https://technet.microsoft.com/library/JJ923390(v=AX.60)
ms:contentKeyID: 52075275
author: Khairunj
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- Brazil
- (BRA)
- Create return purchase order
- post return purchase order
- return purchase order
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a return purchase order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Organizations frequently return items to vendors when the items do not meet quality standards and order specifications, or when the items are damaged in transit. You can create and post a return purchase order for items that are returned to vendors. You must attach a fiscal reference for the return purchase order. You can change the delivery address for a return purchase order. The **CNPJ/CPF**, **IE**, and **Presence type** fields in the **Purchase order** form are updated based on the information that is specified for the vendor on the **Fiscal information** FastTab in the **Vendors** form. You can also modify the delivery address for the vendor in the **Create purchase order** form or on the purchase order lines.

You must assign a fiscal document type to a vendor before you create and post a return purchase order. For more information, see [(BRA) Assign fiscal document types for customers or vendors](bra-assign-fiscal-document-types-for-customers-or-vendors.md).

## Create a return purchase order

Use the **Create purchase order** form to create a return purchase order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order**, and then in the **Vendor account** field, select a vendor account.

3.  On the **General** FastTab, in the **Purchase type** field, select **Returned order**. For more information, see [Create purchase order (form)](https://technet.microsoft.com/library/aa570189\(v=ax.60\)).

4.  In the **RMA number** field, enter the Return Merchandise Authorization (RMA) number for the item that is returned. The number is provided by your vendor. This number is used to track an item that is returned.

5.  In the **Site** field, select the site of the fiscal establishment where you receive the order.

6.  Click **OK**.

7.  In the **Purchase order** form, create a purchase order line. In the **Quantity** field, enter a quantity that has a minus sign.

8.  In the **Purchase order** form, click **Purchase order line** \> **Fiscal document texts** to attach a fiscal document text to the purchase order line. For more information, see [(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md).

9.  On the **Line details** FastTab, on the **Setup** tab, in the **Return action** field, select a return action.

10. On the **Action Pane**, click **Header view**.

11. On the **Fiscal information** FastTab, in the **Operation type** field, select an operation type that you have created in the **Operation type** form. For more information, see [(BRA) Operation type (form)](https://technet.microsoft.com/library/jj822922\(v=ax.60\)).

12. Select the **Use and consumption** check box to indicate that the purchase is for consumption.

13. Select the **Service code on delivery address** check box to use a service code that is based on the delivery address for orders.

14. In the **Presence type** field, modify the presence type of the fiscal operation, if required.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



## Post a return purchase order

Use the **Vendor invoice** form to post a return purchase order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order that has a purchase type of **Returned order** and an approval status of **Confirmed**.

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  In the **Invoice description** field, enter a description for the invoice.

5.  On the **Action Pane**, click **Add fiscal reference** to attach a fiscal reference to the return purchase order. For more information, see [(BRA) Attach a fiscal reference to a fiscal document](bra-attach-a-fiscal-reference-to-a-fiscal-document.md).

6.  In the **Vendor invoice** form, on the **Action Pane**, click **Add shipping specifications**, and then create a shipment specification.

7.  Enter values in the **Volume type**, **Volume quantity**, **Gross weight**, and **Net weight** fields. For more information, see [(BRA) Shipments (form)](https://technet.microsoft.com/library/jj683240\(v=ax.60\)).

8.  Click **Post** \> **Post** to post the invoice.

## See also

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

[(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\))

[(BRA) Fiscal reference (form)](https://technet.microsoft.com/library/jj710558\(v=ax.60\))

  


