---
title: 'Scenario: Upgrade a country-specific or region-specific system'
TOCTitle: 'Scenario: Upgrade a country-specific or region-specific system'
ms:assetid: cead63b6-d48b-4e97-821e-d41e1b3ca152
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn198674(v=AX.60)
ms:contentKeyID: 53874074
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Scenario: Upgrade a country-specific or region-specific system [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This scenario applies to systems that contain country-specific or region-specific features that were previously located in the GLS layer. It describes an upgrade from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012 R2. Note that this country-specific or region-specific scenario requires a type of source-to-target upgrade. In-place upgrade of country-specific or region-specific features to AX 2012 R2 is not supported, nor is source-to-target upgrade to earlier releases of AX 2012.

## Upgrading (GLS) Microsoft Dynamics AX 4.0 or (GLS) Microsoft Dynamics AX 2009 to AX 2012 R2 or AX 2012 R3

## Country-specific or region-specific upgrade paths

For information about the upgrade paths that are supported for country-specific or region-specific upgrades to AX 2012 R2 or AX 2012 R3, see [Supported upgrade paths](supported-upgrade-paths.md).

## Country-specific or region-specific XPO files

Before you upgrade Microsoft Dynamics AX 4.0 and AX 2009 systems that have country-specific or region-specific (GLS) support, you must install additional XPO files on the source system. These files provide forms and functionality that are required to preprocess country-specific or region-specific data. For a list of the available XPO files and their applicability, see [Install optional upgrade XPO files](install-optional-upgrade-xpo-files.md).

## Preprocessing upgrade checklist: Tasks

On systems that include country-specific or region-specific functionality, the **Preprocessing upgrade checklist** includes additional tasks. The following table includes links to topics that explain each task and provide instructions for completing them.

Except for the tasks in this table, the procedures for country-specific or region-specific upgrades are identical to the procedures for source-to-target upgrades. For information about the procedures for source-to-target upgrades, see [Scenario: Upgrade AX 4.0 or AX 2009 to AX 2012 (all versions)](scenario-upgrade-ax-4-0-or-ax-2009-to-ax-2012-all-versions.md).

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><img src="images/Dn198674.Upgrade_checkbox_checked(AX.60).png" title="Checked checkbox" alt="Checked checkbox" /></p></th>
<th><p>Task</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/jj713622(v=ax.60)">(BRA) Legal text ID validation (form)</a></p></td>
</tr>
<tr class="even">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="bra-cfop-code-upgrade.md">(BRA) CFOP code (upgrade)</a></p></td>
</tr>
<tr class="odd">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="bra-i-e-numbers.md">(BRA) I.E. Numbers</a></p></td>
</tr>
<tr class="even">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="bra-cfop-matrix-upgrade.md">(BRA) CFOP matrix (upgrade)</a></p></td>
</tr>
<tr class="odd">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="bra-update-document-model-in-fiscal-document-type.md">(BRA) Update document model in fiscal document type</a></p></td>
</tr>
<tr class="even">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="bra-update-incoming-fiscal-document-models.md">(BRA) Update incoming fiscal document models</a></p></td>
</tr>
<tr class="odd">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="bra-operation-type.md">(BRA) Operation type</a></p></td>
</tr>
<tr class="even">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="chn-tax-registration-types.md">(CHN) Tax registration types</a></p></td>
</tr>
<tr class="odd">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="jpn-configure-for-bill-of-exchange-upgrade.md">(JPN) Configure for bill of exchange upgrade</a></p></td>
</tr>
<tr class="even">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="jpn-configure-for-bill-of-exchange-upgrade.md">(JPN) Configure for bill of exchange upgrade</a></p></td>
</tr>
<tr class="odd">
<td><p><img src="images/Dn198674.Upgrade_checkbox_cleared(AX.60).png" title="Unchecked checkbox" alt="Unchecked checkbox" /></p></td>
<td><p><a href="eeur-rus-generate-upgrade-configuration-macro.md">(EEUR, RUS) Generate upgrade configuration macro</a></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

