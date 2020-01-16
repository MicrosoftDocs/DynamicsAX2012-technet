---
title: Enter a vendor payment that is subject to withholding tax
TOCTitle: Enter a vendor payment that is subject to withholding tax
ms:assetid: b4e65486-2e7e-49f6-9d75-8f177dd9cd13
ms:mtpsurl: https://technet.microsoft.com/library/Gg232420(v=AX.60)
ms:contentKeyID: 37822155
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Enter a vendor payment that is subject to withholding tax 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to enter the information that is required for a vendor payment that is subject to withholding tax. For example, in Italy, the buyer must withhold tax from payments for vendor invoices, and then remit the tax to the tax authority. In Australia, withholding tax must be withheld if a vendor does not provide an Australian Business Number. For more information about vendor payments, see [Key tasks: Vendor payments and settlements](key-tasks-vendor-payments-and-settlements.md) and [Select invoices to pay on behalf of multiple legal entities](select-invoices-to-pay-on-behalf-of-multiple-legal-entities.md).


> [!NOTE]
> <P>An intercompany settlement occurs when you post a payment or payment reversal for an invoice in another legal entity. In an intercompany settlement, the withholding tax transaction information is based on the tax information for the vendor of the invoice, and is posted in the legal entity of the invoice.</P>



1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a journal, and then click **Lines** to open the **Journal voucher** form for payment journal lines.

3.  In the **Account** field, enter a vendor account that is set up for withholding tax. For more information, see [(Global, AUS, ITA) Set up withholding tax for a vendor](global-aus-ita-set-up-withholding-tax-for-a-vendor.md).

4.  Enter a description of the transaction. When the transaction is posted, the same description is used for the withholding tax transactions. You can run a query on the description to find the withholding tax transactions that are associated with a particular invoice.

5.  Click **Functions** \> **Settlement**.

6.  In the **Settle open transactions** form, select the **Mark** check box on the line for each vendor invoice to pay.

7.  To view or change withholding tax information for each invoice, click the **Withholding tax** tab. For example, you can change the information in the **Amount exempted from withhold in invoice currency** field.

## See also

[Find withholding tax transactions for a vendor by using transaction descriptions](find-withholding-tax-transactions-for-a-vendor-by-using-transaction-descriptions.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  


