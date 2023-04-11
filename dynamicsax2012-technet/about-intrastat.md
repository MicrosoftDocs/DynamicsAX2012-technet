---
title: About Intrastat
TOCTitle: About Intrastat
ms:assetid: 2d52e8cf-dcda-4f91-b410-ba3aa1b12045
ms:mtpsurl: https://technet.microsoft.com/library/Aa548435(v=AX.60)
ms:contentKeyID: 36655927
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About Intrastat 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Intrastat reporting is the system that is used to record information and generate statistics on the compulsory declaration of movements of goods to or from other Member States of the European Union (EU). Intrastat reporting is required whenever a transaction crosses the border of another EU country/region.

## General steps in the Intrastat process

The following steps illustrate the overall flow of information that is used for Intrastat reporting.

1.  Enter a transaction that crosses the border of another EU country/region. When you create a sales order, free text invoice, purchase order, or project invoice, the line transactions will be transferred to the **Intrastat** form. Information is transferred only if the **Country/region type** field in the **Vendors** or **Customers** form for the sender or receiver of the goods is **EU**. The **Transaction code** field in the **Intrastat** form is set to the default value that was specified in the **Foreign trade parameters** form. You can change the default value, and complete other Intrastat-related fields manually, before you post the invoice or receipt. When a document line is created, default entries for Intrastat-related fields are taken from the document header. You can change the information on the lines before you post the document and transfer transactions to the **Intrastat** form.

2.  Generate Intrastat transactions by using the **Intrastat** form. The information for the **Intrastat** form is found in and transferred from customer packing slip journals, vendor product receipt journals, and invoice journals in Accounts receivable, Procurement and sourcing, and Project management and accounting.

## Setup

The following steps illustrate the setup process for Intrastat.

1.  Select base data for Intrastat. This can be found in the **Address setup**, **Commodity codes**, **Transaction codes**, **Transport method**, **Port**, and **Statistics procedure** forms. In addition to this information, you can also include information about weight, origin, additional units, and charges on net amount.

2.  Set up default values for Intrastat transactions in the **Foreign trade parameters** form.

## Prerequisites for transferring transactions to the Intrastat form

The following table shows requirements that must be completed before Intrastat transactions can be generated.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Foreign trade parameters</strong> <br />
(Click <strong>Organization administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Foreign trade</strong> &gt; <strong>Foreign trade parameters</strong>.)</p></td>
<td><ol>
<li><p>Click <strong>Country/region properties</strong>.</p></li>
<li><p>In the <strong>Country/region type</strong> field, verify that the selected country/region has a value of <strong>EU</strong>.</p></li>
<li><p>Click <strong>Intrastat</strong>. On the <strong>General</strong> FastTab, in the <strong>Transaction code</strong> field, select the transaction code for sales and purchase orders.</p></li>
<li><p>Click <strong>Compress</strong>, and then select the criteria that must be identical for the compression of Intrastat order lines.</p></li>
<li><p>Click the <strong>Transfer</strong> and <strong>Check setup</strong> FastTabs, and then select other specific criteria for transferring transactions to Intrastat.</p></li>
<li><p>Click <strong>Number sequences</strong>, and then specify number sequences for foreign trade documents.</p></li>
</ol>
<div class="alert">

> [!NOTE]
> <P>The country/region that you are sending goods to or receiving goods from must be in the EU.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Address setup</strong> <br />
(Click <strong>Organization administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Addresses</strong> &gt; <strong>Address setup</strong>.)</p></td>
<td><ol>
<li><p>Click <strong>Country/region</strong>.</p></li>
<li><p>Specify the <strong>Country/region</strong> and <strong>ISO</strong> field values for the relevant countries/regions.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p><strong>Legal entities</strong> <br />
(Click <strong>Organization administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Organization</strong> &gt; <strong>Legal entities</strong>.)</p></td>
<td><ol>
<li><p>Click the <strong>Foreign trade and logistics</strong> FastTab.</p></li>
<li><p>In the <strong>VAT exempt number export</strong> field, select the tax exempt number for export (dispatches).</p></li>
<li><p>In the <strong>Branch number extension export</strong> field, specify the branch number that is used in association with the value in the <strong>VAT exempt number export</strong> field.</p></li>
<li><p>In the <strong>VAT exempt number import</strong> field, select the tax exempt number for import (arrivals).</p></li>
<li><p>In the <strong>Branch number extension import</strong> field, specify the branch number that is used in association with the value in the <strong>VAT exempt number import</strong> field.</p></li>
<li><p>In the <strong>Intrastat code</strong> field, enter the Intrastat code for the relevant countries/regions.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>Released product details</strong> <br />
(Click <strong>Product information management</strong> &gt; <strong>Common</strong> &gt; <strong>Released products</strong>. Select a record. On the <strong>Action Pane</strong>, click <strong>Edit</strong>.)</p></td>
<td><ol>
<li><p>Click the <strong>Foreign trade</strong> FastTab.</p></li>
<li><p>Select <strong>Commodity</strong>. Specify any other relevant field values.</p></li>
<li><p>Click the <strong>Manage inventory</strong> FastTab.</p></li>
<li><p>Enter a value in the <strong>Net weight</strong> field.</p></li>
</ol></td>
</tr>
<tr class="odd">
<td><p><strong>Customers</strong> <br />
(Click <strong>Accounts receivable</strong> &gt; <strong>Common</strong> &gt; <strong>Customers</strong> &gt; <strong>All customers</strong>. Select a customer account. On the <strong>Action Pane</strong>, click <strong>Edit</strong>.)</p></td>
<td><ol>
<li><p>Click the <strong>Addresses</strong> FastTab. Click <strong>Edit</strong>.</p></li>
<li><p>Select a <strong>Country/region</strong>.</p></li>
</ol></td>
</tr>
<tr class="even">
<td><p><strong>Vendors</strong> <br />
(Click <strong>Accounts payable</strong> &gt; <strong>Common</strong> &gt; <strong>Vendors</strong> &gt; <strong>All vendors</strong>. Select a vendor account. On the <strong>Action Pane</strong>, click <strong>Edit</strong>.)</p></td>
<td><ol>
<li><p>Click the <strong>Addresses</strong> FastTab. Click <strong>Edit</strong>.</p></li>
<li><p>Select a <strong>Country/region</strong>.</p></li>
</ol>
<p></p></td>
</tr>
</tbody>
</table>


## Generate Intrastat transactions

The following steps illustrate the process for generating Intrastat information for reporting.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Click the **Transfer XX** button, where **XX** is the International Organization for Standardization (ISO) code for the country/region, as specified in the **Address setup** form.

3.  Verify the types of transactions that will be included, and then click **OK**.

## See also

[Set up Intrastat from a free text invoice](set-up-intrastat-from-a-free-text-invoice.md)

[(BEL) Transfer vendor invoice transactions and generate an Intrastat declaration](bel-transfer-vendor-invoice-transactions-and-generate-an-intrastat-declaration.md)

[(FIN) Generate a Finnish Intrastat declaration](fin-generate-a-finnish-intrastat-declaration.md)

[(GBR) Create and submit an Intrastat report in the CSV02 file format](gbr-create-and-submit-an-intrastat-report-in-the-csv02-file-format.md)

[(ITA) Compress the Intrastat transactions and generate the Intrastat report](ita-compress-the-intrastat-transactions-and-generate-the-intrastat-report.md)

[(ITA) Generate, print, and export the Intrastat report](ita-generate-print-and-export-the-intrastat-report.md)

[(SWE) Generate an Intrastat file for an EU customer](swe-generate-an-intrastat-file-for-an-eu-customer.md)

[(SWE) Generate an Intrastat file for an EU vendor](swe-generate-an-intrastat-file-for-an-eu-vendor.md)

  


