---
title: (CHN) Configure tax integration
TOCTitle: (CHN) Configure tax integration
ms:assetid: 76f2f5f7-741b-477c-b5fe-1532001ffec1
ms:mtpsurl: https://technet.microsoft.com/library/Dn304990(v=AX.60)
ms:contentKeyID: 54899997
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- China
- Forms.TaxProfileTable_CN
- CHN
- CN - 00015
- Golden tax
- Golden tax system
- tax integration
- MsDynAx060.Forms.TaxProfileTable_CN
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Configure tax integration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you export value-added tax (VAT) customer invoices or import VAT customer invoice reference numbers, you must configure tax integration. Follow the steps in this topic to configure Microsoft Dynamics AX for tax integration.

## This task is part of a bigger process

The following illustration shows how the configuration of tax integration relates to other tax integration tasks.

For an overview of the process, see [(CHN) Chinese tax integration for VAT customer invoices](chn-chinese-tax-integration-for-vat-customer-invoices.md).

![Chinese tax integration for VAT customer invoices](images/Dn304990.ChinaTaxIntegration(AX.60).gif "Chinese tax integration for VAT customer invoices")

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
<td><p><strong>Installation task</strong></p></td>
<td><p>In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: If the data upgrade for external invoices did not complete after installing Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2, you can run the TaxExportInvoiceTaxIntegration_CN class to export the remaining external invoices, and then run the data upgrade again. For more information, go to <a href="https://msdn.microsoft.com/library/jj745814.aspx">TaxExportInvoiceTaxIntegration_CN Class</a>.</p></td>
</tr>
<tr class="even">
<td><p><strong>Related setup tasks</strong></p></td>
<td><p>Create a sales tax code for VAT. For more information, see <a href="set-up-and-use-sales-tax-codes.md">Set up and use sales tax codes</a>.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Create a sales tax group and attach the sales tax code for VAT to the sales tax group. For more information, see <a href="set-up-and-use-a-sales-tax-group.md">Set up and use a sales tax group</a> and <a href="https://technet.microsoft.com/library/aa498345(v=ax.60)">Sales tax groups (form)</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Create an item sales tax group and attach the sales tax code for VAT to the item sales tax group. For more information, see <a href="create-item-sales-tax-groups.md">Create item sales tax groups</a> and <a href="https://technet.microsoft.com/library/aa615960(v=ax.60)">Item sales tax groups (form)</a>.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Add the sales tax group for VAT as the default sales tax group for each customer. For more information, see <a href="set-up-a-default-tax-profile-for-a-customer-or-vendor.md">Set up a default tax profile for a customer or vendor</a>.</p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Add the item sales tax group for VAT as the default item sales tax group for each item. For more information, see <a href="set-up-default-item-sales-tax-groups-for-an-item.md">Set up default item sales tax groups for an item</a>.</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Select the <strong>Integration with tax system</strong> check box in the <strong>Accounts receivable parameters</strong> form. For more information, see <a href="https://technet.microsoft.com/library/jj664148(v=ax.60)">(CHN) Accounts receivable parameters (modified form)</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up a tax integration profile

Use the **Tax integration profiles** form to set up a tax integration profile to use for VAT customer invoices. You can specify the maximum amount for a VAT customer document.

To set up a tax integration profile, follow these steps:

1.  Click **Accounts receivable** \> **Setup** \> **Tax integration** \> **Tax integration profiles**.

2.  Select or create a tax integration profile, and then set up the inbound and outbound ports for the tax integration profile. For more information, see [(CHN) Tax integration profiles (form)](https://technet.microsoft.com/library/jj664013\(v=ax.60\)).

3.  In the **Sales tax code** field, select a sales tax code for the tax integration profile. The sales tax code that you select is used to group and combine the invoices. The sales tax code also determines whether a customer invoice is integrated with the external invoice system and whether it will be exported.

4.  In the **Maximum invoice amount** field, enter the maximum amount limit for a VAT customer document that you export.

5.  In the **Maximum invoice lines** field, enter the maximum number of lines that can be included on a VAT customer document that you export.

6.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: Perform the following steps.
    
    1.  Select the **Validate amount limit** check box to post only the invoices that have a total amount that is lower than the amount that you specify in the **Maximum invoice amount** field.
    
    2.  Select the **Split during posting** check box to split invoices that have a total amount that exceeds the amount that you specify in the **Maximum invoice amount** field before you post the invoice. You can select this check box only if you select the **Validate amount limit** check box.
    
    3.  In the **Invoice auditor** field, select the name of the person who audits the invoices.
    
    4.  In the **Payment collector** field, select the name of the person who collects the invoice payments.
    
    5.  On the **Default value of description and unit** FastTab, perform the following steps for each source document that you export using the tax integration profile:
        
        1.  Click **New** to create a record.
        
        2.  In the **Name** field, select the source document to export.
        
        3.  In the **Description** field, enter the default description for the export file.
        
        4.  In the **Unit** field, select the default unit for the export file.

## Next step

[(CHN) Export VAT customer invoices or import invoice reference numbers](chn-export-vat-customer-invoices-or-import-invoice-reference-numbers.md)

## Related tasks

[(CHN) Chinese tax integration for VAT customer invoices](chn-chinese-tax-integration-for-vat-customer-invoices.md)

[Sales tax codes (form)](https://technet.microsoft.com/library/aa553257\(v=ax.60\))

  


