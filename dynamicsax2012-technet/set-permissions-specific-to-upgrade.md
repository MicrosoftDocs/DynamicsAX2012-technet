---
title: Set permissions specific to upgrade
TOCTitle: Set permissions specific to upgrade
ms:assetid: 122768fd-6d63-46ad-b8e3-1d389f544ab0
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg751355(v=AX.60)
ms:contentKeyID: 35132553
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set permissions specific to upgrade 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Before you begin the Microsoft Dynamics AX installation process, work with a system administrator to ensure that the account you log on with at each server has the following permissions that are specific to upgrade. These permissions are implemented according to the principle of least privilege.

The following table lists permissions that must be set for upgrade.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Component</p></th>
<th><p>Additional permissions required</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Upgrade checklists</p></td>
<td><p>Member of the SYSADMIN role in Microsoft Dynamics AX.</p></td>
</tr>
<tr class="even">
<td><p>Source database (the database that will be upgraded to Microsoft Dynamics AX 2012)</p></td>
<td><p>Same domain user (using Windows integrated security) must have ownership privileges on both the source Microsoft Dynamics AX and target Microsoft Dynamics AX 2012 databases.</p></td>
</tr>
</tbody>
</table>

  


