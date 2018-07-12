---
title: (HUN) Set up exchange rates for calculating VAT
TOCTitle: (HUN) Set up exchange rates for calculating VAT
ms:assetid: 96fa9d0c-2b3f-4a31-88d8-3e3de5bf765b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664336(v=AX.60)
ms:contentKeyID: 49385424
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Hungary
---

# (HUN) Set up exchange rates for calculating VAT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Your organization can select the exchange rate to use to calculate value-added tax (VAT) for the VAT statement. The exchange rate that is used to calculate VAT can be different from the exchange rate that your organization uses for company accounting functions, including preparing tax-related documents such as the following:

  - Invoices

  - Free text invoices

  - Purchase orders

  - Project invoices

  - Credit notes

  - Corrective invoices


> [!NOTE]
> <P>Differences in the exchange rate amounts are posted to specified accounts. You can specify these accounts in the <STRONG>Ledger posting groups</STRONG> form.</P>



1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency exchange rate types for sales tax**. In the **Ledger** filter, select the legal entity ledger for which you are setting up exchange rates.

2.  In the left pane, select the currency for which to set up an exchange rate.

3.  Click **Add**, and then, in the **Transaction type** field, select whether this exchange rate record is for a sale or a purchase.

4.  In the **Exchange rate type** field, select **VAT**.
    

    > [!NOTE]
    > <P>If <STRONG>VAT</STRONG> is not available in the <STRONG>Exchange rate type</STRONG> list, you can add it to the list by using the <STRONG>Exchange rate types</STRONG> form.</P>



5.  Click **Add** again to create another exchange rate record for the selected currency, or select another currency in the list, and then repeat steps 3 and 4.

  


