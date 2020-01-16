---
title: Supported upgrade paths
TOCTitle: Supported upgrade paths
ms:assetid: db935f79-1199-4518-a588-9da4f4739cd1
ms:mtpsurl: https://technet.microsoft.com/library/Dd362093(v=AX.60)
ms:contentKeyID: 35133088
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Supported upgrade paths 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic has been updated to describe upgrades to four target Microsoft Dynamics AX versions: Microsoft Dynamics AX 2012, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 R3.


> [!IMPORTANT]
> <P>We strongly recommend that you install the most recent available version of AX 2012. If there is functionality that you do not plan to take advantage of, you can remove the appropriate License code. For example, in the case of the Feature Pack, if you do not want to use the Public Sector functionality, remove the <A href="public-sector-license-code-publicsector.md">Public sector license code (PublicSector)</A>.</P>
> <P><EM>Do not</EM> uninstall Microsoft-released models to remove unwanted functionality. This action will place your system in an unsupported state. If you have uninstalled a Microsoft-released model after installing an instance of Microsoft Dynamics AX, you must reinstall the model using the instructions found in <A href="how-to-export-and-import-a-model.md">How to: Export and Import a Model</A>.</P>



## Supported upgrade sources and targets

The following tables describe the supported methods for an upgrade to each target system.


> [!NOTE]
> <P>We recommend that you install the newest service pack or cumulative update available for your existing system before beginning an upgrade. For Microsoft Dynamics AX 4.0, this would be SP2. For Microsoft Dynamics AX 2009, this would be SP1. Information about the latest cumulative updates and hotfixes is available on CustomerSource for <A href="https://go.microsoft.com/fwlink/?linkid=329036">Microsoft Dynamics AX 2012 R2</A> and for <A href="https://go.microsoft.com/fwlink/?linkid=232954">Microsoft Dynamics AX 2012 (covering also Microsoft Dynamics AX 2012 Feature Pack)</A>.</P>




> [!WARNING]
> <P>In general, we recommend that you install the latest applicable cumulative updates to your source and target systems while upgrading. However, if you plan to upgrade to a system running CU6 for AX 2012 R2, note that certain combinations of updates require special handling. See <A href="scenario-upgrade-to-ax-2012-r2-cu6.md">Scenario: Upgrade to AX 2012 R2 + CU6</A> before proceeding.</P>



## Upgrading to AX 2012

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Source version</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AX 4.0 SP2</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="even">
<td><p>AX 2009 SP1</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
</tbody>
</table>


## Upgrading to AX 2012 Feature Pack

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Source version</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AX 4.0 SP2</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="even">
<td><p>AX 2009 SP1 (without Retail components)</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="odd">
<td><p>AX 2009 for Retail R1</p></td>
<td><p>Indirect upgrade. You must first upgrade to AX 2009 for Retail R2 Refresh. For more information, see the <a href="https://mbs.microsoft.com/customersource/downloads/servicepacks/microsoftdynamicsaxforretailcs.htm?printpage=false%26sid=sv1zlv0gdopipwyrz22i0zez%26stext=ax+for+retail">Deployment and installation Guide: Microsoft Dynamics AX for Retail</a>.</p></td>
</tr>
<tr class="even">
<td><p>AX 2009 for Retail R2</p></td>
<td><p>Indirect upgrade. You must first upgrade to AX 2009 for Retail R2 Refresh. For more information, see the <a href="https://mbs.microsoft.com/customersource/downloads/servicepacks/microsoftdynamicsaxforretailcs.htm?printpage=false%26sid=sv1zlv0gdopipwyrz22i0zez%26stext=ax+for+retail">Deployment and installation Guide: Microsoft Dynamics AX for Retail</a>.</p></td>
</tr>
<tr class="odd">
<td><p>AX 2009 for Retail R2 Refresh</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="even">
<td><p>AX 2012 (without Retail components)</p></td>
<td><p>In-place upgrade on a single system. No source-to-target workflow is used.</p></td>
</tr>
</tbody>
</table>


## Upgrading to AX 2012 R2

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Source version</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AX 4.0 R2</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="even">
<td><p>AX 2009 R1 (without Retail components)</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="odd">
<td><p>AX 2009 for Retail R1</p></td>
<td><p>Indirect upgrade. You must first upgrade to AX 2009 for Retail R2 Refresh. For more information, see the <a href="https://mbs.microsoft.com/customersource/downloads/servicepacks/microsoftdynamicsaxforretailcs.htm?printpage=false%26sid=sv1zlv0gdopipwyrz22i0zez%26stext=ax+for+retail">Deployment and installation Guide: Microsoft Dynamics AX for Retail</a>.</p></td>
</tr>
<tr class="even">
<td><p>AX 2009 for Retail R2</p></td>
<td><p>Indirect upgrade. You must first upgrade to AX 2009 for Retail R2 Refresh. For more information, see the <a href="https://mbs.microsoft.com/customersource/downloads/servicepacks/microsoftdynamicsaxforretailcs.htm?printpage=false%26sid=sv1zlv0gdopipwyrz22i0zez%26stext=ax+for+retail">Deployment and installation Guide: Microsoft Dynamics AX for Retail</a>.</p></td>
</tr>
<tr class="odd">
<td><p>AX 2009 for Retail R2 Refresh</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="even">
<td><p>AX 2012 (without Retail components)</p></td>
<td><p>In-place upgrade on a single system. No source-to-target workflow is used.</p></td>
</tr>
<tr class="odd">
<td><p>AX 2012 Feature Pack</p></td>
<td><p>In-place upgrade on a single system. No source-to-target workflow is used.</p></td>
</tr>
</tbody>
</table>


## Upgrading to AX 2012 R3

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Source version</p></th>
<th><p>Comment</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AX 4.0 SP 2</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="even">
<td><p>AX 2009 SP1 (without Retail components)</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="odd">
<td><p>AX 2009 for Retail R1</p></td>
<td><p>Indirect upgrade. You must first upgrade to AX 2009 for Retail R2 Refresh. For more information, see the <a href="https://mbs.microsoft.com/customersource/downloads/servicepacks/microsoftdynamicsaxforretailcs.htm?printpage=false%26sid=sv1zlv0gdopipwyrz22i0zez%26stext=ax+for+retail">Deployment and installation Guide: Microsoft Dynamics AX for Retail</a>.</p></td>
</tr>
<tr class="even">
<td><p>AX 2009 for Retail R2</p></td>
<td><p>Indirect upgrade. You must first upgrade to AX 2009 for Retail R2 Refresh. For more information, see the <a href="https://mbs.microsoft.com/customersource/downloads/servicepacks/microsoftdynamicsaxforretailcs.htm?printpage=false%26sid=sv1zlv0gdopipwyrz22i0zez%26stext=ax+for+retail">Deployment and installation Guide: Microsoft Dynamics AX for Retail</a>.</p></td>
</tr>
<tr class="odd">
<td><p>AX 2009 for Retail R2 Refresh</p></td>
<td><p>Direct upgrade using the source-to-target model.</p></td>
</tr>
<tr class="even">
<td><p>AX 2012 (without Retail components)</p></td>
<td><p>In-place upgrade on a single system. No source-to-target workflow is used.</p></td>
</tr>
<tr class="odd">
<td><p>AX 2012 Feature Pack</p></td>
<td><p>In-place upgrade on a single system. No source-to-target workflow is used.</p></td>
</tr>
<tr class="even">
<td><p>AX 2012 R2</p></td>
<td><p>In-place upgrade on a single system. No source-to-target workflow is used.</p></td>
</tr>
</tbody>
</table>


## Upgrading to AX 2012 R2 or AX 2012 R3 (international builds)

**Supported source-to-target upgrade paths**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th rowspan="2"> <p>
   
	 Country/region
  </p> </th>
    <th colspan="2"> <p>
   
	 Source
  </p> </th>
    <th rowspan="2"> <p>
   
	 Target
  </p> </th>
  </tr>
  <tr>
    <td> <p> <strong>AX 4.0</strong> </p> </td>
    <td> <p> <strong>AX 2009</strong> </p> </td>
  </tr>
  <tr>
    <td rowspan="2"> <p>
   
	 Brazil
  </p> </td>
    <td> <p>
   
	 Not applicable
  </p> </td>
    <td> <p>
   
	 AX 2009 SP1 + GLD_Cons + RU8 + KB 2890737 (5.0.1600.2174)
  </p> </td>
    <td rowspan="7"> <p>
   
	 AX 2012 R2/AX 2012 R3
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 AX 4.0 SP2 + Brazil FP + 362 DIS + latest DIP
  </p> </td>
    <td> <p>
   
	 AX 2009 SP1 + GLS_Cons + RU8
  </p> </td>
  </tr>
  <tr>
    <td rowspan="2"> <p>
   
	 China
  </p> </td>
    <td rowspan="2"> <p>
   
	 AX 4.0 SP2 + CN GLS
  </p> </td>
    <td> <p>
   
	 AX 2009 SP1 + GLS_Cons + RU8
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 AX 2009 SP1 + GLS_Cons + RU8 or AX 2009 SP1 + GLS_Cons + RU6 + China TR-1
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 India
  </p> </td>
    <td> <p>
   
	 AX 4.0 SP2 + IN GLS
  </p> </td>
    <td> <p>
   
	 AX 2009 SP1 + GLS_Cons + RU8
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Japan
  </p> </td>
    <td> <p>
   
	 AX 4.0 SP2 + JP GLS
  </p> </td>
    <td> <p>
   
	 AX 2009 SP1 + GLS_Cons + RU8
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Russia/Eastern Europe
  </p> </td>
    <td> <p>
   
	 AX 4.0 SP2 FP1 EE + REGFs
  </p> </td>
    <td> <p>
   
	 AX 2009 SP1 + GLS_EE + RU8
  </p> </td>
  </tr>
  <tr>
    <td> <p>
   
	 Russia (Payroll)
  </p> </td>
    <td> <p>
   
	 AX 4.0 SP2 FP1 EE + latest LOS layer
  </p> </td>
    <td> <p>
   
	 AX 2009 SP1 + RU8 + latest SL layer
  </p> </td>
    <td> <p>
   
	 AX 2012 R2/AX 2012 R3 + RU Payroll
  </p> </td>
  </tr>
</table>


**Supported in-place upgrade paths**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Country/region</p></th>
<th><p>Old AX 2012 version</p></th>
<th><p>New AX 2012 version</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>All</p></td>
<td><p>AX 2012 R2</p></td>
<td><p>AX 2012 R3</p></td>
</tr>
</tbody>
</table>


## Upgrading from a Microsoft Dynamics AX source system that uses an Oracle database

You cannot use an Oracle database together with any version of AX 2012. If you are upgrading from an installation of Microsoft Dynamics AX that uses an Oracle database, you must first migrate your data to a Microsoft SQL Server database, and then upgrade to your preferred version of AX 2012.

To migrate your data to a SQL Server database, use the Oracle to Microsoft SQL Server Data Migration Assistant for Microsoft Dynamics AX tool. You can download this tool and the *Oracle to Microsoft SQL Server Data Migration Assistant for Microsoft Dynamics AX Installation Guide* from [CustomerSource](https://mbs.microsoft.com/customersource/downloads/servicepacks/ax2009_oracletosql.htm).

  


