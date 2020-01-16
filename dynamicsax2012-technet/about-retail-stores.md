---
title: About retail stores
TOCTitle: About retail stores
ms:assetid: 0e9db194-7de8-44aa-aaad-82d6bb03bf50
ms:mtpsurl: https://technet.microsoft.com/library/Hh580567(v=AX.60)
ms:contentKeyID: 39519045
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About retail stores 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Microsoft Dynamics AX 2012 for Retail supports multiple retail channels, including online stores, online marketplaces, and brick-and-mortar stores. In Retail, a brick-and-mortar store is called a *retail store*. Each retail store can have its own payment methods, price groups, point-of-sale (POS) registers, income accounts and expense accounts, and staff.


> [!NOTE]
> <P>Microsoft Dynamics AX 2012 R3 also supports call centers as a type of retail channel. For more information about how to set up call centers, see <A href="set-up-a-call-center.md">Set up a call center</A>.</P>



After you create a retail store, you assign the products that you want the store to carry. You also assign employees, registers, and customers to the store. Finally, you add the new store to an organization hierarchy.

## Setting up retail stores

Before you can set up a retail store, you must complete some prerequisite tasks. After you complete these tasks, you can create a retail store and add details.

## Prerequisites

The following table shows the tasks that you must complete before you can set up a retail store in Microsoft Dynamics AX. The first column in the table describes the task. The second column contains a link to a topic that describes how to complete the task.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Topic</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Configure your organization structure and set up organization hierarchies for retail assortments, replenishment, and reporting.</p></td>
<td><p><a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a></p></td>
</tr>
<tr class="even">
<td><p>Set up a warehouse to represent the retail store.</p></td>
<td><p><a href="set-up-a-retail-store.md">Set up a retail store</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up number sequences for retail stores, store statements, and statement vouchers.</p></td>
<td><p><a href="set-up-number-sequences.md">Set up number sequences</a></p></td>
</tr>
<tr class="even">
<td><p>Configure parameters for Retail.</p></td>
<td><p><a href="https://technet.microsoft.com/library/hh597194(v=ax.60)">Retail parameters (form)</a></p>
<p><a href="https://technet.microsoft.com/library/hh580625(v=ax.60)">Retail shared parameters (form)</a></p>
<p><a href="https://technet.microsoft.com/library/hh597151(v=ax.60)">Retail scheduler parameters (form)</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up the methods of payment that the store accepts.</p>
<p>To process credit card transactions at retail point-of-sale (POS) registers, you can also set up payment services.</p></td>
<td><p><a href="set-up-payment-methods-for-an-organization.md">Set up payment methods for an organization</a></p>
<p><a href="set-up-payment-services.md">Set up Payment Services</a></p></td>
</tr>
<tr class="even">
<td><p>Set up sales tax groups.</p></td>
<td><p><a href="set-up-and-use-a-sales-tax-group.md">Set up and use a sales tax group</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up retail products.</p>
<p>Setting up retail products includes setting up retail product hierarchies, product variants, and product assortments.</p></td>
<td><p><a href="setting-up-retail-products.md">Setting up retail products</a></p>
<p><a href="set-up-a-retail-hierarchy.md">Set up a retail hierarchy</a></p>
<p><a href="set-up-sizes-colors-and-styles.md">Set up sizes, colors, and styles</a></p>
<p><a href="set-up-an-assortment.md">Set up an assortment</a></p></td>
</tr>
<tr class="even">
<td><p>Set up product price groups.</p></td>
<td><p><a href="about-setting-prices-by-using-price-groups.md">About setting prices by using price groups</a></p></td>
</tr>
<tr class="odd">
<td><p>Set up retail product pricing.</p>
<p>Setting up retail product pricing includes setting up price adjustments, discounts and discount periods.</p></td>
<td><p><a href="setting-up-price-adjustments-and-discounts.md">Setting up price adjustments and discounts</a></p></td>
</tr>
<tr class="even">
<td><p>Set up staff members.</p>
<div class="alert">

> [!NOTE]
> <P>You must also assign appropriate permissions to the workers, so that they can log on and perform tasks by using the Microsoft Dynamics AX for Retail POS system.</P>


</div></td>
<td><p><a href="set-up-staff-members.md">Set up staff members</a></p></td>
</tr>
<tr class="odd">
<td><p>Configure the Retail POS profiles to assign to the store.</p>
<p>Configuring Retail POS profiles includes many tasks, such as, setting up registers, setting up offline profiles, and setting up receipt formats and profiles. Review all of the tasks included in these topics and complete all of the tasks that apply to you.</p></td>
<td><p><a href="set-up-and-assign-functionality-profiles.md">Set up and assign functionality profiles</a></p>
<p><a href="setting-up-retail-pos.md">Setting up Retail POS</a></p></td>
</tr>
</tbody>
</table>


## Set up a retail store

After you complete the prerequisite tasks, complete these tasks to set up the details for the retail store.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Topic</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create a retail store.</p></td>
<td><p><a href="set-up-a-retail-store.md">Set up a retail store</a></p></td>
</tr>
<tr class="even">
<td><p>Assign a sales tax group to the store.</p></td>
<td><p><a href="assign-sales-tax-groups-to-stores.md">Assign sales tax groups to stores</a></p></td>
</tr>
<tr class="odd">
<td><p>Assign the accepted payment methods to the store.</p></td>
<td><p><a href="set-up-store-payment-methods.md">Set up store payment methods</a></p></td>
</tr>
<tr class="even">
<td><p>Add details to the product descriptions for products that you offer in your retail stores. For example, you can add rich text and images. The additional product details can be viewed in various contexts, such as on the point-of-sale register or on printed labels.</p>
<div class="alert">

> [!NOTE]
> <P>This step applies only if AX 2012 R3 is installed.</P>


</div></td>
<td><p><a href="add-and-update-product-attributes-for-retail-channels.md">Add and update product attributes for retail channels</a></p></td>
</tr>
<tr class="odd">
<td><p>Add the store to an organization hierarchy that is assigned to a purpose of <strong>Retail assortment</strong>, <strong>Retail replenishment</strong> and <strong>Retail reporting</strong>.</p>
<p>For more information about using organization hierarchies for retail purposes, see the <strong>Organization hierarchies</strong> section later in this topic.</p></td>
<td><p><a href="create-or-modify-an-organization-hierarchy.md">Create or modify an organization hierarchy</a></p></td>
</tr>
</tbody>
</table>


## After you set up a retail store

After you enter the details for the retail store, complete these tasks to send the new retail store data to Microsoft Dynamics AX for Retail POS.

For more information about how to configure Retail POS, see [Point of Sale](point-of-sale.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Topic</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Configure the point of sale (POS) registers for the store.</p></td>
<td><p><a href="set-up-registers.md">Set up registers</a></p></td>
</tr>
<tr class="even">
<td><p>Assign product assortments to the store.</p>
<div class="alert">

> [!NOTE]
> <P>You can assign the retail store to an existing assortment or create a new assortment for the retail store.</P>


</div></td>
<td><p><a href="set-up-an-assortment.md">Set up an assortment</a></p></td>
</tr>
<tr class="odd">
<td><p>Process assortments to generate the list of products that are included in the assortment and to make the products available in the retail store.</p></td>
<td><p><a href="configure-the-retail-assortments-job.md">Configure the retail assortments job</a></p></td>
</tr>
<tr class="even">
<td><p>Send data such as number sequences, hardware profiles, POS screen layouts, and so on to the Retail POS registers.</p></td>
<td><p>Deploy Retail POS</p>
<div class="alert">

> [!NOTE]
> <P>If AX 2012 R3 is installed, see <A href="mass-deploy-retail-components-by-using-system-center-configuration-manager.md">Mass deploy Retail components</A>.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Run the jobs to send the store data to Retail POS.</p></td>
<td><p><a href="configure-jobs-and-subjobs-in-retail-scheduler.md">Configure jobs and subjobs in Retail Scheduler</a></p></td>
</tr>
<tr class="even">
<td><p>Publish the retail store to send store data to Retail POS.</p>
<div class="alert">

> [!NOTE]
> <P>This step applies only if AX 2012 R3 is installed.</P>


</div></td>
<td><p><a href="set-up-a-retail-store.md">Set up a retail store</a></p></td>
</tr>
</tbody>
</table>


## Organization hierarchies

Retail uses organization hierarchies in Microsoft Dynamics AX to structure retail channels. Organization hierarchies represent the relationships between the organizations that make up your business. When you set up stores, you can add them to an organization hierarchy. The stores then share data that is used for assortments, replenishment, and reporting.

When you create an organization hierarchy, you assign a purpose to it. The purpose indicates how the hierarchy is used in the business structure. You can create one organization hierarchy for your store operations, and use that hierarchy for assortments, replenishment, and reporting. Alternatively, you can create a separate organization hierarchy for each purpose. You can also create multiple hierarchies with the same purpose and assign a channel to each of those.

After you set up the organization hierarchy and assign stores to it, you use the hierarchy to determine which stores you can distribute assortments to or replenish stock for. For example, you configure an organization hierarchy and assign a purpose of **Retail assortment** to it. Then, when you must distribute assortments to retail channels, you can select only the retail channels that are included in this organization hierarchy.

For more information about how to set up an organization hierarchy, see [Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md).

## See also

[About organizations and organizational hierarchies](about-organizations-and-organizational-hierarchies.md)

  


