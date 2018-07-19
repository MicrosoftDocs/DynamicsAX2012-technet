---
title: (Global, AUS, ITA) Set up withholding tax for a vendor
TOCTitle: (Global, AUS, ITA) Set up withholding tax for a vendor
ms:assetid: 3094a0d7-7176-4ae4-9b65-19eda5ff97bc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548468(v=AX.60)
ms:contentKeyID: 36056315
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# (Global, AUS, ITA) Set up withholding tax for a vendor 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Some countries/regions, such as Italy, require that buyers withhold tax from payments for vendor invoices. The buyers must then remit the tax to the tax authority. In Australia, withholding tax must be withheld if a vendor does not provide an Australian Business Number (ABN). Because withholding tax applies only to vendor invoices, the setup is completed in Accounts payable. For more information, see [Calculate and post withholding tax](calculate-and-post-withholding-tax.md).

By setting up withholding tax, you can more efficiently perform the following tasks:

  - Activate the calculation of withholding tax when you pay a vendor invoice.

  - Keep basic data about the vendor. You can then use this data for reports.

By default, when a payment for a vendor who has been set up for withholding tax is entered in a journal, the journal proposes this setup. You can modify the calculated amounts, select a different withholding tax, or deactivate the calculation of withholding tax for a specific payment. When the payment is posted, the payment description is copied to the **Description** field for the withholding tax transaction. You can use the description to identify the withholding tax transactions that are associated with a specific invoice.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **Vendors on hold**. On the **Action Pane**, in the **New** group, click **Vendor**.

2.  (ITA) If you are setting up withholding tax for the Italian certification report, enter a value in the **Fiscal code** field on the **Invoice and delivery** FastTab.

3.  On the **Invoice and delivery** FastTab, select the **Calculate withholding tax** check box. Select a withholding tax group to activate the calculation when a payment is entered in a journal.

4.  (ITA) If you are setting up withholding tax for Italian reports, on the **Contact information** FastTab, enter values in the **Birth date**, **Birth place**, and **Residence foreign country/region** fields.

## See also

[Set up withholding tax in System administration and General ledger](set-up-withholding-tax-in-system-administration-and-general-ledger.md)

[Calculate and post withholding tax](calculate-and-post-withholding-tax.md)

[Enter a vendor payment that is subject to withholding tax](enter-a-vendor-payment-that-is-subject-to-withholding-tax.md)

[Find withholding tax transactions for a vendor by using transaction descriptions](find-withholding-tax-transactions-for-a-vendor-by-using-transaction-descriptions.md)

  


