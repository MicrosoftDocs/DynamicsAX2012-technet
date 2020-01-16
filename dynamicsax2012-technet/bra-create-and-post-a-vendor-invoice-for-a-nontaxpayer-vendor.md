---
title: (BRA) Create and post a vendor invoice for a nontaxpayer vendor
TOCTitle: (BRA) Create and post a vendor invoice for a nontaxpayer vendor
ms:assetid: 947dc508-f2fb-4cff-a3b6-b16a5f962e30
ms:mtpsurl: https://technet.microsoft.com/library/JJ911296(v=AX.60)
ms:contentKeyID: 52075258
author: Khairunj
ms.date: 11/18/2014
mtps_version: v=AX.60
f1_keywords:
- Brazil
- (BRA)
- Create purchase invoice
- nontaxpayer
- nontaxpayer vendor
- post purchase invoice
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a vendor invoice for a nontaxpayer vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post vendor invoices on behalf of nontaxpayer vendors. You must assign a fiscal establishment to a site. You must also set up a fiscal document type for purchase orders that you create and post on behalf of nontaxpayer vendors. For more information, see [(BRA) Create sites](bra-create-sites.md) and [(BRA) Assign fiscal document types for customers or vendors](bra-assign-fiscal-document-types-for-customers-or-vendors.md). Before you can create and post vendor invoices on behalf of a nontaxpayer vendor, you must specify the vendor as a nontaxpayer vendor.

## Specify a vendor as a nontaxpayer vendor

Use the **Vendors** form to specify a vendor as a nontaxpayer vendor.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click a vendor account.

3.  On the **Fiscal information** FastTab, select the **Generate incoming fiscal document** check box to indicate that the vendor is a nontaxpayer.

## Create a purchase order for a nontaxpayer vendor

Use the **Create purchase order** form to create a purchase order for a nontaxpayer vendor.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  On the **Action Pane**, click **Purchase order**, and then in the **Vendor account** field, select a vendor account that is classified as a nontaxpayer.

3.  On the **General** FastTab, in the **Purchase type** field, select **Purchase order**.

4.  Click **OK**.

5.  In the **Purchase order** form, create a purchase order line. At a minimum, you must specify an item, purchase quantity, unit, and unit price.

6.  On the **Line details** FastTab, on the **Product** tab, in the **Site** field, select a site.

7.  On the **Action Pane**, click **Fiscal document texts** to attach fiscal document texts to the purchase order or purchase order line. For more information, see [(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md).

## Post a vendor invoice for a nontaxpayer vendor

Use the **Vendor invoice** form to post a vendor invoice for a nontaxpayer vendor.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order that has a status of **Approved** or **Confirmed**.

3.  On the **Action Pane**, click **Invoice** \> **Invoice**.

4.  In the **Invoice description** field, enter a description for the invoice.

5.  In the **Invoice date** field, select an invoice date.

6.  On the **Action Pane**, click **Add shipping specifications**, and then create a shipment specification.

7.  Enter values in the **Volume type**, **Volume quantity**, **Gross weight**, and **Net weight** fields. For more information, see [(BRA) Shipments (form)](https://technet.microsoft.com/library/jj683240\(v=ax.60\)).

8.  Click **Header view**.

9.  On the **Fiscal information** FastTab, in the **Operation type** field, select an operation type that you have created in the **Operation type** form. For more information, see [(BRA) Operation type (form)](https://technet.microsoft.com/library/jj822922\(v=ax.60\)).

10. In the **CFOP** field, select a Código Fiscal de Operações e Prestações (CFOP) code that you have created in the **CFOP codes** form. For more information, see [(BRA) CFOP codes (form)](https://technet.microsoft.com/library/jj933522\(v=ax.60\)).

11. Select the **Use and consumption** check box to indicate that the purchase is for consumption.

12. In the **Presence type** field, modify the presence type of the fiscal operation that you specified for the vendor on the **Fiscal information** FastTab in the **Vendors** form, if required.
    

    > [!NOTE]
    > <P>This control is available only if cumulative update 8 for AX2012 R3 is installed.</P>



13. On the **Action Pane**, click **Review** \> **Matching details** to validate the invoice.

14. Click **Vendor invoice** \> **Totals** to verify the total invoice amount for sales tax codes and charges.

15. Click **Post** \> **Post** to post the invoice.

## See also

[(BRA) Purchase order (modified form)](https://technet.microsoft.com/library/jj911277\(v=ax.60\))

[(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\))

[(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md)

[(BRA) Create and post a purchase order for a foreign vendor](bra-create-and-post-a-purchase-order-for-a-foreign-vendor.md)

  


