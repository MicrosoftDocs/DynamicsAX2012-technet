---
title: (POL) Set up VAT exchange rates for foreign currency sales invoices
TOCTitle: (POL) Set up VAT exchange rates for foreign currency sales invoices
ms:assetid: a80c82d9-e2a3-4694-8537-4a7ec8cb699b
ms:mtpsurl: https://technet.microsoft.com/library/Dn511005(v=AX.60)
ms:contentKeyID: 59953760
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- sales invoice
- sales invoices
- exchange rates
- exchange rate
- Poland
- PL - 00014
- foreign currencies
- foreign currency
- foreign trade
- Forms.ExchangeRateCurrencyPairCalculationRules
- VAT exchange rate
- VAT exchange rates
- MsDynAx060.Forms.ExchangeRateCurrencyPairCalculationRules
audience: Application User
ms.search.region: Poland
---

# (POL) Set up VAT exchange rates for foreign currency sales invoices 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Exchange rate calculation rules for currency pairs** form to set up an exchange rate calculation rule for a currency pair. The exchange rate calculation rules are used to convert value-added tax (VAT) amounts for foreign currency sales invoices to VAT amounts in a destination currency, such as Polish zloty.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



When you post a sales invoice that contains VAT amounts in a foreign currency, Microsoft Dynamics AX 2012 R2 identifies the currency of the invoice, and then converts the VAT amounts as follows:

  - If the VAT amount is in euros, AX 2012 R2 converts the VAT amount directly to the destination currency.

  - If the VAT amount is in a foreign currency other than euros, AX 2012 R2 converts the VAT amount to a triangulation currency such as euros, and then converts the VAT amount from that triangulation currency to the destination currency.

To set up a VAT exchange rate rule, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Exchange rate calculation rules for sales tax**.

2.  Click **New** or press CTRL+N to create a record.

3.  In the **Valid for** field, select **All** to apply the rule to all of the exchange rate types or select **Table** to apply the rule to an exchange rate type.

4.  If you select **Table** in the **Valid for** field, then in the **Exchange rate type** field, select an exchange rate type to apply the rule to.

5.  In the **Valid for** field, select **All** to apply the rule to all of the legal entities or select **Table** to apply the rule to a legal entity.

6.  If you select **Table** in the **Valid for** field, then in the **Company** field, select a legal entity to apply the rule to.

7.  In the **From currency** field, select the currency to convert the amounts from.

8.  In the **To currency** field, select the destination currency to convert the amounts to.

9.  In the **Triangulation currency** field, select the triangulation currency to convert the amounts to before converting the amounts to the destination currency that you specify in the **To currency** field. The standard selection for the triangulation currency is euro.

You can include additional lines that contain mismatched amounts on the sales VAT register report by selecting the **Show details** check box in the **Sales VAT register** report. For more information, see [(POL) Sales VAT register (report)](pol-sales-vat-register-report.md).

## See also

[(POL) Post VAT transactions](pol-post-vat-transactions.md)

[(POL) Post taxes on a VAT account](pol-post-taxes-on-a-vat-account.md)

  


