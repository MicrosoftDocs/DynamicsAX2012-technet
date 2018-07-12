---
title: (HUN) Itemized VAT statement
TOCTitle: (HUN) Itemized VAT statement
ms:assetid: f97eeae0-40e2-4cd2-bdd5-f0fc943ce65b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn313051(v=AX.60)
ms:contentKeyID: 54936298
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Itemized VAT statement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Itemized value-added tax (VAT) statements are additional reports that can be generated and submitted to the tax authorities along with standard VAT statements. An itemized VAT statement includes a sheet that displays a summary of the VAT transactions that are listed on the report, along with other sheets that contain detailed information about invoice transactions. The invoices that make up the itemized VAT statement are categorized according to the sales partner or purchase partner with whom you perform the transaction.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012 R2.</P>



## What types of invoices require an itemized VAT statement?

If an invoice’s total amount exceeds the limit that you specify in the **Itemized VAT statement limit (HUF)** field in the **General ledger parameters** form, the invoice requires an itemized VAT statement. You can generate an itemized VAT statement for the following types of invoices:

  - Project invoices

  - Purchase invoices

  - Sales invoices

  - Correction invoices

## Which exchange rate can I use to calculate current amounts while posting transactions to the general ledger?

An exchange rate must be specified for your currency to ensure that transaction amounts post to the general leger correctly. You can specify the exchange rate that is used by your company’s credit institution, or the exchange rate that is provided by your country’s national bank.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(HUN) Set up and generate an itemized VAT statement](hun-set-up-and-generate-an-itemized-vat-statement.md)

  


