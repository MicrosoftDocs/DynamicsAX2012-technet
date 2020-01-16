---
title: Install optional upgrade XPO files
TOCTitle: Install optional upgrade XPO files
ms:assetid: 1f18c5d6-dddd-449b-8c11-f2cb8cf6fdfa
ms:mtpsurl: https://technet.microsoft.com/library/Hh286325(v=AX.60)
ms:contentKeyID: 36609708
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# Install optional upgrade XPO files 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 R3.</P>



Some optional features of Microsoft Dynamics AX require that additional XPO files be installed before preprocessing for a data upgrade can start. We recommend that you import these files only if the associated feature is installed on your source Microsoft Dynamics AX system, and you want to migrate the data for the feature to AX 2012. The XPO files contain upgrade scripts and forms that are required to prepare the data in your source system for upgrade. These optional XPO files must be installed *after* the XPO files for the upgrade framework have been installed.

This topic describes the XPO files for optional features of Microsoft Dynamics AX. The topic also describes the XPO files that are related to batch processing. These files are used to roll back any customizations that you have made to your batch processing class.

## XPO files for optional features

The XPO files for optional features, just like the XPO files for the upgrade framework, are specific to an earlier version of Microsoft Dynamics AX. The correct version is indicated in the file name as follows:

  - AX 4.0: “AX4” or “AX40”

  - AX 2009: “AX5” or “AX50”

All these files are located in the DatabaseUpgrade\\XPO folder on the installation media.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Feature</p></th>
<th><p>Minimum requirements</p></th>
<th><p>XPO files</p></th>
<th><p>Components that are provided</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Payroll</p></td>
<td><p>Payroll for AX 2009</p></td>
<td><p><strong>Provided in AX 2012 R2 and AX 2012 R3</strong></p>
<p>UpgradeAX5_Payroll.xpo</p></td>
<td><ol>
<li><p>Additional tasks on the Preprocessing upgrade checklist for Payroll</p></li>
<li><p>Preprocessing upgrade scripts for Payroll</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p>Retail</p></td>
<td><p>AX 2009 for Retail</p></td>
<td><p><strong>Provided in AX 2012 Feature Pack:</strong></p>
<p>SharedProject_AX50PreUpgrade_Retail.xpo</p>
<p><strong>Provided in AX 2012 R2 and AX 2012 R3:</strong></p>
<p>UpgradeAX5_Retail.xpo</p></td>
<td><ul>
<li><p>Additional tasks on the <strong>Preprocessing upgrade checklist</strong> for Retail</p></li>
<li><p>User input forms that are opened by the new checklist tasks.</p></li>
<li><p>Preprocessing upgrade scripts for Retail.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Lean manufacturing</p></td>
<td><p>Lean manufacturing for AX 2009</p></td>
<td><p><strong>Provided in AX 2012 Feature Pack, AX 2012 R2, and AX 2012 R3:</strong></p>
<p>SharedProject_AX50PreUpgrade_Lean.xpo</p></td>
<td><ul>
<li><p>Additional tasks on the <strong>Preprocessing upgrade checklist</strong> for lean manufacturing.</p></li>
<li><p>User input forms that are opened by the new checklist tasks.</p></li>
<li><p>Preprocessing upgrade scripts for lean manufacturing.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Process manufacturing production and logistics</p></td>
<td><p>Process Industries for AX 4.0 SP2 or Process Industries for AX 2009</p></td>
<td><p><strong>Provided inAX 2012 Feature Pack, AX 2012 R2, and AX 2012 R3:</strong></p>
<p>PI_UpgradeAX4.xpo</p>
<p>PI_UpgradeAX5.xpo</p></td>
<td><ul>
<li><p>An additional task on the <strong>Preprocessing upgrade checklist</strong> for process manufacturing.</p></li>
<li><p>A user input form that is opened by the new checklist task.</p></li>
<li><p>Preprocessing upgrade scripts for process manufacturing.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Project Management and Accounting add-in</p></td>
<td><p>Professional Services Automation for AX 4.0 SP2 or Professional Services Automation 2009 RU4 for AX 2009</p></td>
<td><p><strong>Provided in AX 2012 Feature Pack, AX 2012 R2, and AX 2012 R3:</strong></p>
<p>UpgradeAX4_SI.xpo</p>
<p>UpgradeAX5_SI.xpo</p></td>
<td><ul>
<li><p>For AX 4.0, a modified upgrade script.</p></li>
<li><p>For AX 2009, an additional upgrade readiness script.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Country-specific Brazil)</p></td>
<td><p>AX 4.0 SP2 + Brazil FP + 362 DIS + latest DIP</p></td>
<td><p><strong>Provided in AX 2012 R2 and AX 2012 R3:</strong></p>
<p>UpgradeAX4_GBR.xpo</p></td>
<td><p>Additional or modified upgrade preprocessing tasks, forms, and scripts that support functionality that is specific to Brazil:</p>
<ul>
<li><p>Upgrade support for fiscal operation (CFOP) codes in purchase and sales orders.</p></li>
<li><p>Location type “Outside Brazil” changed to “Outside country.”</p></li>
<li><p>Addition of transaction type “Tax fiscal document.”</p></li>
<li><p>Validation of legal text IDs in fiscal documents.</p></li>
<li><p>Validation of tax registration (I.E.) numbers.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Country-specific (China)</p></td>
<td><p>AXC 4.0 SP2 + CN GLS</p></td>
<td><p><strong>Provided in AX 2012 R2 and AX 2012 R3:</strong></p>
<p>UpgradeAX4_GCN.xpo</p></td>
<td><p>Additional or modified upgrade preprocessing tasks, forms, and scripts that support functionality that is specific to China:</p>
<ul>
<li><p>Upgrade support for VAT registration numbers.</p></li>
<li><p>Enhancements of tax integration feature to reduce AIF setup workload.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Country-specific (India)</p></td>
<td><p>AX 4.0 SP2 + IN GLS</p></td>
<td><p><strong>Provided in AX 2012 R2 and AX 2012 R3:</strong></p>
<p>UpgradeAX4_GIN.xpo</p></td>
<td><p>Additional or modified upgrade preprocessing scripts that support functionality that is specific to India.</p></td>
</tr>
<tr class="odd">
<td><p>Country-specific (Russia and Eastern Europe)</p></td>
<td><p>AX 4.0 SP2 FP1 EE + REGFs</p></td>
<td><p><strong>Provided in AX 2012 R2 and AX 2012 R3:</strong></p>
<p>UpgradeAX4_GLS_EE.xpo</p>
<p>UpgradeAX5_GLS_EE.xpo</p></td>
<td><p>Additional or modified upgrade preprocessing tasks, forms, and scripts that support functionality that is specific to Russia and Eastern Europe:</p>
<ul>
<li><p>Configuration macro task added to reconcile RU and EE Upgrade preprocessing scripts.</p></li>
<li><p>Upgrade support for number sequences.</p></li>
<li><p>Enhanced upgrade support for financial dimension framework.</p></li>
<li><p>Support for increasing the string size of extended data types during upgrade.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Country-specific (Japan)</p></td>
<td><p>AX 4.0 SP2 + JP GLS</p></td>
<td><p><strong>Provided in AX 2012 R2 and AX 2012 R3:</strong></p>
<p>UpgradeAX4_GJP.xpo</p>
<div class="alert">

> [!NOTE]
> <P>This package corresponds to the Japan functionality contained in UpgradeAX5_GLS_Cons.xpo, below.</P>


</div></td>
<td><p>Additional or modified upgrade preprocessing tasks, forms, and scripts that support functionality that is specific to Japan:</p>
<ul>
<li><p>Enhancements to bill-of-exchange support.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>Country-specific (China, Japan, Brazil, and India)</p></td>
<td><ul>
<li><p>China: AX 2009 SP1 + GLS_Cons + RUx</p>
<p>–or–</p>
<p>AX 2009 SP1 + GLS_Cons + RU7 or latest + China TR-1</p></li>
<li><p>Japan: AX 2009 SP1 + GLS_Cons + RUx</p></li>
<li><p>Brazil: AX 2009 SP1 + GLS_Cons + RUx</p></li>
<li><p>India: AX 2009 SP1 + GLS_Cons + RUx</p></li>
</ul>
<p></p></td>
<td><p><strong>Provided in AX 2012 R2 and AX 2012 R3:</strong></p>
<p>UpgradeAX5_GLS_Cons.xpo</p>
<div class="alert">

> [!NOTE]
> <P>Functionality for Japan delivered in this package corresponds to UpgradeAX4_GJP.xpo, above.</P>


</div></td>
<td><p>Additional or modified upgrade preprocessing tasks, forms, and scripts that support functionality that is specific to China, Japan, Brazil, and India.</p>
<p>The package includes the following functionality for Japan:</p>
<ul>
<li><p>Enhancements to bill-of-exchange support.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Country-specific (Russia)</p></td>
<td><p>AX 4.0 SP2 FP1 EE + RUHRP</p></td>
<td><p><strong>Provided in AX 2012 R2 only:</strong></p>
<p>SharedProject_AX40PreUpgrade_CISPayroll.xpo</p>
<p>SharedProject_AX50PreUpgrade_CISPayroll.xpo</p></td>
<td><p>Additional or modified upgrade preprocessing form elements and scripts that support functionality that is specific to Russia.</p>
<p>The package includes the following functionality for Russia:</p>
<ul>
<li><p>Payroll support</p></li>
</ul>
<div class="alert">

> [!IMPORTANT]
> <P>Before installing the XPO for this feature, install either UpgradeAX4_GLS_EE.xpo or UpgradeAX5_GLS_EE.xpo as appropriate.</P>


</div></td>
</tr>
</tbody>
</table>


## XPO files for batch processing

XPO files that are related to batch processing are included in the DatabaseUpgrade\\XPO folder in AX 2012 Feature Pack, AX 2012 R2, and AX 2012 R3. One file is included for each upgrade path that is supported:

  - PrivateProject\_Ax40PreUpgradeFramework\_Batch.xpo

  - PrivateProject\_Ax50PreUpgradeFramework\_Batch.xpo

These XPO files roll back any customizations that you have made to the batch processing class on your source Microsoft Dynamics AX system. To minimize downtime during data preprocessing, we recommend that you import the appropriate XPO file for your system.

  


