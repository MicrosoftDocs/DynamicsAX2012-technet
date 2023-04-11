---
title: (RUS) Create a relationship between RCOAD and RCM codes
TOCTitle: (RUS) Create a relationship between RCOAD and RCM codes
ms:assetid: d7184331-e996-4c0f-9678-37f95c9542cf
ms:mtpsurl: https://technet.microsoft.com/library/Dn788797(v=AX.60)
ms:contentKeyID: 62518195
author: tonyafehr
ms.date: 06/27/2014
mtps_version: v=AX.60
f1_keywords:
- RCOAD code
- Classes.LedgerRCOADReplacer_RU
- Forms.LedgerRCOADtoRCM_RU
- RCOAD
- RCM code
- RCM
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a relationship between RCOAD and RCM codes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

If you are required to use the Russian Classification of Municipalities (RCM) code instead of the Russian Classification of Objects of Administrative Division (RCOAD) code, this topic explains how you can to create a relationship between RCOAD and RCM codes to replace the codes. You must specify an RCM effective date to automatically replace the RCOAD codes with the RCM codes.

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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 R3</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p>Related setup tasks</p></td>
<td><ul>
<li><p>In the <strong>Manage addresses</strong> form, on the <strong>Tax registration</strong> FastTab, in the <strong>Registration number</strong> field, enter an RCOAD code for the vendor. For more information see <a href="https://technet.microsoft.com/library/jj733401(v=ax.60)">(RUS) Manage addresses (modified form)</a>.</p></li>
<li><p>Set up a sales tax authority, a settlement period, a sales tax code, a sales tax relationship, and a budget revenue classification code. For more information, see <a href="rus-set-up-the-calculation-of-assessed-tax.md">(RUS) Set up the calculation of assessed tax</a>.</p></li>
<li><p>Set up a territory code and specify a sales tax code in the <strong>Distribution</strong> form. For more information, see <a href="rus-set-up-a-location-code-and-an-rcoad-code-to-distribute-a-fixed-asset.md">(RUS) Set up a location code and an RCOAD code to distribute a fixed asset</a> and <a href="https://technet.microsoft.com/library/jj853238(v=ax.60)">(RUS) Distribution - tax reporting (form)</a>.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## Create a relationship between RCOAD and RCM codes

Use the **RCOAD and RCM relation** form to create a relationship between RCOAD and RCM codes.

1.  Click **General ledger** \> **Setup** \> **RCOAD and RCM relation**.

2.  Click **New** to enter an RCOAD code manually.
    
    –or–
    
    Click **Load RCOAD** to automatically import the list of existing RCOAD codes.

3.  In the **RCM code** field, enter an RCM code for an RCOAD code.

4.  In the **Control sum value** field, enter the control sum value that is used to verify the RCM code.

## Replace an RCOAD code with an RCM code

To replace an RCOAD code with an RCM code, follow these steps:

1.  Click **General ledger** \> **Periodic** \> **Replace RCOAD with RCM**.

2.  In the **RCM effective date** field, specify the effective date from which the RCOAD codes are replaced with the RCM codes.

3.  Click **OK** to replace the RCOAD codes with RCM codes. The replaced RCM codes can be viewed in the following forms:
    
      - **Edit address**
    
      - **RCOAD codes**
    
      - **Distribution**

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
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must have the following roles:</p>
<ul>
<li><p><strong>Accounting manager</strong> (LedgerAccountingManager)</p></li>
<li><p><strong>Accounting supervisor</strong> (LedgerAccountingSupervisor)</p></li>
</ul>
<p>To create a relationship between RCOAD and RCM codes, you must be a member of a security role that includes <strong>Enable general ledger process</strong> (LedgerGeneralLedgerProcessEnable) duty.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To create a relationship between RCOAD and RCM codes, you must be a member of a security role that includes the following privileges:</p>
<ul>
<li><p><strong>Replace RCOAD with RCM</strong> (LedgerRCOADReplacer_RU)</p></li>
<li><p><strong>RCOAD and RCM relation</strong> (LedgerRCOADtoRCM_RU)</p></li>
</ul></td>
</tr>
</tbody>
</table>

  


