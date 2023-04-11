---
title: 'Scenario: Upgrade to AX 2012 R2 + CU6'
TOCTitle: 'Scenario: Upgrade to AX 2012 R2 + CU6'
ms:assetid: bf50d3ce-709d-4495-848a-c615910607b6
ms:mtpsurl: https://technet.microsoft.com/library/Dn313122(v=AX.60)
ms:contentKeyID: 54940412
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Scenario: Upgrade to AX 2012 R2 + CU6 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

If you plan to install Cumulative Update 6 (CU6) for Microsoft Dynamics AX 2012 R2 as part of an upgrade, you should review this topic to avoid potential problems on your upgraded system. This topic covers both source-to-target and in-place upgrade scenarios involving CU6 for Microsoft Dynamics AX 2012 R2.

## Preserve element IDs during upgrade to CU6

While upgrading from Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack to Microsoft Dynamics AX 2012 R2, you can install all of the applicable cumulative updates at one time using slipstreaming. However, certain combinations of cumulative updates require you to take extra precautions to preserve consistent element IDs in the upgraded Microsoft Dynamics AX system. This topic describes those scenarios and provides a SQL script which you will run manually again your upgraded Microsoft Dynamics AX 2012 R2 model store to restore correct element IDs.

## Overview of available cumulative updates

The following table lists the cumulative updates released for each version of Microsoft Dynamics AX 2012 through Microsoft Dynamics AX 2012 R2 CU6. Cumulative updates for Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 Feature Pack are a single series and are applicable to both versions. Microsoft Dynamics AX 2012 Feature Pack was released with CU2 was integrated into it.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Microsoft Dynamics AX 2012</p></th>
<th><p>Microsoft Dynamics AX 2012 Feature Pack</p></th>
<th><p>Microsoft Dynamics AX 2012 R2</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>CU1</p></td>
<td><p>(CU2 built in)</p></td>
<td><p>CU1</p></td>
</tr>
<tr class="even">
<td><p>CU2</p></td>
<td><p>CU3</p></td>
<td><p>CU6</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>CU4</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>CU5</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


The following configurations cannot to upgraded to Microsoft Dynamics AX 2012 R2 + CU6 without additional steps.

  - Microsoft Dynamics AX 2012 + CU4

  - Microsoft Dynamics AX 2012 + CU5

  - Microsoft Dynamics AX 2012 Feature Pack + CU4

  - Microsoft Dynamics AX 2012 Feature Pack + CU5

If your upgrade scenario involves upgrading to Microsoft Dynamics AX 2012 R2 + CU6 from any of these configurations, see [SQL patch script for AX 2012 R2 + CU6 upgrade scenarios](fix-element-ids-sql-patch-script-for-ax-2012-r2-cu6-upgrade-scenarios.md) for instructions.

## Apply CU6 to CHN environments

This section provides China-specific information needed to install CU6 for Microsoft Dynamics AX 2012 R2 as a part of upgrade from the following Microsoft Dynamics AX versions and configurations:

  - Microsoft Dynamics AX 2009 GLS with Chinese tax integration

  - Microsoft Dynamics AX 2012 R2 with Chinese tax integration

  - Microsoft Dynamics AX 2012 R2 with CU1 and Chinese tax integration

On systems with tax integration for China, you must export external invoices before you upgrade from Microsoft Dynamics AX 2009 GLS or install updates to Microsoft Dynamics AX 2012 R2. Unless you do this, jobs related to the updateExternalInvoice\_CN class will fail during data upgrade postsynchronization and block other jobs from continuing.

Two solutions are available:

**Solution 1:** Export the external invoices manually before installing CU6.

1.  In Microsoft Dynamics AX 2009, click **Accounts receivable** \> **Periodic** \> **Export to file**.

2.  In Microsoft Dynamics AX 2012 R2: Click **Accounts receivable** \> **Periodic** \> **Tax integration** \> **Export to file**.

**Solution 2:** If you upgraded without exporting the external invoices and encountered an error stating that all invoices are not exported, you can manually run the TaxExportInvoiceTaxIntegration\_CN class to export all the remaining external invoices. Then rerun the data upgrade.

For additional troubleshooting information, see [(CHN) Chinese tax integration for VAT customer invoices](chn-chinese-tax-integration-for-vat-customer-invoices.md) and [(CHN) Configure tax integration](chn-configure-tax-integration.md).

  


