---
title: Automate the process of building loads
TOCTitle: Automate the process of building loads
ms:assetid: 96a5f406-928f-4858-9802-cfd078b3d95e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn887223(v=AX.60)
ms:contentKeyID: 63378895
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- load
- carrier
- shipping
- proposal
- transportation
- shipment
- Forms.TMSLoadBuildProposal
- Forms.TMSLoadBuildStrategy
- Forms.TMSLoadBuildWorkbench
audience: Application User
ms.search.region: Global
---

# Automate the process of building loads 



> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes a feature that is available only if you are running Microsoft Dynamics AX 2012 R3 Cumulative Update 8. The topic provides information about how to use load building strategies to automatically build loads. The following are some examples of when this is useful:

  - When you regularly ship a certain set of products. Rather than building loads every time, you can apply load building strategies.

  - When you want to maximize efficiency by avoiding half full loads.

## Use a load building strategy

Microsoft Dynamics AX provides a load building strategy named **Volume-based load building strategy**. This strategy lets you use the maximum values specified for height and weight in the load template, or override the settings by entering new values. To use this strategy, select it in the **Load building strategy** field on the **Setup** FastTab in the **Load building workbench** form.

In addition, you can add your own load-building strategies by creating a new class in the Application Object Tree (AOT). For information about how to do this, see the following procedures.

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
<td><p><strong>Released products</strong> and <strong>Warehouses</strong></p></td>
<td><p>The products and warehouses that are included in the sales orders must be enabled for <strong>Warehouse management</strong> processes.</p></td>
</tr>
<tr class="even">
<td><p><strong>Load template</strong></p></td>
<td><p>You must create one or more load templates. When you generate proposed loads, load building strategies use the attributes defined on the load template to determine what to put in the loads. For more information, see <a href="set-up-a-load-template.md">Set up a load template</a>.</p>
<div class="alert">

> [!NOTE]
> <P>A load building strategy named <STRONG>Volume-based load building strategy</STRONG> is provided in AX 2012 R3 CU8. If you have more than one load template, the volume based load template strategy uses only the first load template in the list.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Licenses</p></td>
<td><p>To be able to add a new class to the AOT, you need the X++ development license code for Microsoft Dynamics AX: SysXpp.</p></td>
</tr>
</tbody>
</table>


## Create a class for a new load building strategy

You can create new classes if you want to implement different strategies for building loads. This section provides tips and tricks that can help you create and implement your own load building strategy class.

A load building strategy named **Volume-based load building strategy** is provided in AX 2012 R3 CU8. This strategy lets you use the maximum values specified for height and weight in the load template, or override the settings by entering new values.

You must create a class that implements the **TMSILoadBuildStrategy** interface. To make the new class available, you need to apply it with **TMSLoadBuildStrategyEnableAttribute**. When you create the class, you should consider the following:

  - The **getDescription** method has to return a reference to a Microsoft Dynamics AX label that contains a user-friendly description of the strategy that you’re building. This description is displayed when you set up and use strategies that use this class.

  - Your class can require specific numeric, string, Boolean, and UTC date and time values for initializing the class instance. To notify the system about the type of data that is needed to initialize the class instance, you need to implement the **populateParameterCollection** method. This method requires that you provide object instances that derive from the **TMSLoadBuildStrategyParam** class. These objects represent parameters, so you need to make sure that they use unique keys to identify the parameter names. The keys are used to retrieve the parameter value when an object is initialized by the **init** method. The parameter values are specified by the user on the **Load building strategy parameters** form. After you add a strategy class, you have to click **Generate class list** on the **Load building strategies** form to add the class and its parameters to the list in the form.

  - The **TMSLoadBuildSession** table groups information about proposed loads into a load building session. This ensures that sessions are kept separate if more than one user is performing the process at the same time. The **TMSProposedLoadContent** table contains information about the supply and demand lines that need to be assigned to loads. The **TMSLoadBuildStrategyInputSet** table groups lines so that content lines that should not be packed together are kept separate. The load building process for each request occurs separately for each load building strategy input set. The **proposeLoads** method on your strategy class is called one time for each input set. This method should iterate through the **TMSProposedLoadContent** table records that belong to a load building strategy input set, and assign the reference to the **TMSProposedLoad** table records. By leaving the optional reference to **TMSProposedLoads** table blank, you indicate that the proposed load content record is not assigned to a proposed load. After you use the proposed loads to create loads, the lines in the **TMSProposedLoad** table become lines in the **TMSLoadTable** table. Records in the **TMSProposedLoadContent** table become one or more load lines. For an overview of the physical data model, see the following diagram.
    
    ![Proposed Loads for TM AX 2012 CU8](images/Dn887223.ProposedLoadsforTMAX2012CU8(AX.60).png "Proposed Loads for TM AX 2012 CU8")

## Set up a load building strategy and set parameters for it

After you’ve added a class for load building strategies to the AOT, you need to apply the class in Microsoft Dynamics AX. You do this by setting up load building strategies, which also let you set and maintain parameters for the strategy.

To set up a load building strategy and set parameters for it, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Load building strategies**.

2.  In the **Name** field, enter a name for the strategy.

3.  In the **Load building strategy class** field, select the class that contains the logic for the load building strategy. When you select a class, the **Description** field automatically displays the description of the strategy of the class.
    

    > [!NOTE]
    > <P>If you are setting up a strategy, or have updated a class and want to add it to the list of classes, click <STRONG>Generate class list</STRONG>.</P>



4.  To add or maintain parameters for the class, click **Parameters**.

5.  Select the attribute in the list on the left part of the form, and on the **General** FastTab, enter or select the parameter settings.
    

    > [!NOTE]
    > <P>The parameters that are available are provided through the class, and can vary depending on the design of the class. For the volume-based load building strategy class that is provided in AX 2012 R3 CU8, you can specify the percentage of the maximum volume capacity that you can fill for a load, and the maximum weight capacity. The parameter value works together with the maximum setting specified on the load template. For example, if the maximum volume capacity setting on the load template is 100 percent, and you specify a value of 10 for the volume capacity parameter, then a load will be filled to 10 percent.</P>



## Build proposed loads, make changes, and then create loads based on the proposed loads

You can create proposed loads based on a load building strategy.

To build proposed loads, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Load building workbench**.
    
    –or–
    
    Click **Transportation management** \> **Inquiries** \> **Load planning workbench**. On the **Action Pane**, click **Load building workbench**.

2.  In the **Load building template** field, select the template to use to generate the proposed loads, or enter a name for a new template.

3.  In the **Load building strategy** field, select the strategy that contains the criteria to apply when generating the proposed loads.

4.  In the **Supply or demand type** field, select **Sales**.

5.  Optional: On the **Setup** FastTab, you can specify ranges of criteria to control what goes into the load. For example, you can specify ranges of shipping and delivery dates, postal codes, country and region, and sites and warehouses. You can also apply filter codes. For more information, see [Set up filters and filter groups](set-up-filters-and-filter-groups.md).

6.  Optional: To define additional criteria for finding sales order lines, click **Edit query**, and then enter the criteria. Typically, this is used for specific cases. For example, if you want to use a specific carrier for the loads.

7.  On the **Load templates** FastTab, select the load template to use to generate the proposed loads. Use the **Move up** and **Move down** buttons to arrange them in the sequence in which you want them to be evaluated.

8.  Click **Propose loads**.

To change the proposed loads, follow these steps:

1.  On the **Proposed load lines** FastTab, do any of the following:
    
      - To remove a proposed load line, click **Remove from proposed load**. The line is moved from the **Proposed load lines** FastTab to the **Not included** FastTab. It is still available in the supply and demand.
    
      - To assign the load line to a different load, in the **Proposed load** column, select the load to assign it to.

2.  On the **Not included** FastTab, you can add lines to a proposed load. For example, this is useful if you know that the items can fit on the load although the system did not find capacity for it. The **Not included** FastTab includes sales order lines that the load building strategy could not include in a load. This can occur if a load already exceeded the maximum allowed for a load. To add a line to the proposed load, in the **Proposed load** column, select the load to assign it to.

To create loads based on the proposed loads, follow this step:

  - Click **Create loads**.

## Clean up unused data for proposed loads

When you create proposed loads, a session is created to store the temporary proposals. When you create the loads, the information about the proposed loads is cleared. However, if you create proposed loads, but do not create the loads, the data is not cleared. If you frequently create proposed loads, the data can start to pile up. By default, the batch job will delete records that were created at least one day before the current date.

To run a batch job to clean up unused data for proposed loads, follow these steps:

1.  Click **Transportation management** \> **Periodic** \> **Clear load building session information**.

2.  Enter criteria for the batch job.

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p>
<p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Select the <strong>X++ development</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


