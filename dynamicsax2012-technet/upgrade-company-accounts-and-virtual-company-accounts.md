---
title: Upgrade company accounts and virtual company accounts
TOCTitle: Upgrade company accounts and virtual company accounts
ms:assetid: 2e36c456-16f8-49c3-9ec4-24ed66e5ccc9
ms:mtpsurl: https://technet.microsoft.com/library/Hh575203(v=AX.60)
ms:contentKeyID: 39555337
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Upgrade company accounts and virtual company accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Perform the **Virtual company accounts** task in the upgrade checklist to prepare the Microsoft Dynamics AX 2012 target system for upgrade. This task opens the **Virtual company accounts** form, where you can create virtual companies.


> [!NOTE]
> <P>This task appears in the upgrade checklist only if you upgrade to Microsoft Dynamics AX 2012 R3 or AX 2012 R2. However, we recommend that you perform this task no matter which version of Microsoft Dynamics AX 2012 you are upgrading to.</P>



The information in this topic can help you understand how to upgrade companies and virtual companies to Microsoft Dynamics AX 2012.

The following table provides an overview of how domains, companies, and virtual companies are upgraded. If the upgrade method is “Manual,” you must evaluate and upgrade the data in a manner that is appropriate for your business.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Terminology in previous releases</p></th>
<th><p>Equivalent in Microsoft Dynamics AX 2012</p></th>
<th><p>Upgrade method</p></th>
<th><p>Details</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Domain</p></td>
<td><p>Organizational hierarchy</p></td>
<td><p><strong>Manual upgrade</strong></p></td>
<td><p>In previous releases of Microsoft Dynamics AX, you could create a collection of companies that was known as a domain. You could use domains to set up user permissions for a group of company accounts. Domain functionality was removed from Microsoft Dynamics AX 2012. For information about how to upgrade a domain, see <a href="upgrade-domains.md">Upgrade domains</a>.</p></td>
</tr>
<tr class="even">
<td><p>Company</p></td>
<td><p>Legal entity</p></td>
<td><p><strong>Automatic upgrade</strong></p></td>
<td><p>A company account in previous releases is upgraded to a company account in Microsoft Dynamics AX 2012, and a corresponding legal entity is created.</p>
<p>For this release, every record for a legal entity is associated with a company ID. This association exists because some functional areas in the program use a company ID, or DataAreaId, in their data models. In these functional areas, companies are used as a boundary for data security. Users can access data only for the company that they are currently logged on to.</p>
<p>If you are upgrading to Microsoft Dynamics AX 2012 R3 or AX 2012 R2, company accounts must be associated with partitions. If you do not map companies to partitions, all companies will be mapped to the default partition. If existing company accounts must belong to separate partitions in AX 2012 R3 or AX 2012 R2, manual intervention is required.</p>
<p>Data is shared only among organizations that reside in the same partition. If you plan to share data through virtual companies, all company accounts that are associated with the virtual company account must reside in the same partition.</p>
<p>For more information about how to map company accounts to partitions during the upgrade process, see <a href="configure-partitions.md">Configure partitions</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Virtual company</p></td>
<td><p>Shared data tables or virtual company</p></td>
<td><p><strong>Manual upgrade</strong></p></td>
<td><p>A virtual company account is a collection of tables that is shared among a group of companies. When users save information in one of the tables, the data becomes available to the other company accounts in the group.</p>
<p>In Microsoft Dynamics AX 2012, most master data entities, such as charts of accounts, parties, and products, are shared among organizations. Before you upgrade, we recommend that you determine whether the data that you want to share is already shared organization-wide in Microsoft Dynamics AX 2012. Review the tables that are in the table collection of each virtual company. If any tables have been converted to shared data tables, their presence in the table collection of a virtual company is redundant. Therefore, we recommend that you remove these tables from the table collection.</p>
<p>Some master data entities, such as customer accounts and vendor accounts, are still defined per company. To share data from master data entities that are not shared by default, you may want to continue to use virtual companies. When you upgrade, you must create the necessary table collections and virtual companies on the target system during the data upgrade. For more information about how to create virtual companies and table collections, see <a href="virtual-company-accounts-in-microsoft-dynamics-ax.md">Virtual company accounts in Microsoft Dynamics AX</a>.</p>
<div class="alert">

> [!NOTE]
> <P>When you use virtual companies, you must share all attributes of a relationship. Therefore, you may want to use a shared data entity such as a party to share data for customers and vendors.</P>


</div></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>If you want to help secure shared data based on organization, you may have to create a customization that includes changes to the data model and extensible data security policies. For more information about extensible data security policies, see the white paper <A href="http://www.microsoft.com/download/en/details.aspx?id=3110">Developing Extensible Data Security Policies</A>.</P>


  


