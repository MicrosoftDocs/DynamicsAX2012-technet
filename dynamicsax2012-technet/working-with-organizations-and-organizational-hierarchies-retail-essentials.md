---
title: Working with organizations and organizational hierarchies (Retail essentials)
TOCTitle: Working with organizations and organizational hierarchies (Retail essentials)
ms:assetid: 06da61a1-8155-4e70-a475-bd441b2c9ac9
ms:mtpsurl: https://technet.microsoft.com/library/Dn716038(v=AX.60)
ms:contentKeyID: 62200305
author: tonyafehr
ms.date: 01/07/2015
mtps_version: v=AX.60
---

# Working with organizations and organizational hierarchies (Retail essentials) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

An organization is a group of people who work together to carry out a business process or achieve a goal. An organizational hierarchy represents the relationships between the business units that make up your organization.

## Organizations

In Retail essentials, you can define three types of internal organizations: legal entities, operating units, and teams.

In Microsoft Dynamics AX, all internal organizations are types of the **Party** entity. Therefore, these organizations use an address book to store addresses and other contact information. A party can be either a person or an organization, and it can belong to one or more address books. For more information, see [Working with address books (Retail essentials)](working-with-address-books-retail-essentials.md).

## Legal entities

A legal entity is an organization that has a registered or legislated legal structure. Legal entities can enter into legal contracts and are required to prepare statements that report on their performance.

A company is a type of legal entity in Microsoft Dynamics AX, and every legal entity is associated with a company ID. This association exists because a company ID, or DataAreaId, is used in some data models where companies are used as a boundary for data security. Users can access data only for the company that they are currently logged on to.

## Operating units

An operating unit is an organization that is used to divide the control of economic resources and operational processes in a business. People in an operating unit have a duty to maximize the use of scarce resources, improve processes, and account for their performance.

In Retail essentials, the types of operating units include cost centers, business units, value streams, departments, and retail channels. The following table provides more information about each type of operating unit.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Operating unit type</p></th>
<th><p>Description</p></th>
<th><p>Purpose</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Cost center</strong></p></td>
<td><p>An operating unit in which managers are accountable for budgeted and actual expenditures.</p></td>
<td><p>Use cost centers to manage and control business processes that span legal entities.</p></td>
</tr>
<tr class="even">
<td><p><strong>Business unit</strong></p></td>
<td><p>A semi-autonomous operating unit that is created to meet strategic business objectives.</p></td>
<td><p>Use business units for financial reporting that is based on industries or product lines that the organization serves across legal entities.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Value stream</strong></p></td>
<td><p>An operating unit that controls one or more production flows.</p></td>
<td><p>Commonly used in lean manufacturing to control the activities and flows that are required to supply a product or service to consumers.</p></td>
</tr>
<tr class="even">
<td><p><strong>Department</strong></p></td>
<td><p>An operating unit that represents a category or functional part of an organization that performs a specific task, such as sales or accounting.</p></td>
<td><p>Use departments to report on functional areas. A department may be responsible for reporting its profit or loss, and may consist of a group of cost centers.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Retail channel</strong></p></td>
<td><p>An operating unit that represents a brick-and-mortar store.</p></td>
<td><p>Use to manage and control one or more stores within or across legal entities.</p></td>
</tr>
</tbody>
</table>


## Organizational hierarchies

Use organizational hierarchies to view and report on a business from different perspectives. For example, you can set up a hierarchy of legal entities for tax, legal, or statutory reporting. Set up a hierarchy that is based on operating units to report financial information that is not legally required, but that is used for internal control. For example, you can create a purchasing hierarchy to control purchasing policies, rules, and business processes.

In Retail essentials, each hierarchy is assigned a purpose. The purpose of a hierarchy determines the types of organizations that can be included in the hierarchy. The purpose also determines which application scenarios a hierarchy can be used in. For example, a retail hierarchy can be used to buy and sell products in a retail store.

Organizations in a hierarchy can share parameters, policies, and transactions. An organization can inherit or override the parameters of its parent organization. However, shared master data, such as products and address books, applies to the whole organization and can’t be overridden for individual organizations.

## Best practices for setting up an organization in a hierarchy

Consider the following best practices when you implement an organization hierarchy:

  - Create a department to specify the intersection between a legal entity and a business unit. You can then roll up data from a department to a legal entity for statutory reporting, and from a department to a business unit for internal reporting.
    
    Departments can serve as profit centers. If you use departments, you do not have to use legal entities and business units as dimensions in the account structure. You can use just departments as a dimension. However, you must use both cost centers and departments as dimensions in the account structure if cost centers are used only as cost accumulators, and departments are used for revenue recognition.

  - Set up multiple hierarchies for operating units if you have complex requirements for reporting profit and loss.

  - In a single legal entity, don’t set up multiple hierarchies for the same hierarchy purpose.

  - Don’t create a hierarchy for every purpose. Usually, you can use one hierarchy for multiple purposes. For example, one hierarchy of operating units can be assigned to all policy-related purposes.

  - Create balanced hierarchies. In a hierarchy, all nodes that are the same distance from the root node are defined as a level. In a balanced hierarchy, only one type of operating unit can occur at each level, and the distance from the root node to each level is consistent. If there are intermediate levels between a department and a legal entity or a business unit, placeholder organizations may be required to create a balanced hierarchy.

  - Don’t set up a separate hierarchy of operating units if the structure for legal entities is also your operating structure. A mixed hierarchy of legal entities and operating units may serve both purposes.

  - Before you set up major restructuring scenarios, use the hierarchy's effective dates to perform an impact analysis and a validation test.

  - Save a hierarchy as a draft if you might change a hierarchy before you publish it.

  - Limit the number of people who have permissions to add or remove organizations from a hierarchy in a production environment. A smaller number reduces the chance that costly mistakes can occur and corrections must be made.

## Retail store management

The following table describes the Retail essentials scenarios where organization hierarchies can be used.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Task</p></th>
<th><p>Description</p></th>
<th><p>Hierarchy purpose</p></th>
<th><p>More information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Manage retail assortments</p></td>
<td><p>Identify the products that are available in each retail store.</p></td>
<td><p><strong>Retail assortment</strong></p></td>
<td><p><a href="assortments-retail-essentials.md">Assortments (Retail essentials)</a></p></td>
</tr>
<tr class="even">
<td><p>Manage retail replenishment</p></td>
<td><p>Group stores to replenish inventory based on replenishment rules.</p></td>
<td><p><strong>Retail replenishment</strong></p></td>
<td><p><a href="set-up-replenishment-hierarchies-retail-essentials.md">Set up replenishment hierarchies (Retail essentials)</a></p>
<p><a href="set-up-replenishment-rules-retail-essentials.md">Set up replenishment rules (Retail essentials)</a></p></td>
</tr>
<tr class="odd">
<td><p>Report data for stores</p></td>
<td><p>Group stores for reporting.</p></td>
<td><p><strong>Retail reporting</strong></p></td>
<td><p><a href="reports-retail-essentials.md">Reports (Retail essentials)</a></p></td>
</tr>
<tr class="even">
<td><p>Post inventory, calculate statements, or post statements for a group of stores</p></td>
<td><p>Create a group of stores that can be assigned to a batch job. When you define a batch job to post inventory, calculate statements, or post statements, you can specify which hierarchy the job applies to. When stores are added to or removed from the hierarchy, you don’t have to modify the batch job.</p></td>
<td><p><strong>Retail POS posting</strong></p></td>
<td><p><a href="inventory-management-retail-essentials.md">Inventory management (Retail essentials)</a></p>
<p><a href="create-and-post-a-statement-retail-essentials.md">Create and post a statement (Retail essentials)</a></p></td>
</tr>
</tbody>
</table>


## See also

[Create or modify an organization hierarchy (Retail essentials)](create-or-modify-an-organization-hierarchy-retail-essentials.md)

  


