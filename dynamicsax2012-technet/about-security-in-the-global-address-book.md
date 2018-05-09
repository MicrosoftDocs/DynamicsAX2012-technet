---
title: About security in the global address book
TOCTitle: About security in the global address book
ms:assetid: 8a7ce7ac-e482-48d9-892e-b16c08d50660
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731852(v=AX.60)
ms:contentKeyID: 35132714
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# About security in the global address book 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic assumes that you are familiar with the topic [Global address books and address reference data](global-address-books-and-address-reference-data.md).

## Determining security

You can set security privileges to party records in the following ways:

  - **Secure by legal entity** - Security privileges are based on the legal entity that a party is associated with. If you secure party records by legal entity, workers can only access the records that are associated with any legal entity that the worker has access to.

  - **Secure by address book** - Security privileges are based on teams. With this method, only workers who are assigned to a team that has access to an address book can view the party records in that address book.

  - **Secure by both legal entity and address book** – Security privileges are based on both legal entities and teams.

You can create address books at any time and if you choose, you can set security parameters for the address books at any time. Setting security for address books is not required in Microsoft Dynamics AX. However, if you do not restrict access by legal entity, or if security privileges are not set for an address book, all workers in your organization can view all party records. For more information about how to set up address book parameters, see [Set up global address book parameters](set-up-global-address-book-parameters.md). You can use the **Security policy options** link in the parameters form to select whether the enforcement of security privileges for address books is based on teams, legal entities, or both.

## Party record security based on legal entity

If you select **Secure by legal entity** in the **Global address book parameters** form, party record access for a worker is restricted to the legal entity that the worker has access to. When a new party record is created, if the record is not associated with a legal entity, all workers in your organization can view the party record.

The following table shows an example of two workers and the legal entities that they have access to.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>User</p></th>
<th><p>Legal entity</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>User 1</p></td>
<td><p>LE1</p></td>
</tr>
<tr class="even">
<td><p>User 2</p></td>
<td><p>LE1 and LE2</p></td>
</tr>
</tbody>
</table>


In this example, User 1 can view only the party records that belong to LE1. User 2 can view the party records that belong to both LE1 and LE2.

## Address book security based on teams

If you select **Secure by address book** in the **Global address book parameters** form, access to the address books is restricted by team. You must select the teams that have access to each address book. For each address book, you can set security privileges that allow or deny access to specific teams. If you grant a team privileges to an address book, all members of the team can view the records in the address book. If you do not grant a team access to an address book, the team cannot view the address book or its contents.


> [!IMPORTANT]
> <P>[The information in this note applies only to Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack. It does not apply to Microsoft Dynamics AX 2012 R2.]</P>
> <P>If you secure address books by team in Microsoft Dynamics AX, you must create a team that includes all Microsoft Dynamics AX users. Do not grant any security privileges to the team. If you do not create this team a worker who is not assigned to a team cannot access party records.</P>
> <P>For example, if you associate 95 percent of your party records with address books and the remaining 5 percent are not associated with an address book, Worker A, who is assigned to a team, can view the records associated with the address book that the team has access to. Worker A can also view the remaining 5 percent of records that are not associated with an address book. Worker B, who is not assigned to a team, cannot view any party records because the address books are secured by team.</P>



The following table shows an example of two teams and the address books that they have access to.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Address book</p></th>
<th><p>Team</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>PubSC</p></td>
<td><p>Public sector</p></td>
</tr>
<tr class="even">
<td><p>PTJPN</p></td>
<td><p>Pneumatic</p></td>
</tr>
</tbody>
</table>


In this example, the Public sector team can view only the party records that are in the PubSC address book. The Pneumatic team can view only the party records that are in the PTJPN address book.


> [!NOTE]
> <P>If you have also selected <STRONG>Secure by legal entity</STRONG>, a team member can view party records that are assigned to the same legal entity as the team member.</P>



For more information about teams, see [Manage teams](manage-teams.md).

## See also

[Set up global address book parameters](set-up-global-address-book-parameters.md)

[Create address books](create-address-books.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

