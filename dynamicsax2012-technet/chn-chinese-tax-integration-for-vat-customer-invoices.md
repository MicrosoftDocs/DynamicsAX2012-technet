---
title: (CHN) Chinese tax integration for VAT customer invoices
TOCTitle: (CHN) Chinese tax integration for VAT customer invoices
ms:assetid: 643a344c-513b-4928-8058-f554eaacdbc4
ms:mtpsurl: https://technet.microsoft.com/library/Dn282392(v=AX.60)
ms:contentKeyID: 54906855
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- China
- CHN
- CN - 00015
- Golden tax system
- tax integration
- VAT customer invoices
audience: Application User
ms.search.region: China (PRC)
---

# (CHN) Chinese tax integration for VAT customer invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can generate value-added tax (VAT) customer invoices, and then export them as text files. You can then import reference numbers for the VAT customer invoices that can be linked to the original invoices.

Before you export a VAT customer invoice, you can split the VAT customer invoice to create multiple invoice documents. You can also combine multiple VAT customer invoices to create one invoice export document that contains the line details of the original invoices.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## What is a VAT customer invoice?

A VAT customer invoice is generated when you post a customer transaction that uses the sales tax group for VAT and the item sales tax group for VAT. You can generate a VAT customer invoice from a sales order, a return sales order, a credit note, a free text invoice, or a project sales invoice.

## Can I create one tax integration profile for multiple types of documents?

Yes. You can create one tax integration profile for multiple types of documents.

## When should I split a VAT customer invoice?

You should split a VAT customer invoice if the **Over amount limit** check box is selected in the **VAT invoice integration** form. The **Over amount limit** check box is selected for the invoices that have a total invoice amount that exceeds the amount limit that you specify in the **Maximum invoice amount** field in the **Tax integration profiles** form.

## Which VAT customer invoices can I combine?

You can combine VAT customer invoices that use the same invoice account number and sales tax code.

## How many times can I export an invoice?

You can export an invoice only one time.

## When I run the data upgrade after installing Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2, I get an error that states that all invoices are not exported. How do I solve this issue?

To fix this issue, you can run the TaxExportInvoiceTaxIntegration\_CN class to export these remaining invoices. You can then run the data upgrade again. For more information, go to [TaxExportInvoiceTaxIntegration\_CN Class](https://msdn.microsoft.com/library/jj745814.aspx).

## Can I customize information or add new information on VAT customer invoices?

Yes. You can customize VAT customer invoices by adding other fields, and then export the VAT customer invoices as text files. Perform the following steps to customize VAT customer invoices to include other details.

1.  If the information is available in the default data set, perform the following steps:
    
    1.  Press CTRL + D to open the **Developer console**, in the Application Object Tree (**AOT**) node, expand the **Data dictionary** node, the **Maps** node, the **TaxIntgrExportDocumentLineSourceMap\_CN** node, and the **Mappings** node.
    
    2.  Expand the table, and then select the field for which you want to use different information.
    
    3.  In the **Properties** window, in the **MapFieldTo** field, select the field that you want to replace the relationship with.
    
    –or–
    
    If the information is not available in the default dataset, perform the following steps:
    
    1.  Press CTRL + D to open the **Developer console**, expand the **AOT** node, and then expand the **Classes** node and the **TaxIntgrExportDocumentExporter\_CN** node.
    
    2.  Right-click the TaxIntgrExportDocumentExporter\_CN.doPopulateExportData() method, and then click **View code**.
    
    3.  Replace the default fields in Documentview with the ones you want to include. For example, to replace customer name with customer account, change the code line headerTmp.InvoiceInfo += documentView.CustName; to headerTmp.InvoiceInfo += documentView.CustAccount;

2.  Restart the Application Object Server (AOS).

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(CHN) Configure tax integration](chn-configure-tax-integration.md)

[(CHN) Export VAT customer invoices or import invoice reference numbers](chn-export-vat-customer-invoices-or-import-invoice-reference-numbers.md)

[(CHN) Split or combine VAT customer invoices](chn-split-or-combine-vat-customer-invoices.md)

  


