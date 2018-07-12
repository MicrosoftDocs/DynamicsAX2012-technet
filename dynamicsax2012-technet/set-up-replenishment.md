---
title: Set up replenishment
TOCTitle: Set up replenishment
ms:assetid: 17f53aca-b238-4838-a67f-781366c9e34e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn750873(v=AX.60)
ms:contentKeyID: 62369568
ms.date: 06/14/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.WHSReplenishmentTemplates
- Forms.WHSRequestType
audience: Application User
ms.search.region: Global
---

# Set up replenishment 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up replenishment for locations in a warehouse. You can set up the following replenishment strategies:

  - Replenishment based on demand – This strategy creates replenishment work for outbound orders or loads if inventory is not available when the work is created by the wave. For example, if the quantity that is required for a sales order is not available when a wave is processed, replenishment work can be created.
    

    > [!NOTE]
    > <P>If you have Microsoft Dynamics AX 2012 R3 Cumulative Update 9 and KB3068847 installed, when wave demand replenishment is triggered in the warehouse, it will first try to find existing demand replenishment work for items with same dimensions and&nbsp;location area, where the work is either open or in progress and has unreserved quantities. It will then deduct the demanded quantity from the existing demand replenishment fulfilling these criteria. If the unreserved quantities on an existing demand replenishment work item are not enough to satisfy the new demand, new demand replenishment work will be created.</P>



  - Replenishment based on minimum and maximum quantities – This strategy uses minimum and maximum stocking limits to determine when to replenish locations. The item and location criteria define the inventory that is evaluated for replenishment.

You define replenishment strategies by setting up replenishment templates. A replenishment template is a set of rules that control when and how inventory is replenished. If you create multiple replenishment templates, you can select when and how often groups of items and locations are evaluated for replenishment.

Depending on the strategy that you want to use, you can set up replenishment to be run manually, or as a batch job that can be scheduled.


> [!NOTE]
> <P>If you have Microsoft Dynamics AX 2012 R3 Cumulative Update 9 installed, there is an <STRONG>Allow wave demand to use unreserved quantities</STRONG> checkbox on the <STRONG>Replenishment template</STRONG> form. This should be enabled if you want to allow demand replenishment to deduct unreserved quantities from work generated from the selected replenishment template. This checkbox needs to be set for each existing replenishment template in order to enable demand replenishment templates to use this logic. When demand replenishment is triggered in the warehouse, it will deduct the demand from existing replenishment work with unreserved quantities, if the work originates from replenishment templates with the <STRONG>Allow wave demand to use unreserved quantities</STRONG> option enabled.</P>



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
<td><p><strong>Replenishment templates</strong></p></td>
<td><p>Define the units of measurement for the inventory to replenish. For more information, see <a href="https://technet.microsoft.com/en-us/library/hh209233(v=ax.60)">Units (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Request types</strong></p></td>
<td><p>Optional: Set up request types to connect a replenishment template with a specific location directive. This can improve system performance when work is created for replenishment.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Fixed locations</strong></p></td>
<td><p>Optional: Locations that do not contain a quantity of an item will not be replenished. If you want to replenish locations that are empty, you must use fixed locations for items. You can use the replenishment template to specify that you want to replenish empty fixed locations for an item or replenish only fixed locations.</p>
<p>For more information, see the “Optional: Assign a fixed location to a product or product variant” section in <a href="set-up-parameters-to-create-a-warehouse-location.md">Set up parameters to create a warehouse location</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Work templates</strong></p></td>
<td><p>Set up a work class to control who can perform replenishment work.</p></td>
</tr>
</tbody>
</table>


## Define how to create the work to replenish a location

You can set up one or more work templates to specify how to create the work to replenish a location. After you set up the work template, you can assign it to the replenishment template. You can use the same work template for replenishment based on minimum and maximum values and demand-based replenishment.

To set up a work template to create work for replenishment, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Work** \> **Work templates**.

2.  In the **Work order type** field, select **Replenishment**.

3.  The remaining steps for this procedure also apply to other work templates. For more information, see [Create a work template](create-a-work-template.md).

## Specify the location to pick the items to replenish with, and where to put them

You must set up location directives to specify the locations from which to pick the items to replenish with, and where to put them.


> [!NOTE]
> <P>If you set up a location directive for a replenishment strategy that is based on minimum and maximum values, on the <STRONG>Location directives</STRONG> FastTab, you must only create lines for picking. Demand-based picking strategies require lines for both picking and put away.</P>



To specify locations for picking replenishment items and putting them in the specified locations, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Location directives**.

2.  In the **Work order type** field, select **Replenishment**.

3.  The remaining steps for this procedure also apply to other location directives. For more information, see [Create a location directive](create-a-location-directive.md).

## Set up a wave template for replenishment

If you want to automatically create replenishment work for a wave demand replenishment strategy, you must set up a wave template for replenishment. The wave template must include the **replenish** wave method in the sequence of steps. If you want to automatically release the replenishment wave to create replenishment work, select the **Automate replenishment work** check box.

To set up a wave template for replenishment, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Waves** \> **Wave templates**.

2.  Click **New** to create a new wave template.

3.  In the **Wave template type** field, select **Shipping**.

4.  The remaining steps for this procedure also apply to other wave templates. For more information, see [Create a wave template](create-a-wave-template.md).

## Set up a replenishment template to replenish based on demand

You can set up a replenishment template so that replenishment work is created if a quantity in a location cannot meet the demand for a wave or load. The quantities are evaluated for the item and location when the work for the wave or load is created.

The key difference between wave demand and load demand is that load demand replenishment cannot be automated. Wave demand can be run by using a batch job, but it can also be automated through the wave template. For more information, see [Create a wave template](create-a-wave-template.md).


> [!NOTE]
> <P>Some fields in the <STRONG>Replenishment templates</STRONG> form are used only for replenishment that is based on minimum and maximum quantities. These fields are not available on replenishment templates for wave demand or load demand. For example, you do not need to define minimum and maximum stocking limits, and the demand increment is always set to round up.</P>



To set up a replenishment template for wave demand or load demand, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Replenishment** \> **Replenishment templates**.

2.  Click **New** to create a new template.

3.  On the **Replenishment Template Details** FastTab, in the **Replenish template** and **Description** fields, enter a name and a description for the template.

4.  In the **Replenishment type** field, select **Wave demand** or **Load demand**.

5.  To use a specific wave template to create the replenishment work, in the **Wave step code** field, enter a code for the wave method that will be included in the wave template. If you specify a wave step code, only the related wave template is used.

6.  On the **Replenishment Template Lines** FastTab, click **New**.

7.  In the **Sequence number** field, enter a number to define the position of the line in the sequence of lines.

8.  In the **Description** field, enter a description of the criteria represented in the line.

9.  In the **Request type** field, select the request type to connect the replenishment template to the location directive that you want to use.

10. In the **Replenishment unit** field, select the unit of measure to use for the replenishment.

11. If you are setting up a template for a load demand, in the **Applicable demand** field, select one of the following options.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Full quantity</strong></p></td>
    <td><p>Add the full quantity of the load line to the demand.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Loose quantity</strong></p></td>
    <td><p>Add any quantity that is not evenly divisible by the load line’s packing quantity to the demand. For example, if the quantity on the load line is 125, and the packing quantity is 50, the quantity of 25 is added to the demand.</p></td>
    </tr>
    </tbody>
    </table>
    

    > [!NOTE]
    > <P>The <STRONG>Applicable demand</STRONG> field is used only for replenishment templates for load demand. For wave demand templates, the full quantity of the load line is always added to the demand.</P>



12. Optional: If you want to use a specific work template to create the work, in the **Work template code** field, select the work template.

13. Optional: To use a specific location directive to determine the location to replenish and where to pick the replenishment items, in the **Directive code** field, select the directive code that is associated with the location directive.
    

    > [!NOTE]
    > <P>The <STRONG>Select locations</STRONG> query is not used for replenishment for wave demand or load demand.</P>



14. Optional: To apply this replenishment to one or more selected items, click **Item selection**, and then specify the items in the query criteria.
    

    > [!NOTE]
    > <P>If you have Microsoft Dynamics AX 2012 R3 Cumulative Update 8 installed, the <STRONG>Item selection</STRONG> button has been renamed to <STRONG>Select products</STRONG>. Additionally, a <STRONG>Select product variants</STRONG> query is available, which functions like the <STRONG>Item selection</STRONG> query. These queries allow you to apply the replenishment template to one or more selected products or product variants. You cannot apply the same replenishment template line to both products and product variants. Therefore, in the <STRONG>Product query mode</STRONG> field, you must select the query mode that you want to use. When you select a query mode, the button for the corresponding query is available. All other aspects of replenishment are the same.</P>



15. Optional: For load demand and minimum and maximum value replenishment, you can apply this replenishment template to one or more selected warehouses and locations by clicking **Select locations** to set up the **Location %1** query.

## Set up a replenishment template to replenish based on minimum and maximum stock limits

You can set up a replenishment template that will replenish stock when the quantity in the location is less than the minimum amount. You can also specify the maximum value to replenish in the location. In the template, create one line for each item and location. When you run replenishment by using the batch job, Microsoft Dynamics AX will evaluate whether replenishment is required in the sequence in which the lines are organized. For more information, see [Run replenishment manually](run-replenishment-manually.md).


> [!NOTE]
> <P>We recommend that you manually verify that the maximum value defined for replenishment in the replenishment template does not exceed the maximum stock quantity defined for locations in the <STRONG>Location stocking limits</STRONG> form. To view location stocking limits, go to <STRONG>Warehouse management</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Warehouse setup</STRONG> &gt; <STRONG>Location stocking limits</STRONG>.</P>



To set up replenishment based on minimum and maximum stock limits, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Replenishment** \> **Replenishment templates**.

2.  Click **New** to create a new template.

3.  On the **Replenishment Template Details** FastTab, in the **Replenish template** and **Description** fields, enter a name and a description for the template.

4.  In the **Replenishment type** field, select **Minimum or maximum**.

5.  On the **Replenishment Template Lines** FastTab, click **New**.

6.  In the **Sequence number** field, enter a number to define the position of the line in the sequence. The number must be larger than zero.

7.  In the **Description** field, enter a description of the criteria in the line.

8.  In the **Minimum quantity** and **Maximum quantity** fields, specify a range of quantities to replenish.

9.  In the **Unit** field, select the unit of measure for the item.

10. In the **Request type** field, select the request type to connect the replenishment template to the location directive that you want to use.

11. In the **Replenishment unit** field, select the unit of measure to use for the replenishment.

12. In the **Demand increment** field, select the principle to use when rounding quantities. The replenishment quantity will be rounded up or down to the nearest increment based on the selection in the **Replenishment unit** field.
    

    > [!NOTE]
    > <P>If you round up, and the replenishment unit is larger than the item’s unit of measure, the quantity added to the demand can exceed the maximum. For example, an item is packaged as 10 per case, there are 8 in a location, and the maximum stocking limit is 100. The item will be replenished with 10 cases, for a total quantity of 108 in the location.</P>



13. Optional: If you want to use a specific work template to create the work, in the **Work template code** field, select the work template.

14. In the **Directive code** field, select the directive code that is associated with the location directive that will determine where to pick the replenishment items from.

15. To set up queries that will determine the item and location to replenish, do the following:
    
    1.  Click **Item selection**, and then set up the **Item %1** query.
    
    2.  Click **Select locations**, and then set up the **Location %1** query.

16. Optional: If you have specified fixed locations for the items, you can use the following options:
    
      - **Evaluate empty fixed locations** – Select this check box to replenish fixed locations for items when they are empty. Otherwise, only the locations where there is a quantity on hand will be replenished.
    
      - **Replenish only fixed locations** – Select this check box to replenish only fixed locations for items. Locations that are not specified as fixed locations for the items will not be replenished.  
        
        **Example**
        
        The following example shows fixed locations and non-fixed locations for items in a warehouse. The locations are either empty or contain a quantity.
        
        ![Replenishing fixed locations](images/Dn750873.WHSReplenishmentFixedLocations(AX.60).png "Replenishing fixed locations")
        
          
        
        The following table shows the locations that will be replenished, depending on whether the **Evaluate empty fixed locations** and **Replenish only fixed locations** check boxes are selected.
        
        <table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <td colspan="2"> <p></p> <p></p> </td>
    <td colspan="2"> <p> <strong>Replenish only fixed locations</strong> </p> </td>
  </tr>
  <tr>
    <td rowspan="3"> <p> <strong>Evaluate empty fixed locations</strong> </p> </td>
    <td> <p></p> </td>
    <td> <p>
   
	 Not selected
  </p> </td>
    <td> <p>
   
	 Selected
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Not selected
  </p> </td>
    <td> <p>
   
	 Location 2, Location 3
  </p> </td>
    <td> <p>
   
	 Location 3
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Selected
  </p> </td>
    <td> <p>
   
	 Location 1, Location 2, Location 3
  </p> </td>
    <td> <p>
   
	 Location 1, Location 3
  </p> </td>
  </tr>
</table>


## Related tasks

[Create a work template](create-a-work-template.md)

[Create a location directive](create-a-location-directive.md)

[Create a wave template](create-a-wave-template.md)

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


## See also

[Run replenishment manually](run-replenishment-manually.md)

  


