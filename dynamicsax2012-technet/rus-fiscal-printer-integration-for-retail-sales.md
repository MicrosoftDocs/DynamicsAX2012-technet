---
title: (RUS) Fiscal printer integration for retail sales
TOCTitle: (RUS) Fiscal printer integration for retail sales
ms:assetid: 54cd21aa-a998-4eb9-aea0-bcf3bf3f1634
ms:mtpsurl: https://technet.microsoft.com/library/Dn510393(v=AX.60)
ms:contentKeyID: 59944201
author: Khairunj
ms.date: 02/27/2015
mtps_version: v=AX.60
f1_keywords:
- Russia
- POS
- Fiscal printer
- fiscal printers
- fiscal receipt
- fiscal receipts
audience: Application User
ms.search.region: Russia
---

# (RUS) Fiscal printer integration for retail sales 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can register retail point of sale (POS) sales and print fiscal receipts using a certified Shtrih-M fiscal printer that is integrated with Microsoft Dynamics AX POS. You can perform the following tasks by using the fiscal printer integration:

  - Configure a fiscal printer using the POS hardware profile and the fiscal printer configuration file.

  - Configure fiscal receipt layouts and print fiscal receipts for retail POS documents.

  - Register discounted sales, sales with multiple payments, and loyalty transactions.

  - Open and close shifts at the POS by using the fiscal printer.

  - Save fiscal receipt data for the retail transactions and transfer the data to Microsoft Dynamics AX.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## What document types do fiscal printers support?

Fiscal printers support the printing of fiscal receipts for documents that are related to retail POS. You can print fiscal receipts for retail sales, item returns, starting amounts, float entries, tender removals, X-reports, and Z-reports.

## Can I register a retail sale with multiple payments using varied payment methods?

Yes. You can add items to a sales transaction at the POS and register partial payments for the sales. You can use multiple payment methods to make the partial payments. The fiscal receipt is printed for the closing transaction after the final payment for the sales transaction is completed.

## Can I configure multiple fiscal receipt layouts for POS document types?

Yes. You can configure multiple layouts for various POS document types. A document type can have only one layout. The printer configuration file may contain additional settings for all document types to use multiple fiscal receipt layouts. If additional printer settings are not specified in the printer configuration file, the default layout is used to print a fiscal receipt.

## Does the integrated fiscal printer support tax calculations?

Yes. Fiscal printers calculate taxes, and print them on a fiscal receipt. The tax transaction details are transferred to retail POS and Microsoft Dynamics AX after the calculation of taxes.

## Can I print retail discounts on a fiscal receipt?

Yes. Retail discounts can be printed on a fiscal receipt based on the layout that is configured for the receipt. You can print discounts on sales receipt lines, return receipts, and receipt totals.

## Can I print a fiscal receipt for a customer order or a customer account deposit that is paid in POS?

No. You cannot print a fiscal receipt for a customer order or a customer deposit transaction.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[(RUS) Configure fiscal printers to generate a fiscal receipt](rus-configure-fiscal-printers-to-generate-a-fiscal-receipt.md)

[Integrating Microsoft Dynamics AX for Retail POS with fiscal printers for Russia – White paper](https://mbs.microsoft.com/customersource/global/ax/support/support-news/integratingmsdynaxforposprintersrussia)

  


