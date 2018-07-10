---
title: Create a purchase order
TOCTitle: Create a purchase order
ms:assetid: 713c05bd-fdcb-4d37-80ba-cdc09f7c782e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa571317(v=AX.60)
ms:contentKeyID: 37832507
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- purchase order
- purchase orders
- procurement
- purchase order creation
---

# Create a purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a purchase order that has all the information that you need to purchase specific products at a specific price or for a specific delivery date from a vendor.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order** to create a new purchase order.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. On the **Action Pane**, on the **Purchase order** tab, in the **New** group, click **Purchase order** to create a new purchase order.

2.  In the **Create purchase order** form, select a vendor account.
    
      - Click **Yes** to copy vendor information such as the address, delivery address, currency, invoice account number, and language to the purchase order.
    
      - Click **No** to create the new purchase order without copying previous vendor purchase information.

3.  On the **General** FastTab, in the **Purchase type** field, select the type of purchase order to create. For more information about order types, see [About purchase order types](about-purchase-order-types.md).

4.  Optionally, enter or modify the rest of the information in the **Create purchase order** form, and then click **OK**. The new purchase order is displayed.
    

    > [!NOTE]
    > <P>If a purchase agreement exists for the selected vendor, you can order against the purchase agreement. Purchase agreements are available in the <STRONG>Purchase agreement ID</STRONG> field. For more information, see <A href="create-a-purchase-release-order.md">Create a purchase release order</A>.</P>



5.  In the **Purchase order lines** grid, click **Add line** or press Ctrl+N to create a new purchase order line.

6.  At a minimum, on the purchase order line, specify an item or a procurement category, a purchase quantity, a unit of measure, and a unit price.

7.  On the **Line details** FastTab, on the **Delivery** tab, enter a delivery date in the **Delivery date** field. If the purchase order is based on a purchase agreement, the delivery date must be in the validity period of the associated purchase agreement line.

8.  If the purchase order is for a fixed asset, use the **Fixed assets** tab on the **Line details** FastTab to enter an existing fixed asset number. You can also create a new fixed asset here.

9.  Click **Add line** or press Ctrl+N to create additional lines for the purchase order.

> [!TIP]  
> <ul>
> <li><p>To create accounting distributions for a purchase order line, select the line. Then, on the <strong>Action Pane</strong>, on the <strong>Financials</strong> tab, click <strong>Distribute amounts</strong>. For more information, see <a href="create-accounting-distributions-for-purchase-orders.md">Create accounting distributions for purchase orders</a>.</p></li>
> <li><p>To view subledger journal lines, select the line. Then, on the <strong>Action Pane</strong>, on the <strong>Financials</strong> tab, click <strong>Subledger journal</strong>. For more information, see <a href="view-subledger-journals-for-purchase-orders.md">View subledger journals for purchase orders</a>.</p></li>
> <li><p>If you enable committed costs for purchase orders on the <strong>Cost control</strong> tab of the <strong>Project parameters</strong> form, and if you enable budget control for the project on the <strong>Setup</strong> tab of the <strong>Project details</strong> form, the purchase order is subject to budget control for the project. If workflow is implemented, the project budget is checked when each line is saved, but it is not reduced until the purchase order is approved.</p></li>
> <li><p>If you turn on budget control, and you select <strong>Purchase orders</strong> and <strong>Enable budget control for line item on entry</strong> in the <strong>Select source documents</strong> area of the <strong>Budget control configuration</strong> form, the first column in the <strong>Purchase order lines</strong> grid in the <strong>Purchase order</strong> form displays a budget check icon. A red X indicates that the budget check failed, a yellow triangle indicates that the budget check passed with warnings, and a green check mark indicates that the budget check passed. This column is blank if budget checking is not performed. Budget check results can be affected by settings for project budget control, over-budget permissions, and other budget control parameters and settings. For more information, see <a href="about-budget-control.md">About budget control</a>.</p></li>
> <li><p>To display inventory dimensions on the line in the <strong>Purchase order lines</strong> grid, click <strong>Purchase order line</strong> &gt; <strong>Dimensions</strong>.</p></li>
> <li><p>To validate a purchase order with a vendor before the purchase order is confirmed, on the <strong>Action Pane</strong>, under <strong>Purchase</strong>, in the <strong>Generate</strong> group, click <strong>Purchase inquiry</strong>.</p></li>
> <li><p>To reference reserved budget, on the <strong>Line details</strong> FastTab, under <strong>General budget reservations</strong>, provide document and line numbers for a general budget reservation. You can click <strong>Advanced selection options</strong> to search for more reservations.</p>

> [!NOTE]  
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>

<p>For a project purchase order, the budget reservation line must reference a project. For a non-project purchase order, the budget reservation line cannot reference a project. For more information, see <a href="use-project-accounting-with-general-budget-reservations-public-sector.md">Use project accounting with general budget reservations (Public sector)</a>.</p>
<p>Purchase order lines that reference a general budget reservation cannot be edited. This restriction exists to prevent potential accounting errors if changes are made to the purchase order accounting distributions. However, you can add new lines to the purchase order as a way to make changes.</p>
<p>When you specify a general budget reservation on a purchase order line, all project details and project distributions are copied. Because of the budget reservation reference, some of the project details are not editable. For more information, see <a href="create-a-general-budget-reservation-public-sector.md">Create a general budget reservation (Public sector)</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## See also

[About purchase agreements](about-purchase-agreements.md)

[Create accounting distributions for purchase orders](create-accounting-distributions-for-purchase-orders.md)

[View the status of open purchase orders](view-the-status-of-open-purchase-orders.md)

[Confirming PO codes (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208558\(v=ax.60\))

[Create a purchase inquiry](create-a-purchase-inquiry.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

