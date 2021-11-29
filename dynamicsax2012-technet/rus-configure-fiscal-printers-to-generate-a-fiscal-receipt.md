---
title: (RUS) Configure fiscal printers to generate a fiscal receipt
TOCTitle: (RUS) Configure fiscal printers to generate a fiscal receipt
ms:assetid: 6bf3a747-fc4c-4bf4-9481-1286ac51ff07
ms:mtpsurl: https://technet.microsoft.com/library/Dn510394(v=AX.60)
ms:contentKeyID: 59944202
author: Khairunj
ms.date: 09/26/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.RetailHardwareProfile
- Forms.RetailTransactionTable
- Russia
- POS
- fiscal printer
- fiscal printers
- fiscal receipt
- fiscal receipts
audience: Application User
ms.search.region: Russia
---

# (RUS) Configure fiscal printers to generate a fiscal receipt 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to configure a certified Shtrih-M fiscal printer, create fiscal printer configurations, and maintain fiscal printer configuration files in Microsoft Dynamics AX. You can register retail point of sale (POS) sales, and then print fiscal receipts using the Shtrih-M fiscal printer.

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
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later and hotfix KB2968462</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
</tbody>
</table>


## Configure fiscal printer settings in the Hardware profiles form

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Hardware profiles**.

2.  Create a new hardware profile. For more information, see [Set up hardware profiles](set-up-hardware-profiles.md).

3.  On the **Fiscal printer** FastTab, in the **Fiscal printer** field, select **Third-party driver**.

4.  In the **Device name** field, enter the name of the fiscal printer.

5.  In the **Description** field, enter a description for the fiscal printer.

## Create fiscal printer configurations and import fiscal printer configuration files

Use the **Fiscal register configurations** form to create fiscal printer configurations and import fiscal printer configuration files.

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Fiscal register configurations**.

2.  Click **New** to create a new fiscal printer configuration.

3.  Enter an identifier and description for the fiscal printer configuration.

4.  Click **Import**, and then specify the filename and path of the configuration file that you want to import. You can preview the imported configuration file on the **Preview** FastTab.

## If required: Export fiscal printer configuration files

Use the **Fiscal register configurations** form to export a fiscal printer configuration file. You can also export a sample configuration file that is created based on the template that is stored in the Application Object Tree (AOT).

1.  Click **Retail** \> **Setup** \> **POS** \> **Profiles** \> **Fiscal register configurations**.

2.  Select a fiscal printer configuration, and then click **Export**. Specify the file name and path to export a fiscal printer configuration file.

3.  Optional: Click **Export sample configuration**, and then specify the file name and path to export a sample fiscal printer configuration file.

## If required: View the fiscal memory data in the Retail store transactions form

1.  Register a sales transaction in retail POS to generate a fiscal receipt. For more information, see [Point of Sale for Microsoft Dynamics AX Retail](point-of-sale.md).

2.  Click **Retail** \> **Inquiries** \> **Retail store transactions**.

3.  On the **Fiscal memory data** FastTab, verify the fiscal memory data for a fiscal receipt.
    
    The following table provides descriptions of the fields on the **Fiscal memory data** FastTab.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Shift ID</strong></p></td>
    <td><p>The unique identification code of the fiscal printer shift.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>CCK number</strong></p></td>
    <td><p>The Cryptographic Control Key (CCK) number that is assigned to the fiscal receipt by the fiscal printer.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>ESCT factory number</strong></p></td>
    <td><p>The factory number of the Electronic Storage Controlling Tape (ESCT) that is assigned to the fiscal receipt by the fiscal printer.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Document serial number</strong></p></td>
    <td><p>The serial number of the fiscal receipt that is assigned by the fiscal printer.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Printer serial number</strong></p></td>
    <td><p>The serial number of the fiscal printer.</p></td>
    </tr>
    </tbody>
    </table>

  


