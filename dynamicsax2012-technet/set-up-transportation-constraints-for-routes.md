---
title: Set up transportation constraints for routes
TOCTitle: Set up transportation constraints for routes
ms:assetid: fa72c254-84e6-42a8-9ab9-be176aeecd2f
ms:mtpsurl: https://technet.microsoft.com/library/Dn553214(v=AX.60)
ms:contentKeyID: 62200193
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- routes
- shipment
- shipping carrier
- constraints
- Forms.TMSConstraint
- item constraint
audience: Application User
ms.search.region: Global
---

# Set up transportation constraints for routes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to set up transportation constraints for items, shipments, or shipping carriers. The transportation coordinator selects a constraint action in the **Constraints** form based on which one of the following scenarios occur in the **Rate route workbench** form:

  - **Warn** – The warning message indicates that the route should not be assigned to the freight.

  - **Restrict** – This restricts the transportation coordinator from assigning a route to the freight.

For example, you can set a constraint on hazardous chemicals so that the item is not transported using a particular shipping carrier.

## Set up an item constraint

You can set up a constraint for an item using the item number or filter codes.

To set up an item constraint, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Routing** \> **Constraints**.

2.  In the **Item** area, click **New** to create an item constraint.

3.  Enter an identifier (ID) and a name for the item constraint.

4.  Optional: Select the site and warehouse in which this item constraint should be applied.

5.  In the **Item number** field, select the item for which you want to set a constraint.
    
    –or–
    
    In the code fields, select one or more filter codes to set the constraint for items that are assigned to the selected filter codes. For example, if you select the filter code for inflammable items, then the constraint is applied to all inflammable items. For more information, see Configure item filters and filter codes for warehouse transactions.

6.  In the rightmost pane, on the **Condition** FastTab, specify the conditions for the item constraint.

7.  In the **Constraint action** field, select either **Warn** or **Restrict** to trigger a warning message or restrict the transportation coordinator from assigning a route when the conditions for the item constraints are met in the **Rate route workbench** form.

## Set up a shipment constraint

To set up a shipment constraint, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Routing** \> **Constraints**.

2.  In the left pane, click **Shipment**.

3.  In the **Shipment** area, click **New** to create a shipment constraint.

4.  Enter an ID and name for the shipment constraint.

5.  Optional: Select the site and warehouse in which this shipment constraint should be applied.

6.  Select a customer or vendor account for the shipment for which you want to set a constraint.

7.  Enter the maximum and minimum weight of the shipment.

8.  In the rightmost pane, on the **Condition** FastTab, specify the conditions for the shipment constraint.

9.  In the **Constraint action** field, select either **Warn** or **Restrict** to trigger a warning message or restrict the transportation coordinator from assigning a route when the conditions for the shipment constraints are met in the **Rate route workbench** form.

## Set up a shipping carrier constraint

To set up a shipping carrier constraint, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Routing** \> **Constraints**.

2.  In the left pane, click **Shipping carrier**.

3.  In the **Shipping carrier** area, click **New** to create a shipping carrier constraint.

4.  Enter an ID and a name for the shipping carrier constraint.

5.  Optional: Select the site and warehouse in which this shipment carrier constraint should be applied.

6.  Select a shipping carrier and carrier service for which you want to set a constraint.
    

    > [!NOTE]
    > <P>If you select a shipping carrier, you must select a carrier service.</P>



7.  In the rightmost pane, on the **Condition** FastTab, specify the conditions for the shipping carrier constraint.

8.  In the **Constraint action** field, select either **Warn** or **Restrict** to trigger a warning message or restrict the transportation coordinator from assigning a route when the conditions for the shipping carrier constraints are met in the **Rate route workbench** form.

## Next step

[Set up a route plan and routing guide for freight transportation](set-up-a-route-plan-and-routing-guide-for-freight-transportation.md)

## Related tasks

[Set up a transportation mode and method for a shipping carrier](set-up-a-transportation-mode-and-method-for-a-shipping-carrier.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

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
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


