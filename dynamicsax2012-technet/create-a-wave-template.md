---
title: Create a wave template
TOCTitle: Create a wave template
ms:assetid: 8928feb2-0584-47ec-8d34-1bb8359be5ea
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553177(v=AX.60)
ms:contentKeyID: 62200112
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- picking
- wave
- pick
- Forms.WHSWaveTemplateTable
- Forms.WHSPostMethod
- Forms.WHSWaveAttributes
- Forms.WHSWaveFilterTable
- outbound
- wave template
---

# Create a wave template 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up the criteria that determine whether waves are processed manually or automatically, and the work that is generated for a warehouse when a wave is processed. You specify the criteria by setting up wave templates and queries that match a wave with released lines in sales orders, production orders, and kanbans.

## Settings for wave templates

When you set up a wave template, you specify the following:

  - The site and warehouse that the template will create work for.

  - The sequence in which the templates are matched to released lines on sales orders, production orders, and kanbans. When a line on a sales order, production order, or kanban is released to the warehouse or to production, Microsoft Dynamics AX 2012 R3 applies the first wave template that the line meets the criteria for. We recommend that you put the template with the most specific criteria at the top of the list. The broader the criteria, the more likely it is for a line to meet the criteria, which could lead to lines being assigned to the wrong wave.

  - The wave methods that perform the actions that are created by the template, such creating or distributing work for each type of wave template. These actions are also referred to as wave steps. Wave methods are predefined for each type of wave template, and are displayed in the **Selected methods** list on the **Methods** FastTab. You cannot remove the predefined wave methods, however, you can rearrange the order of the methods and add additional methods. For example, if you’re creating a wave template for shipping, you can add methods for replenishment and containerization.
    
    Wave containerization can be added to a sequence of wave methods to define the containerization of the lines processed in a wave template.
    

    > [!NOTE]
    > <P>If needed, a developer can create additional methods and add them to the AOS. You can view the full list of methods in the <STRONG>Wave process methods</STRONG> form.</P>



  - The wave attributes to use for the wave template. Wave attributes are useful for assigning additional criteria, such as a specific customer name, to a wave template. You create these attributes in the **Wave attributes** form.

Some settings represent strategic decisions for wave processing, as follows:

  - If the template is used for shipping items for sales orders and transfer orders, or used for moving items to production for production orders or kanbans.

  - If a wave is processed manually or automatically, as follows:
    
      - Manual processing – The line is added to a wave and the inventory is reserved, however, you must click **Process** on the **All waves** list page to create the picking work for the order.
    
      - Automatic processing – You can fully or partially automate wave processing. If you fully-automate wave processing, a wave is created that includes the line from the sales order, production order, or kanban when a sales order, production order, or kanban is created. The items are deducted from on-hand inventory and the picking work is created. If you partially automate wave processing, you can specify values that will trigger wave processing. For example, you can specify a maximum weight for shipments that will trigger wave processing when the total weight of the lines in the wave reaches the value.

  - If you assign shipments to an open wave. For example, if you promise customers that an order placed by 12:00 PM will ship within 24 hours, you can set up the wave template to automatically assign order lines to an open wave until 12:00 PM. At that time the wave is automatically processed.

When a wave is processed, the picking work that is created is based on the work template and the location directive that is specified for the warehouse. The work template specifies how the picking work is created, and the location directive specifies the pick and put locations.

## Create a wave template

To set up a wave template, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Waves** \> **Wave templates**.

2.  Click **New** to create a new wave template.

3.  In the **Wave template type** field, select one of the following options.
    
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
    <td><p><strong>Shipping</strong></p></td>
    <td><p>Use the wave template for shipping items for sales orders and transfer orders.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Production orders</strong></p></td>
    <td><p>Use the wave template to move items for production orders.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Kanban</strong></p></td>
    <td><p>Use the wave template to move items for kanban orders.</p></td>
    </tr>
    </tbody>
    </table>


4.  In the **Wave template name** and **Wave template description** fields, enter a name and a description for the wave template.
    

    > [!NOTE]
    > <P>If more than one template is created for a warehouse, the number in the <STRONG>Wave template sequence</STRONG> field indicates the position of the template in the sequence in which the templates are applied when the template’s criteria is met. You can click <STRONG>Move up</STRONG> or <STRONG>Move down</STRONG> to rearrange the sequence of templates.</P>



5.  In the **Site** and **Warehouse** fields, select the site and warehouse that the wave template will create waves and picking work for.

6.  Optional: To automate wave processing, select the following.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Automate wave creation</strong></p></td>
    <td><p>Select this check box to automatically create a wave when a sales order, production order, or kanban is released to the warehouse.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Process wave at release to warehouse</strong></p></td>
    <td><p>Select this check box to automatically process the wave and create work when a line is released to the warehouse.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Process wave automatically at threshold</strong></p></td>
    <td><p>Select this check box to automatically process the wave when its values reach the thresholds for weight, shipment, and lines specified in the <strong>Wave thresholds</strong> field group.</p>
    <p>This check box is available only if <strong>Shipping</strong> is selected in the <strong>Wave template type</strong> field.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Automate wave release</strong></p></td>
    <td><p>Select this check box to automatically release the wave. The picking work is created and made available on mobile devices.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Automate replenishment work</strong></p></td>
    <td><p><span id="asdf"></span> Select this check box to create demand-based replenishment work and release it automatically. You must add the replenishment wave method to the wave template, and create a replenishment template of the type <strong>Wave demand</strong>. Set up a replenishment template in the <strong>Replenishment templates</strong> form. This requires that you add the <strong>replenish</strong> method to the wave template.</p></td>
    </tr>
    </tbody>
    </table>


7.  Optional: To assign lines to an open wave when the lines are released, select the **Assign to open waves** check box. Lines are assigned to waves based on the query filter for the wave template.

8.  Optional: In the **Default values** field group, select the wave attributes to use as additional criteria for the wave template.

9.  On the **Methods** FastTab, the **Selected methods** pane lists the methods for the selected wave template type. To add an additional method, do the following:
    
    1.  Select a method on the **Remaining methods** pane, and then click the **Left** arrow to add it to the **Selected methods** pane.
    
    2.  To change the sequence, select a method, and then click **Up** or **Down** arrows.
        

        > [!NOTE]
        > <P>When you add a method, it’s automatically listed in the appropriate location in the sequence of steps.</P>



10. To set up the query that will match released lines to an appropriate wave, click **Load**.

11. To verify that the wave template settings are valid, click **Validate template**.

## Next step

[Set up warehouse parameters for wave processing](set-up-warehouse-parameters-for-wave-processing.md)

[Set up containerization](set-up-containerization.md)

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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

