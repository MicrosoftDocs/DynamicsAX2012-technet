---
title: 'Examples: Three-way matching policies'
TOCTitle: 'Examples: Three-way matching policies'
ms:assetid: 2cd96625-caf1-4f24-a3eb-8ff16c12a87c
ms:mtpsurl: https://technet.microsoft.com/library/Hh292596(v=AX.60)
ms:contentKeyID: 36655926
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Examples: Three-way matching policies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

For conceptual information about matching policies, see [About Accounts payable invoice matching](about-accounts-payable-invoice-matching.md).

## Example: Three-way matching for items

Summary: Ken is the controller at the corporate headquarters of a legal entity named Fabrikam. Ken decides that all vendor invoices that are based on purchase orders should be matched with purchase order lines (two-way matching). For purchases of items that will be used as fixed assets, invoices should be matched with both the purchase order lines and the product receipt lines (three-way matching).

Fabrikam operates with multiple legal entities and employees in all parts of the world. As the volume of transactions increases, discrepancies between receipts and invoices are also increasing. This results in assets being written off. Invoices from vendors are being paid, but the process does not include identifying discrepancies when fewer items are received than were ordered, or when items are not received at all. Spending also increases because employees still need tools and other materials to do their jobs. Ken wants to make sure that vendors are shipping the products that are ordered and the items are being received by Fabrikam employees. Therefore, Ken requires two-way and three-way matching for all legal entities in the organization. Invoice matching helps make sure that problems with items that have disappeared or not been received can be tracked and resolved.

The invoice matching policies in this example help people in the following roles meet these goals:

  - Ken is the controller for the Fabrikam enterprise. He can help the people in his organization to identify and correct problems with ordering, receiving, and paying for items (goods and services) from vendors.

  - Phyllis and April are accounting managers in the accounts payable department for the United States division of Fabrikam. They can enforce corporate policy and make sure that invoices are paid only after the invoices are matched with the purchase order and receipts of goods and services, where applicable.

  - Tony is the production manager for the United States division of Fabrikam. He and other production personnel can make sure that items are received as they were ordered from vendors, and are accounted for so that the personnel have what they must have in order to perform their jobs.

## Prerequisites

  - Ken sets the matching policy at the legal entity level to **Three-way matching**.

  - Ken sets the **Match price totals** field for the legal entity to **Percentage**, and enters 15% as the tolerance percentage.

  - Ken sets the matching policy at the item level for item 1500 – CNC Milicron Machine to **Three-way matching**. This item is an asset item that is used for production at Fabrikam. Invoices for this item are matched with purchase order lines for prices and with product receipts for quantities.

  - Tony enters a requisition for five CNC Milicron Machines. Alicia, a purchase order clerk at Fabrikam, issues a purchase order to a legal entity named Contoso to supply the items.
    
    <table style="width:100%;">
    <colgroup>
    <col style="width: 16%" />
    <col style="width: 16%" />
    <col style="width: 16%" />
    <col style="width: 16%" />
    <col style="width: 16%" />
    <col style="width: 16%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Item number</strong></p></th>
    <th><p><strong>Quantity</strong></p></th>
    <th><p><strong>Unit price</strong></p></th>
    <th><p><strong>Net amount</strong></p></th>
    <th><p><strong>Charges code</strong></p></th>
    <th><p><strong>Charges value</strong></p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>1500 – CNC Milicron Machine</p></td>
    <td><p>5</p></td>
    <td><p>8,000.00</p></td>
    <td><p>40,000.00</p></td>
    <td><p>Shipping &amp; handling</p></td>
    <td><p>3,000.00</p></td>
    </tr>
    </tbody>
    </table>


  - Arnie, an accounts receivable clerk at Contoso, reviews shipments for the week. Arnie selects shipment transactions to invoice Fabrikam for the delivery of the CNC Milicron Machines. Arnie includes a charge for shipping and handling. Fabrikam will consider the charge to be part of the cost of the asset.

## Scenario

1.  Sammy, a worker in the receiving department at Fabrikam, receives the total quantity of machines that are shipped from Contoso. He enters a quantity of 5 on a product receipt. Because the purchase order has been fully received, the status of the purchase order changes to **Received**.

2.  April, the accounts payable coordinator at Fabrikam, enters and verifies the invoice that is submitted by Contoso. She verifies the following information:
    
      - For items that require three-way matching, the quantity on the invoice line matches the quantity that was received. The received quantity is indicated on the product receipt that is matched to the invoice.
    
      - For items that require two-way or three-way matching, the prices on the invoice line are within the tolerances that are defined in Microsoft Dynamics AX.
        
        This includes the following types of price matching:
        
          - Net unit price matching – The net unit price on the invoice line matches the net unit price on the purchase order line, within the tolerance percentage. In this example, the net unit price tolerance is +8%.
        
          - Price totals matching – The net amount on the invoice line matches the net amount on the purchase order line, within the tolerance percentage, amount, or percentage and amount. In this example, the price totals matching tolerance is +15%.

The paper invoice from Contoso contains the following information.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Quantity</p></th>
<th><p>Unit price</p></th>
<th><p>Net amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1500 – CNC Milicron Machine</p></td>
<td><p>5</p></td>
<td><p>8,100.00</p></td>
<td><p>40,500.00</p></td>
</tr>
<tr class="even">
<td><p>Shipping and handling</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>4,000.00</p></td>
</tr>
<tr class="odd">
<td><p>Tax</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>0.00</p></td>
</tr>
<tr class="even">
<td><p>Total</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>44,500.00</p></td>
</tr>
</tbody>
</table>


In Microsoft Dynamics AX, the invoice line includes the following information.

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Item number</strong></p></th>
<th><p><strong>Quantity</strong></p></th>
<th><p><strong>Unit price</strong></p></th>
<th><p><strong>Line net amount</strong></p></th>
<th><p><strong>Matching policy</strong></p></th>
<th><p><strong>Product receipt quantity match</strong></p></th>
<th><p><strong>Price match</strong></p></th>
<th><p><strong>Price total match</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>1500 – CNC Milicron Machine</p></td>
<td><p>5</p></td>
<td><p>8,100.00</p></td>
<td><p>40,500.00</p></td>
<td><p><strong>Three-way matching</strong></p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
</tbody>
</table>


Because this line passes the invoice matching process, the invoice can be posted.

## Example: Three-way matching for item and vendor combinations

Summary: Ken is the controller at the corporate headquarters of a legal entity named Fabrikam. Ken decides that all invoices that are based on purchase orders should be matched with purchase order lines (two-way matching). Cassie is the bookkeeper at the Malaysia division of Fabrikam. She specifies that selected items that are ordered from certain vendors in Malaysia should be matched with both the purchase order lines and product receipt lines (three-way matching). She can also override the matching policy to a higher level of matching for specific purchase orders.

The volume and amounts are small, and there have been problems with delivery from some vendors in Malaysia. For these reasons, Cassie sets the level of control for certain item and vendor combinations that are procured in Malaysia to three-way matching.

The invoice matching policies in this example help people in the following roles meet these goals:

  - Ken is the controller for the Fabrikam enterprise. He can help the people in his organization to identify and correct problems with ordering, receiving, and paying for items (goods and services) from vendors.

  - Cassie is the bookkeeper for the Malaysia division of Fabrikam. She can enforce corporate policy and make sure that invoices are paid only after they are matched with purchase order lines and product receipts that represent the receipt of goods and services. She can also increase the level of control to three-way matching for specific items to control operational costs.

## Prerequisites

  - Ken sets the matching policy at the legal entity level to **Two-way matching**.

  - Ken sets the **Match price totals** field for the legal entity to **Percentage**, and enters 10% as the tolerance percentage.

  - Ken sets the unit price tolerance for all items to 2%.

  - Cassie sets the matching policy at the item and vendor combination level for item PH2500 – Computer and vendor Contoso to **Three-way matching**.

  - Alicia, a purchase order clerk at the Malaysia division of Fabrikam, issues purchase orders to Contoso to supply three items, as shown in the following table. When she creates the purchase order, she overrides the matching policy for the wireless mouse to be three-way matching instead of two-way matching.
    
    <table style="width:100%;">
    <colgroup>
    <col style="width: 16%" />
    <col style="width: 16%" />
    <col style="width: 16%" />
    <col style="width: 16%" />
    <col style="width: 16%" />
    <col style="width: 16%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p><strong>Item number</strong></p></th>
    <th><p><strong>Quantity</strong></p></th>
    <th><p><strong>Unit price</strong></p></th>
    <th><p><strong>Net amount</strong></p></th>
    <th><p><strong>Matching policy</strong> (default entry)</p></th>
    <th><p><strong>Matching policy</strong> (on the purchase order line)</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>PH2500 – Computer</p></td>
    <td><p>2</p></td>
    <td><p>2,500.00</p></td>
    <td><p>5,000.00</p></td>
    <td><p><strong>Three-way matching</strong></p></td>
    <td><p><strong>Three-way matching</strong></p></td>
    </tr>
    <tr class="even">
    <td><p>MM01 – Wireless Mouse</p></td>
    <td><p>2</p></td>
    <td><p>40.00</p></td>
    <td><p>80.00</p></td>
    <td><p><strong>Two-way matching</strong></p></td>
    <td><p><strong>Three-way matching</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p>USB Drive</p></td>
    <td><p>200</p></td>
    <td><p>10.00</p></td>
    <td><p>2,000.00</p></td>
    <td><p><strong>Two-way matching</strong></p></td>
    <td><p><strong>Two-way matching</strong></p></td>
    </tr>
    </tbody>
    </table>


## Scenario

1.  The items arrive. Sammy, a worker in the receiving department of the Malaysia division of Fabrikam, is interrupted and does not post the product receipt immediately.

2.  April, the accounts payable coordinator at Fabrikam, enters and verifies the invoice that is submitted by Contoso. She verifies the following information:
    
      - For items that require three-way matching, the quantity on the invoice line matches the quantity that was received. The received quantity is indicated on the product receipt that is matched to the invoice.
    
      - For items that require two-way or three-way matching, the prices on the invoice line are within the tolerances that are defined in Microsoft Dynamics AX.
        
        This includes the following types of price matching:
        
          - Net unit price matching – The net unit price on the invoice line matches the net unit price on the purchase order line, within the tolerance percentage. In this example, the net unit price tolerance is +2%.
        
          - Price totals matching – The net amount on the invoice line matches the net amount on the purchase order line, within the tolerance percentage, amount, or percentage and amount. In this example, the price totals matching tolerance is +10%.

The paper invoice from Contoso contains the following information.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Quantity</p></th>
<th><p>Unit price</p></th>
<th><p>Net amount</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>PH2500 – Computer</p></td>
<td><p>2</p></td>
<td><p>2,500.00</p></td>
<td><p>5,000.00</p></td>
</tr>
<tr class="even">
<td><p>MM01 – Wireless Mouse</p></td>
<td><p>2</p></td>
<td><p>41.00</p></td>
<td><p>82.00</p></td>
</tr>
<tr class="odd">
<td><p>USB Drive</p></td>
<td><p>200</p></td>
<td><p>10.05</p></td>
<td><p>2,010.00</p></td>
</tr>
<tr class="even">
<td><p>Total invoice</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>7,092.00</p></td>
</tr>
</tbody>
</table>


In Microsoft Dynamics AX, the invoice line includes the following information.

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Item number</strong></p></th>
<th><p><strong>Quantity</strong></p></th>
<th><p><strong>Unit price</strong></p></th>
<th><p><strong>Line net amount</strong></p></th>
<th><p><strong>Matching policy</strong></p></th>
<th><p><strong>Product receipt quantity match</strong></p></th>
<th><p><strong>Price match</strong></p></th>
<th><p><strong>Price total match</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>PH2500 – Computer</p></td>
<td><p>2</p></td>
<td><p>2,500.00</p></td>
<td><p>5,000.00</p></td>
<td><p><strong>Three-way matching</strong></p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="even">
<td><p>MM01 – Wireless Mouse</p></td>
<td><p>2</p></td>
<td><p>41.00</p></td>
<td><p>82.00</p></td>
<td><p><strong>Three-way matching</strong></p></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><img src="images/Hh292596.WarnIcon(AX.60).gif" title="WarnIcon" alt="WarnIcon" /></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
<tr class="odd">
<td><p>USB Drive</p></td>
<td><p>200</p></td>
<td><p>10.05</p></td>
<td><p>2010.00</p></td>
<td><p><strong>Two-way matching</strong></p></td>
<td><p></p></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
<td><img src="images/Hh292596.CheckMark(AX.60).gif" title="Check mark" alt="Check mark" /></td>
</tr>
</tbody>
</table>


Note the following items:

  - For the PH2500 – Computer line, the **Product receipt quantity match** column has a warning icon because the invoice line is not matched to a product receipt.

  - For the MM01 – Wireless Mouse line, the **Product receipt quantity match** column has a warning icon because the invoice line is not matched to a product receipt. The **Unit price match** column has a warning icon because the 2% net unit price tolerance is exceeded.

  - For the USB Drive line, the **Product receipt quantity match** column is blank because two-way matching does not match invoice line and product receipt line quantities.

If approval is required for invoices to be posted with invoice matching discrepancies, the **Approve posting with matching discrepancies** check box in the **Invoice matching details** form must be selected before the invoice can be posted with price matching errors and quantity matching errors. If approval is not required, invoice processing can continue if there are no other posting errors.

## See also

[Invoice matching details (form)](https://technet.microsoft.com/library/hh209713\(v=ax.60\))

[Matching policy (form)](https://technet.microsoft.com/library/hh209508\(v=ax.60\))

[Vendor invoice (form)](https://technet.microsoft.com/library/hh209644\(v=ax.60\))

  


