---
title: (EEUR) Set up exchange rates for calculating VAT
TOCTitle: (EEUR) Set up exchange rates for calculating VAT
ms:assetid: 2aaa883b-5787-4c79-b3c1-d0cfb20fe02e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ852135(v=AX.60)
ms:contentKeyID: 50281221
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Czech Republic, Estonia, Hungary, Latvia, Lithuania, Poland, Russia
---

# (EEUR) Set up exchange rates for calculating VAT 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Your organization can select the exchange rate to use to calculate value-added tax (VAT) for VAT statements. The exchange rate that is used to calculate VAT can be different from the exchange rate that your organization uses for company accounting functions. Accounting functions include preparing tax-related documents such as the following:

  - Invoices

  - Free text invoices

  - Purchase orders

  - Project invoices

  - Credit notes

  - Corrective invoices


> [!NOTE]
> <P>Differences in sales tax amounts that are caused by the difference between the VAT currency exchange rate and the accounting currency exchange rate for your organization are posted to specified accounts. You can specify these accounts in the <STRONG>Ledger posting groups</STRONG> form.</P>



1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency exchange rate types for sales tax**.

2.  In the **Ledger** filter, select the legal entity ledger for which you are setting up exchange rates.

3.  In the left pane, select the currency for which to set up an exchange rate.

4.  Click **Add**, and then, in the **Transaction type** field, select whether this exchange rate record is for a sale or a purchase.

5.  In the **Exchange rate type** field, select **VAT**.
    

    > [!NOTE]
    > <P>If <STRONG>VAT</STRONG> is not available in the <STRONG>Exchange rate type</STRONG> list, you can add it to the list by using the <STRONG>Exchange rate types</STRONG> form.</P>



6.  Click **Add** again to create another exchange rate record for the selected currency, or select another currency in the list, and then repeat steps 4 and 5.

## See also

[Ledger posting groups (form)](https://technet.microsoft.com/en-us/library/aa598801\(v=ax.60\))

[Currency exchange rates (form)](https://technet.microsoft.com/en-us/library/hh209477\(v=ax.60\))

  


