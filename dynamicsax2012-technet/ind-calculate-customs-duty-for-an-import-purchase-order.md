---
title: (IND) Calculate customs duty for an import purchase order
TOCTitle: (IND) Calculate customs duty for an import purchase order
ms:assetid: 87d074bf-6b5a-411f-8bcf-c4ec7cc4658f
ms:mtpsurl: https://technet.microsoft.com/library/JJ677992(v=AX.60)
ms:contentKeyID: 49385955
author: tonyafehr
ms.date: 11/17/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.PurchTableListPage
- Forms.TaxTmpWorkTrans
- customs duty
- excise amount
audience: Application User
ms.search.region: India
---

# (IND) Calculate customs duty for an import purchase order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create an import purchase order and add import landing charges, you can specify the currency that is used for the charges. You can calculate the charges in the company’s currency, the transaction currency, or the vendor’s currency. If you select a currency other than the company currency, when you confirm the import order, the applicable customs exchange rate is used to convert the charges to the company currency.

The exchange rate that you define for import transactions is used to calculate the assessable value and customs duty charges for import orders. For more information about how to set up customs exchange rates for import orders, see [Currency exchange rates (form)](https://technet.microsoft.com/library/hh209477\(v=ax.60\)).

The default percentage that is used to calculate the customs landing charges for import orders is set up in the **Accounts payable parameters** form. For more information about how to set up landing charges, see [(IND) Accounts payable parameters (modified form)](https://technet.microsoft.com/library/jj664793\(v=ax.60\)).

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R3 with cumulative update 8 (CU8)</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: India</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ol>
<li><p>In the <strong>General ledger parameters</strong> form, on the <strong>Sales tax</strong> pane, in the <strong>Apply India taxes</strong> field group, select the <strong>Excise</strong> check box and the <strong>Customs</strong> check box. For more information, see <a href="https://technet.microsoft.com/library/jj677901(v=ax.60)">(IND) General ledger parameters (modified form)</a>.</p></li>
<li><p>In the <strong>Exchange rate types</strong> form, set up the exchange rate types that will be used for the tax calculation. For more information, see <a href="https://technet.microsoft.com/library/hh242857(v=ax.60)">Exchange rate types (form)</a>.</p></li>
<li><p>In the <strong>Released product details</strong> form, on the <strong>General</strong> FastTab, in the <strong>Excise</strong> field group, select the <strong>Excise record type</strong> for the product. For more information, see <a href="https://technet.microsoft.com/library/aa615563(v=ax.60)">Released product details (form)</a>.</p></li>
</ol></td>
</tr>
</tbody>
</table>


## Add landing charges and calculate customs duty

Use the following procedure to add landing charges and calculate customs duty for an import order.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Create an import purchase order in a foreign currency for a foreign vendor. For more information, see [(IND) Create import purchase orders](ind-create-import-purchase-orders.md).

2.  Optional: In the purchase order line, you can change the value in the **Assessable value in the accounting currency** field. The assessable value is updated in the bill of entry lines and vendor invoice lines. Based on the bill of entry date and the defined currency exchange rates, the assessable value and customs duty are calculated, and can be modified.

3.  On the **Action Pane**, on the **Purchase** tab, click **Sales tax**.

4.  On the **Adjustment** tab, in the **Adjust sales tax** field, select **Detail**. In the **Actual sales tax amount in customs currency** field, you can adjust the calculated customs duty that is displayed in the **Calculated sales tax amount in Customs currency.** field. Click **Apply**, and then close the **Sales tax transactions** form.

5.  In the **Charges** group, click **Maintain charges**.

6.  In the **Charges transactions** form, enter information about the assessable value and landing charges for the purchase order line. For more information, see [Charges transactions (form)](https://technet.microsoft.com/library/aa633876\(v=ax.60\)).

7.  Close the **Charges transactions** form.

8.  In the **Purchase order** form, on the **Action Pane**, on the **Purchase** tab, in the **Generate** group, click **Confirm**.

The landing charges and customs duty for the import order lines are automatically calculated and posted for the products in the import purchase order.

## See also

[(IND) Create a purchase order and post charges](ind-create-a-purchase-order-and-post-charges.md)

  


