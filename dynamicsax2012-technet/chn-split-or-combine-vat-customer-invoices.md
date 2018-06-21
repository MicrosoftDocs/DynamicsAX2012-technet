---
title: (CHN) Split or combine VAT customer invoices
TOCTitle: (CHN) Split or combine VAT customer invoices
ms:assetid: c65960eb-0b18-445a-8128-7b4dc0502e67
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn282393(v=AX.60)
ms:contentKeyID: 54906856
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- China
- CHN
- split invoices
- CN - 00015
- Forms.TaxIntgrExportDocument_CN
- VAT customer invoices
- Forms.TaxIntgrExportDocumentSplit_CN
- merge invoices
- MsDynAx060.Forms.TaxIntgrExportDocument_CN
- MsDynAx060.Forms.TaxIntgrExportDocumentSplit_CN
---

# (CHN) Split or combine VAT customer invoices [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Follow the steps in this topic to split a value-added tax (VAT) customer invoice to create multiple invoice documents. You can also combine multiple VAT customer invoices to create one invoice export document that contains the line details of the original invoices.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## This task is part of a bigger process

The following illustration shows how the configuration of the tax integration relates to other tax integration tasks.

For an overview of the process see [(CHN) Chinese tax integration for VAT customer invoices](chn-chinese-tax-integration-for-vat-customer-invoices.md).

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
<td><p><strong>Related setup task</strong></p></td>
<td><p>Configure Microsoft Dynamics AX for tax integration. For more information, see <a href="chn-configure-tax-integration.md">(CHN) Configure tax integration</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Split a VAT customer invoice

Use the **VAT invoice integration** form to manually split a VAT customer invoice that has a total invoice amount that exceeds the amount limit that you specify in the **Maximum invoice amount** field in the **Tax integration profiles** form.

To split a VAT customer invoice, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Tax integration** \> **VAT invoice integration**.

2.  In the upper pane, select a VAT customer invoice to split. You can split VAT customer invoices for which the **Over amount limit** check box is selected.

3.  Click **Split** to open the **Split export documents** form.

4.  In the **Split based on** field, select one of the following options to indicate the method to use to split the VAT customer invoice:
    
      - **Amount** – Split the invoice based on the amounts that you specify. You can specify the split amounts in the **Amount** field in the lower pane, and then click **Split** to split the invoice.
    
      - **Percent** – Split the invoice based on the percentages that you specify. You can specify the split percentages in the **Percent** field in the lower pane, and then click **Split** to split the invoice.
    
      - **Quantity** – Split the invoice based on the quantities that you specify. Click **Split**, and then specify the split quantities in the **Split quantity** field. Click **OK**.

5.  In the **Split export documents** form, click **OK**. The split invoices are updated in the **VAT invoice integration** form.

## 2\. Split VAT customer invoices automatically

Use the **VAT invoice integration** form to split multiple customer invoices based on the value that you specified in the **Maximum invoice amount** field in the **Tax integration profiles** form.

To split VAT customer invoices automatically, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Tax integration** \> **VAT invoice integration**.

2.  Click **Automatic split**.

3.  Specify the criteria to select multiple VAT customer invoices to split.

4.  Click **OK** to split the selected VAT customer invoices. The VAT customer invoices that have a value that exceeds the maximum invoice amount that you specified in the **Maximum invoice amount** field in the **Tax integration profiles** form are split until the value of each split invoice is less than the maximum invoice amount.

## 3\. Combine VAT customer invoices

Use the **VAT invoice integration** form to combine VAT customer invoices to create one invoice. You can only combine VAT customer invoices that use the same invoice account number and sales tax code.

To combine VAT customer invoices, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Tax integration** \> **VAT invoice integration**.

2.  In the upper pane, select the VAT customer invoices to combine.

3.  Click **Merge** to combine the selected invoices.

## 4\. Combine VAT customer invoices automatically

Use the **VAT invoice integration** form to combine multiple customer invoices based on the value that you specified in the **Maximum invoice amount** field in the **Tax integration profiles** form.

To merge VAT customer invoices automatically, follow these steps:

1.  Click **Accounts receivable** \> **Periodic** \> **Tax integration** \> **VAT invoice integration**.

2.  Click **Automatic merge**.

3.  Specify the criteria to select multiple VAT customer invoices to combine.

4.  Click **OK** to combine selected VAT customer invoices. The VAT customer invoices that have a value that is less than the maximum invoice amount that you specified in the **Maximum invoice amount** field in the **Tax integration profiles** form are combined until the value of combined invoices is less than the maximum invoice amount.

## Next step

[(CHN) Export VAT customer invoices or import invoice reference numbers](chn-export-vat-customer-invoices-or-import-invoice-reference-numbers.md)

## Related tasks

[(CHN) Chinese tax integration for VAT customer invoices](chn-chinese-tax-integration-for-vat-customer-invoices.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

