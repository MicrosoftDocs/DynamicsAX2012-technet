---
title: Database security best practices
TOCTitle: Database security best practices
ms:assetid: 5673912e-3b7c-4ec8-a31f-da02d2727797
ms:mtpsurl: https://technet.microsoft.com/library/Dn385338(v=AX.60)
ms:contentKeyID: 56554591
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Database security best practices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If a malicious user were to gain access to the Microsoft Dynamics AX database, that user might gain access to data, including sensitive data such as credit card numbers, bank account numbers, and personal identification numbers. You should deploy the database as described in this section to protect data in your business or organization and reduce the overall attack surface of this core Microsoft Dynamics AX component.

We recommend that you do the following:

  - Follow SQL Server security recommended practices.

  - Use the table permissions framework.

  - Secure the database logs.

## Follow SQL Server security recommended practices

We assume that you have followed the recommended transactional SQL Server security best practices described in the article [Securing SQL Server](https://msdn.microsoft.com/library/bb283235.aspx). These best practices include:

  - Platform and network security, including physical, operating system and file security

  - Principals and database object security

We also assume that security best practices are in place for all functions of SQL Server throughout the environment:

  - [Security and protection (SSRS)](https://msdn.microsoft.com/library/bb522728.aspx)

  - [Security and protection for analytics](security-and-protection-for-analytics.md)

  - [Security planning for SharePoint 2013 farms](https://technet.microsoft.com/library/hh377941.aspx)

## Encrypt sensitive data

We recommend that you implement database encryption to enhance the security of data, including sensitive data, such as credit card numbers, bank account numbers, and personal identification numbers. If your business or organization processes and stores credit card information, we recommend that you adhere to the standards set by the [PCI Security Standards Council](https://go.microsoft.com/fwlink/?linkid=119942) for securing cardholder data. The [PCI Data Security Standard](https://go.microsoft.com/fwlink/?linkid=119943) requires the following:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Security standard</p></th>
<th><p>Requirement</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Build and Maintain a Secure Network</p></td>
<td><p>1. Install and maintain a firewall configuration to protect cardholder data.</p>
<p>2. Do not use vendor-supplied defaults for system passwords and other security parameters.</p></td>
</tr>
<tr class="even">
<td><p>Protect Cardholder Data</p></td>
<td><p>3. Protect stored cardholder data.</p>
<p>4. Encrypt the transmission of cardholder data across open, public networks.</p></td>
</tr>
<tr class="odd">
<td><p>Maintain a Vulnerability Management Program</p></td>
<td><p>5. Use and regularly update antivirus software.</p>
<p>6. Develop and maintain secure systems and applications.</p></td>
</tr>
<tr class="even">
<td><p>Implement Strong Access Control Measures</p></td>
<td><p>7. Restrict access to cardholder data.</p>
<p>8. Assign a unique ID to each user with computer access.</p>
<p>9. Restrict physical access to cardholder data.</p></td>
</tr>
<tr class="odd">
<td><p>Regularly Monitor and Test Networks</p></td>
<td><p>10. Track and monitor all access to network resources and cardholder data.</p>
<p>11. Regularly test security systems and processes.</p></td>
</tr>
<tr class="even">
<td><p>Maintain an Information Security Policy</p></td>
<td><p>12. Maintain a policy that addresses information security.</p></td>
</tr>
</tbody>
</table>


Enabling database encryption directly addresses the requirement to protect stored cardholder data. SQL Server includes an encryption feature called Transparent Data Encryption (TDE). TDE is designed to provide protection for the entire database while it is at rest, without affecting existing applications. Implementing encryption in a database traditionally involves complicated application changes, such as modifying table schemas, removing functionality, and significant performance degradations. Custom schemes are often used to resolve equality searches, and ranged searches often cannot be used at all. Even basic database elements, such as creating an index or using foreign keys often do not work with cell-level or column-level encryption schemes, because the use of these features inherently leaks information. TDE solves these problems by encrypting everything, including all data types, keys, and indexes. For more information, see [Database Encryption in SQL Server 2008 Enterprise Edition](https://go.microsoft.com/fwlink/?linkid=119936).

## Secure the database logs

Database logs can contain sensitive data. By default, any database log that is created can be queried by any user who has access to the database. Users can query the log by using .NET Business Connector, X++, alerts, or direct access to the database. To protect data, restrict the permissions on the **sysdatabaselog** table. For detailed information, see [Table Properties](https://technet.microsoft.com/library/aa871620\(v=ax.60\)).

  


