---
title: Set up currency exchange rates (Retail essentials)
TOCTitle: Set up currency exchange rates (Retail essentials)
ms:assetid: 409a0564-592a-4e67-87c8-2d6c520a2484
ms:mtpsurl: https://technet.microsoft.com/library/Dn716078(v=AX.60)
ms:contentKeyID: 62200341
author: Khairunj
ms.date: 08/15/2014
mtps_version: v=AX.60
---

# Set up currency exchange rates (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up and define currency exchange rates between any two currencies, or a currency pair. The exchange rate that is calculated is based on the accounting currency, reporting currency, and exchange rate type for the legal entity. Currencies are shared and can be used by any legal entity.


> [!NOTE]
> <P>In Retail essentials, the form that you use to complete this task includes a subset of the controls that are available for other configurations of Retail. If a topic about this form describes controls that you don't see, it may be because you’re using Retail essentials.</P>



To set up exchange rates between currencies, follow these steps:

1.  Click **Retail essentials** \> **Financials** \> **Setup** \> **Currency exchange rates**.

2.  In the **Currency exchange rates** form, in the **Exchange rate type** field, select the type of exchange rate to use. For example, you can set up an exchange rate for budgeting, and a different exchange rate for the end of a fiscal period.

3.  Click **New** to create a new currency exchange rate.

4.  In the **From currency** field, select a currency to convert. This currency is also named the *base* currency.

5.  In the **To currency** field, select the currency to convert to. This currency is also named the *quotation* currency.

6.  In the **Quotation unit** field, select the number of the base currency that the exchange rate is based on. For example, if 100 units of the base currency are converted to 100 units of the quotation currency, the quotation unit is 100. Or, if one unit of the base currency is converted to 100 units of the quotation currency, the quotation unit is 1.

7.  In the **From date**, select the starting date for the exchange rate for the specified currencies.

8.  In the **To date**, select the ending date for the exchange rate for the specified currencies.

9.  To create specific date ranges in which an exchange rate for the selected currencies is valid, click **Add**, and then enter the starting date and exchange rate to use. When you add another exchange rate and enter a starting date that is later than another exchange rate’s starting date, the earlier exchange rate is no longer valid.

## See also

[Financials (Retail essentials)](financials-retail-essentials.md)

  


