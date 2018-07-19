---
title: Set up Accounts payable invoice matching
TOCTitle: Set up Accounts payable invoice matching
ms:assetid: eead4cc7-9836-4324-8a91-3d14945925de
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243265(v=AX.60)
ms:contentKeyID: 36059911
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- purchase order
- accounts
- AP
- payable
- charges
- 2 way
- 3 way
- 2-way
- 3-way
- two way
- invoice matching
- three-way
- three way
- two-way
- invoice match
- price match
- price totals
- price matching
- invoice totals
- quantity match
- product receipt
- quantity matching
audience: Application User
ms.search.region: Global
---

# Set up Accounts payable invoice matching 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the following procedures to set up invoice matching for Accounts payable. For more information, and for examples, see [About Accounts payable invoice matching](about-accounts-payable-invoice-matching.md).


> [!NOTE]
> <P>Other forms of invoice validation can be completed by using vendor invoice policies.</P>



## Set up Accounts payable parameters for invoice matching

Before you begin, make sure that the **Invoice matching** configuration key is selected. If your legal entity tracks expenses, such as freight, by using charges, make sure that the **Charges** configuration key is selected.

1.  Switch to the legal entity that you are setting up invoice matching for.

2.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

3.  Click **Invoice validation**, and then select the **Enable invoice matching validation** check box.

4.  In the **Post invoice with discrepancies** field, select whether approval is required before an invoice that contains discrepancies for invoice matching can be posted.

5.  Optional: To match actual invoice totals with expected totals, based on information on the purchase order, select the **Match invoice totals** check box.
    
    1.  In the **Display invoice totals match icon** field, select whether an icon is displayed if a discrepancy for invoice matching exceeds the tolerance. You can select to display the icon when a positive discrepancy exceeds the tolerance, or when either a positive or a negative discrepancy exceeds the tolerance.
        
        For example, the tolerance is 5 percent, and the total invoice amount on the purchase order is 100.00. Therefore, a price match icon is displayed if the total invoice amount on the invoice exceeds 105.00. If you select **If greater than or less than tolerance**, the icon is also displayed if the invoice amount is less than 95.00.
    
    2.  In the **Invoice totals tolerance percentage** field, enter the maximum percentage variance that is acceptable.
        
        For information about how to override the invoice totals tolerance percentage for a specific vendor, see [Define invoice totals matching tolerances for vendors](define-invoice-totals-matching-tolerances-for-vendors.md).

6.  Optional: To match price or price and quantity information for line items on invoices, follow these steps:
    
    1.  In the **Line matching policy** field, select a value to be used as the default policy for the legal entity that you are working with.
    
    2.  To allow a different level of matching to be applied for an item, vendor, vendor and item combination, or purchase order line, select a value in the **Allow matching policy override** field.
        
        For information about how to override the legal entity line matching policy for a specific vendor, item, or vendor and item combination, see [Matching policy (form)](https://technet.microsoft.com/en-us/library/hh209508\(v=ax.60\)). For information about how to override the legal entity line matching policy for a specific purchase order, see [Purchase order (form)](https://technet.microsoft.com/en-us/library/aa557983\(v=ax.60\)).
    
    3.  In the **Display unit price match icon** field, select when an icon is displayed if a discrepancy for invoice matching exceeds the tolerance for the net unit price. The icon can be displayed when a positive discrepancy exceeds the tolerance, or when either a positive or a negative discrepancy exceeds the tolerance.
        
        For example, the tolerance is 5 percent, and the unit price on the purchase order is 10.00. Therefore, a price match icon is displayed if the net unit price on the invoice exceeds 10.50. If you select **If greater than or less than tolerance**, the icon is also displayed if the net unit price on the invoice is less than 9.50.

7.  Optional: To match price totals for line items on invoices, select a value in the **Match price totals** field.
    
    1.  Enter the price totals tolerance percentage, amount, or percentage and amount.
    
    2.  In the **Display price total match icon** field, select when an icon is displayed if a discrepancy for invoice matching exceeds the tolerance. The icon can be displayed when a positive discrepancy exceeds the tolerance, or when either a positive or a negative discrepancy exceeds the tolerance.
        
        For example, the tolerance is 5 percent, and the line price total on the purchase order is 10.00. Therefore, a price match icon is displayed if the line price total on the invoice exceeds 10.50. If you select **If greater than or less than tolerance**, the icon is also displayed if the line price total on the invoice is less than 9.50.

8.  Optional: To match actual charges with expected charges, based on information on the purchase order, select the **Match charges** check box.
    
    1.  In the **Display charges match icon** field, select when an icon is displayed if a discrepancy for invoice matching exceeds the tolerance. The icon can be displayed when a positive discrepancy exceeds the tolerance, or when either a positive or a negative discrepancy exceeds the tolerance.
        
        For example, the tolerance is 5 percent, and the expected charge, based on the purchase order, is 10.00. Therefore, a charges match icon is displayed if the actual charge exceeds 10.50. If you select **If greater than or less than tolerance**, the icon is also displayed if the charge is less than 9.50.
    
    2.  In the **Charges tolerance percentage** field, enter the maximum percentage variance that is acceptable.
        
        For information about how to override this percentage for a specific charges code, see [Define matching tolerances for charges codes](define-matching-tolerances-for-charges-codes.md).

## Set up item model groups for invoice matching

Price discrepancies between the price of an item on a packing slip and the price on a corresponding invoice can affect the recorded inventory cost of the item. To help make sure that inventory costs are recorded correctly, you can require that packing slip information be posted before invoice information can be posted.

1.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Item model groups**.

2.  Select an item model group.

3.  On the **Setup** FastTab, select the **Receiving requirements** check box.

4.  Select the **Deduction requirements** check box.

5.  Repeat steps 2 through 4 for each item model group to use invoice matching for.

## Set up information about item price tolerances

If you use a line matching policy of **Two-way matching** or **Three-way matching**, complete this procedure.

You can set up information about price tolerances for all items in your legal entity, for item price tolerance groups, or for individual items. To set up item price tolerances by group, you must first create item price tolerance groups. You can then assign each item to the appropriate group. For example, you can set up three item price tolerance groups: High, Medium, and Low.

1.  Click **Inventory management** \> **Setup** \> **Price/discount** \> **Item price tolerance groups**.

2.  Click **New** to create an item price tolerance group.

3.  Enter an identifier and a name for the item price tolerance group.

4.  Repeat steps 2 and 3 for each item price tolerance group.

5.  Click **Product information management** \> **Common** \> **Released products**.

6.  Select an item. On the **Action Pane**, click **Edit**.

7.  Click **Grid View** at the bottom of the form or press CTRL+SHIFT+G to view all items, and then select an item in the list.

8.  On the **Purchase** FastTab, select an item price tolerance group.

9.  Repeat steps 7 and 8 for each item.

## Set up information about vendor price tolerances

If you use a line matching policy of **Two-way matching** or **Three-way matching**, complete this procedure.

You can set up information about price tolerances for all vendors in your legal entity, for vendor price tolerance groups, or for individual vendors. To set up vendor price tolerances by group, you must first create vendor price tolerance groups. You can then assign each vendor to the appropriate group. For example, you can set up two vendor price tolerance groups: 10 percent and 5 percent.

1.  Click **Accounts payable** \> **Setup** \> **Vendors** \> **Vendor price tolerance groups**.

2.  Click **New** to create a vendor price tolerance group.

3.  Enter an identifier and a name for the vendor price tolerance group.

4.  Repeat steps 2 and 3 for each vendor price tolerance group.

5.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

6.  Select a vendor account. On the **Action Pane**, click **Edit**.

7.  On the **Invoice and delivery** FastTab, select a vendor price tolerance group.

8.  Repeat steps 6 and 7 for each vendor.

## Set up price tolerance percentages

If you use a line matching policy of **Two-way matching** or **Three-way matching**, complete this procedure.

You can set up price tolerance percentages for your legal entity, items, and vendors. When vendor invoices are compared with the information on purchase orders, the applicable price tolerance percentage is searched for. The following table shows the search order.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item code</p></th>
<th><p>Account code</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Table</p></td>
<td><p>Table</p></td>
</tr>
<tr class="even">
<td><p>Table</p></td>
<td><p>Group</p></td>
</tr>
<tr class="odd">
<td><p>Table</p></td>
<td><p>All</p></td>
</tr>
<tr class="even">
<td><p>Group</p></td>
<td><p>Table</p></td>
</tr>
<tr class="odd">
<td><p>Group</p></td>
<td><p>Group</p></td>
</tr>
<tr class="even">
<td><p>Group</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>All</p></td>
<td><p>Table</p></td>
</tr>
<tr class="even">
<td><p>All</p></td>
<td><p>Group</p></td>
</tr>
<tr class="odd">
<td><p>All</p></td>
<td><p>All</p></td>
</tr>
</tbody>
</table>


The default legal entity price tolerance is 0 percent, and this price tolerance is applied to all items and all accounts (All, All). You cannot delete the record for the default legal entity price tolerance.

For example, you can set up the following records for price tolerance percentage.

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
<th><p>Item code</p></th>
<th><p>Item relation</p></th>
<th><p>Account code</p></th>
<th><p>Account relation</p></th>
<th><p>Price tolerance percentage</p></th>
<th><p>Notes</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>All</p></td>
<td><p></p></td>
<td><p>All</p></td>
<td><p></p></td>
<td><p>1%</p></td>
<td><p>This percentage applies to all items and all vendors, unless one of the other scenarios applies. This is the legal entity price tolerance percentage.</p></td>
</tr>
<tr class="even">
<td><p>Table</p></td>
<td><p>Battery</p></td>
<td><p>All</p></td>
<td><p></p></td>
<td><p>1%</p></td>
<td><p>This percentage applies to the Battery item from all vendors.</p></td>
</tr>
<tr class="odd">
<td><p>Group</p></td>
<td><p>Low</p></td>
<td><p>All</p></td>
<td><p></p></td>
<td><p>2%</p></td>
<td><p>This percentage applies to all items that are assigned to the Low item price tolerance group, and to All vendors.</p></td>
</tr>
<tr class="even">
<td><p>Group</p></td>
<td><p>Medium</p></td>
<td><p>All</p></td>
<td><p></p></td>
<td><p>6%</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Group</p></td>
<td><p>High</p></td>
<td><p>All</p></td>
<td><p></p></td>
<td><p>15%</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>All</p></td>
<td><p></p></td>
<td><p>Group</p></td>
<td><p>5 percent</p></td>
<td><p>5%</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>All</p></td>
<td><p></p></td>
<td><p>Group</p></td>
<td><p>10 percent</p></td>
<td><p>10%</p></td>
<td><p>This percentage applies to vendors who are assigned to the 10 percent group, and to All items.</p></td>
</tr>
</tbody>
</table>


1.  Click **Accounts payable** \> **Setup** \> **Invoice matching** \> **Price tolerances**.

2.  Click **New** to create a price tolerance percentage.

3.  Enter information about the item and vendor combination that the price tolerance applies to, and the price tolerance percentage.
    

    > [!NOTE]
    > <P>By default, negative price discrepancies are allowed. However, you cannot enter a negative number as the price tolerance percentage. To track negative price tolerance percentages, select <STRONG>If greater than or less than tolerance</STRONG> in the <STRONG>Display unit price match icon</STRONG> field in the <STRONG>Accounts payable parameters</STRONG> form. Then enter price tolerance percentages in the <STRONG>Price tolerances</STRONG> form.</P>



4.  Repeat steps 2 and 3 for each price tolerance percentage.

## See also

[Key tasks: Vendor invoices](key-tasks-vendor-invoices.md)

[Account for vendor invoice variance due to charges](account-for-vendor-invoice-variance-due-to-charges.md)

[Record the receipt of vendor invoices and match against received quantities](record-the-receipt-of-vendor-invoices-and-match-against-received-quantities.md)

[Resolve net unit price invoice matching discrepancies](resolve-net-unit-price-invoice-matching-discrepancies.md)

[Accounts payable parameters (form)](https://technet.microsoft.com/en-us/library/aa596348\(v=ax.60\))

[Item model groups (form)](https://technet.microsoft.com/en-us/library/aa577092\(v=ax.60\))

[Item price tolerance groups (form)](https://technet.microsoft.com/en-us/library/hh209702\(v=ax.60\))

[Released product details (form)](https://technet.microsoft.com/en-us/library/aa615563\(v=ax.60\))

[Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\))

[Vendor price tolerance groups (form)](https://technet.microsoft.com/en-us/library/hh242256\(v=ax.60\))

[Price tolerances (form)](https://technet.microsoft.com/en-us/library/hh209247\(v=ax.60\))

[About invoice matching and intercompany purchase orders](about-invoice-matching-and-intercompany-purchase-orders.md)

  


