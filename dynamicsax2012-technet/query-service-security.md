---
title: Query Service Security
TOCTitle: Query Service Security
ms:assetid: 797fe421-73e1-4759-a582-aaf11b0422b7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg862440(v=AX.60)
ms:contentKeyID: 35246051
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Query Service Security 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

There are two types of security to consider when you work with the Microsoft Dynamics AX query service:

  - Access security – who can access the query service

  - Data security – what data can a user access by using the query service

## Access Security

Only authenticated Microsoft Dynamics AX users can access the query service. In order to retrieve data by using the query service, you must have a valid username in Microsoft Dynamics AX. The query service uses Windows integrated security. Therefore, when a caller invokes the query service, the system verifies the credentials under which the calling client is running and verifies that the username is a valid Microsoft Dynamics AX user.

The query service is always available and any authenticated Microsoft Dynamics AX user can access the service.

## Data Security

The data that a calling user can access by using the query service depends on what roles the user is a member of. The query service respects any record-level or field-level security that is implemented for the calling user.

The user’s security access determines the query behavior or the data that is returned for a user as shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>Security Condition</p></td>
<td><p>Result</p></td>
</tr>
<tr class="even">
<td><p>User does not have access to one or more tables accessed by a query data source.</p></td>
<td><p>The query will fail with an error that indicates that access is denied.</p></td>
</tr>
<tr class="odd">
<td><p>User does not have access to a field returned by a query data source.</p></td>
<td><p>The field is returned in the dataset but the field value is DbNull.</p>
<p>For more information about data that the AOS withholds from the current user, see <a href="https://technet.microsoft.com/en-us/library/gg840968(v=ax.60)">Finding All Fields the AOS can Trim</a>.</p></td>
</tr>
<tr class="even">
<td><p>User does not have access to a field that is used in a query data source relation (join), order by, group by, data source range, or query filter.</p></td>
<td><p>The query will fail with an error that indicates that access is denied.</p></td>
</tr>
</tbody>
</table>


## See also

[Query Service](query-service.md)

