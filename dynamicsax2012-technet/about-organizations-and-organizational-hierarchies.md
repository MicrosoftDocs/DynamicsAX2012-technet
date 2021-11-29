---
title: About organizations and organizational hierarchies
TOCTitle: About organizations and organizational hierarchies
ms:assetid: 137789f9-7c07-4102-8222-6f06bb0ed3f1
ms:mtpsurl: https://technet.microsoft.com/library/Hh242144(v=AX.60)
ms:contentKeyID: 36056047
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About organizations and organizational hierarchies 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An organization is a group of people who are working together to carry out a business process or achieve a goal. Organizational hierarchies represent the relationships between the organizations that make up your business.

## Organizations

In Microsoft Dynamics AX, you can define the following types of internal organizations: legal entities, operating units, and teams.

All internal organizations are types of the **Party** entity. Therefore, these organizations use the address book to store address and contact information. A party, which can be either a person or an organization, can belong to one or more address books. For more information, see [Global address books and address reference data](global-address-books-and-address-reference-data.md).

## Legal entities

A legal entity is an organization that has a registered or legislated legal structure. Legal entities can enter into legal contracts and are required to prepare statements that report on their performance.

A company is a type of legal entity. In this release of Microsoft Dynamics AX, companies are the only kind of legal entity that you can create, and every legal entity is associated with a company ID. This association exists because some functional areas in the program use a company ID, or DataAreaId, in their data models. In these functional areas, companies are used as a boundary for data security. Users can access data only for the company that they are currently logged on to.

## Operating units

An operating unit is an organization that is used to divide the control of economic resources and operational processes in a business. People in an operating unit have a duty to maximize the use of scarce resources, improve processes, and account for their performance.

In Microsoft Dynamics AX, the types of operating units include cost centers, business units, value streams, departments, and retail channels. The following table provides more information about each type of operating unit.

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
<td><p>Cost center</p></td>
<td><p>An operating unit in which managers are accountable for budgeted and actual expenditures.</p></td>
<td><p>Used for the management and operational control of business processes that span legal entities.</p></td>
</tr>
<tr class="even">
<td><p>Business unit</p></td>
<td><p>A semi-autonomous operating unit that is created to meet strategic business objectives.</p></td>
<td><p>Used for financial reporting that is based on industries or product lines that the organization serves independently of legal entities.</p></td>
</tr>
<tr class="odd">
<td><p>Value stream</p></td>
<td><p>An operating unit that controls one or more production flows.</p></td>
<td><p>Commonly used in lean manufacturing to control the activities and flows that are required to supply a product or service to consumers.</p></td>
</tr>
<tr class="even">
<td><p>Department</p></td>
<td><p>An operating unit that represents a category or functional part of an organization that performs a specific task, such as sales or accounting.</p></td>
<td><p>Used to report on functional areas. A department may have profit and loss responsibility, and may consist of a group of cost centers.</p></td>
</tr>
<tr class="odd">
<td><p>Retail channel</p></td>
<td><p>An operating unit that represents a brick and mortar store, an online store or an online marketplace.</p></td>
<td><p>Used for the management and operational control of one or more stores within or across legal entities.</p></td>
</tr>
</tbody>
</table>


## Teams

A team is an organization in which the members share a common responsibility, interest, or objective. For more information about teams, see [Manage teams](manage-teams.md). Teams cannot be used in organizational hierarchies.

## Organizational hierarchies

Set up organizational hierarchies to view and report on your business from different perspectives. For example, you can set up a hierarchy of legal entities for tax, legal, or statutory reporting. Set up a hierarchy that is based on operating units to report financial information that is not legally required, but that is used for internal control. For example, you can create a purchasing hierarchy to control purchasing policies, rules, and business processes.

Each hierarchy is assigned a purpose in Microsoft Dynamics AX. The purpose of a hierarchy determines the types of organizations that can be included in the hierarchy. The purpose also determines which application scenarios a hierarchy can be used in. For more information, see [How to use organization hierarchy purposes](organization-hierarchies.md).

Organizations in a hierarchy can share parameters, policies, and transactions. An organization can inherit or override the parameters of its parent organization. However, shared master data, such as products and address books, applies to the whole organization and cannot be overridden for individual organizations.

Creating organizations and hierarchies requires careful planning. For more information, see [Plan the organizational hierarchy](plan-the-organizational-hierarchy.md).

## See also

[Create or modify a legal entity](create-or-modify-a-legal-entity.md)

[Create or modify an operating unit](create-or-modify-an-operating-unit.md)

[Create or modify an organization hierarchy](create-or-modify-an-organization-hierarchy.md)

  


