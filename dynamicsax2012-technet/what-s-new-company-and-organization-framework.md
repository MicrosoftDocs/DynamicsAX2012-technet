---
title: "What's new: Company and organization framework"
TOCTitle: Company and organization framework
ms:assetid: 0bc44ae4-1e8b-41b2-9180-83f24bd7bef4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn507119(v=AX.60)
ms:contentKeyID: 59623208
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Company and organization framework [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2012 has a new organization framework that supersedes the simple company feature that earlier versions had. The framework lets you create organizations and structure the organizations into hierarchies. Therefore, you can better model the separate legal and operational entities of a global corporation, and the hierarchical relationships between those entities.

## Overview

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Item</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required feature</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Product areas affected</p></td>
<td><p>All</p></td>
</tr>
<tr class="odd">
<td><p>Stakeholders</p></td>
<td><p>Business decision makers</p>
<p>Technical decision makers</p>
<p>Implementation team members</p>
<p>Independent software vendors (ISVs)/developers</p>
<p>Partners</p></td>
</tr>
</tbody>
</table>


## New functionality

The organization model functionality in AX 2012 lets you create more detailed hierarchy models that better reflect your business structure and processes. You can also more easily share data between organizations. This data includes reference information, master data, and transactions. Earlier versions of Microsoft Dynamics AX had limited capabilities for hierarchies and business modeling. Additionally, earlier versions did not share data between organizations, except in certain cross-company and virtual company scenarios.

## What’s new in AX 2012

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>What can you do?</p></th>
<th><p>Microsoft Dynamics AX 2009</p></th>
<th><p>AX 2012</p></th>
<th><p>Why is this important?</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Create organizations, such as legal entities and operating units.</p></td>
<td><p>Each organization in the business was created as a “company,” regardless of the type or hierarchy of the organization. In tables, the dataAreaId field identified each company and therefore determined the security boundary for each company’s data.</p>
<p>Some organizational concepts were independent of one other. For example, in the dimensions functionality, cost centers and departments were independent of each other. Likewise, in Human resource management, departments and organization units were independent of each other. Because these organizational concepts were independent of one other, they could not be maintained or managed in one location.</p></td>
<td><p>Concepts such as the organization, legal entity, and operational unit have replaced by the simple concept of a company.</p>
<p>You can create legal entities to represent the legal structure of your business, and you can create several types of operating units to represent how your business operates. All organization types are included in the organization model and can be used in hierarchies.</p></td>
<td><p>Business models more accurately reflect your business.</p></td>
</tr>
<tr class="even">
<td><p>Create organization hierarchies.</p></td>
<td><p>Hierarchical relationships between companies could not be represented.</p></td>
<td><p>New organization types can be arranged into hierarchies to model the legal and economic dimensions of any real business.</p></td>
<td><p>Business models more accurately reflect your business.</p></td>
</tr>
<tr class="odd">
<td><p>Create multiple operating unit hierarchies.</p></td>
<td><p>The feature was not supported.</p></td>
<td><p>You can build specialized hierarchies to report on various perspectives of the business. You can also use hierarchies to aggregate data from related business units.</p></td>
<td><p>Reporting can be more complex and accurate.</p></td>
</tr>
<tr class="even">
<td><p>Share parameters, policies, and transactions between organizations.</p></td>
<td><p>Because companies provided the security boundary for data, it was difficult to share data across companies. For the same reason, parameters and reference data had to be set up for every company.</p>
<p>To share data, you had to create virtual companies.</p></td>
<td><p>Many tables are shared by all organizations. Therefore, users can access data in those tables, regardless of the company or organization context.</p></td>
<td><p>It is easier to access and share data.</p>
<p>Data and security can be managed independently.</p></td>
</tr>
<tr class="odd">
<td><p>Perform tasks and view data in multiple organizations.</p></td>
<td><p>Tasks could be performed only in the context of a company. Company information could be accessed only when users were logged on to that company.</p></td>
<td><p>Users can view or modify data in different organization structures. The organization structures that users can access depend on the business process that the users are working in, not the company that they are logged on to.</p></td>
<td><p>It is easier to access and share data.</p>
<p>Data and security can be managed independently.</p></td>
</tr>
<tr class="even">
<td><p>Set up security based on the organization model.</p></td>
<td><p>Companies provided the data security boundary. Data was secured based on the company that it was associated with.</p></td>
<td><p>You can use the data security framework to help secure data based on any condition.</p>
<p>You can associate a user in a particular role with any organization or with an organization hierarchy. If you associate the users in a particular role with a hierarchy, user permissions change as the hierarchy changes. For example, if organizations are added to the hierarchy, users who have been granted access to the hierarchy automatically gain access to the new organizations.</p></td>
<td><p>Data and security can be managed independently.</p></td>
</tr>
<tr class="odd">
<td><p>Use the organization structure to control economic resources and operational processes.</p></td>
<td><p>The feature was not supported.</p></td>
<td><ul>
<li><p>Organizations can be used as financial dimensions.</p></li>
<li><p>Business rules and policies can be defined for organizations.</p></li>
</ul>
<p>For more information, see <a href="organization-hierarchies.md">How to use organization hierarchy purposes</a>.</p></td>
<td><p>Business models more accurately reflect your business.</p></td>
</tr>
</tbody>
</table>


## Special considerations

Before you set up the organization structure, you should plan a hierarchy of organizations that meets your organizational and reporting requirements. For more information about how to plan organization structures, see [Plan the organizational hierarchy](plan-the-organizational-hierarchy.md).

The organization model supports data sharing that you previously might have implemented by using virtual companies. If you are currently using virtual companies, we recommend that you evaluate whether the organization model meets your requirements. Virtual companies are still required in some cases. For more information, see [Upgrade company accounts and virtual company accounts](upgrade-company-accounts-and-virtual-company-accounts.md).


> [!NOTE]
> <P>AX 2012 changes the way that hierarchies are created for all operational units. These operational units include departments. After upgrade, you must re-create the hierarchies for departments.</P>



## More information

For more information about organization modeling, see [Organizations and organizational hierarchies](organizations-and-organizational-hierarchies.md).

Developers can extend the organization model by adding elements to some base enumerations and extending some classes. For more information about the developer experience, see [Extending the Organization Model](https://technet.microsoft.com/en-us/library/gg989786\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

