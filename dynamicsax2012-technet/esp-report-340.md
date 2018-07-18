---
title: (ESP) Report 340
TOCTitle: (ESP) Report 340
ms:assetid: f421811a-1bf3-4746-96de-7db41f21ceaa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn304985(v=AX.60)
ms:contentKeyID: 54899961
ms.date: 06/07/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TaxReportTable
- ES - 00002
- MsDynAx060.Forms.TaxReportTable
audience: Application User
ms.search.region: Spain
---

# (ESP) Report 340 


_**Applies To:** Microsoft Dynamics AX 2012_

All Spanish legal entities can generate Report 340 for vendor invoices and customer invoices monthly. You can use the **Spanish VAT reports** form to generate Report 340.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 3 for AX 2012.</P>



Before you generate the report, you can specify the operation type for VAT report lines for a legal entity. The operation type is required for record type 2. For example, if the legal entity has rented a business property, then the operation type is R.

You can also identify and include any cash amount that is received from the sale of property that exceeds a specified limit, and include it in the report.

## What are the record types for Report 340?

The Report 340 file format consists of two record types based on the structure.

  - **Type 1** – This record type contains header information about the legal entity that generates the report.

  - **Type 2** – This record type contains information about the items and services that are purchased and sold by a legal entity during a specified period. You can select the operation type identification letter for each transaction. Based on the value of the operation type, you can provide other information, such as the property tax account number of the rented property, the location code of the property, the cash amount that is received from the sale of the property, the cash amount that is subject to VAT, and the year in which the cash is received from the customer. You can enter the values in the **VAT report lines** form.

## Can I include cash prepayments and partial payments in the report?

Yes. You can include partial payments and prepayments that are made by a customer in the same way that you include standard cash payments. However, you must provide the fiscal year in which the prepayment is made and the invoice date that matches the payment. If the prepayment is made during a different year, then you must provide the payment year in the **VAT report lines** form.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

  


