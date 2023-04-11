---
title: (RUS) Import exchange rates from the CBRF website
TOCTitle: (RUS) Import exchange rates from the CBRF website
ms:assetid: 7f6e9730-18a6-4fa0-b204-e795839a5a6b
ms:mtpsurl: https://technet.microsoft.com/library/JJ678408(v=AX.60)
ms:contentKeyID: 49387639
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Import exchange rates from the CBRF website 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can import exchange rates from the Central Bank of the Russian Federation (CBRF) website, and set them up in the **Currency exchange rates** form. For more information about how to configure exchange rate providers and exchange rate types, see [(RUS) Set up import of exchange rates](rus-set-up-import-of-exchange-rates.md) and [Exchange rate types (form)](https://technet.microsoft.com/library/hh242857\(v=ax.60\)).

1.  Click **General ledger** \> **Periodic** \> **Import currency exchange rates**.

2.  On the **General** tab, in the **Exchange rate type** field, select the exchange rate type that you want to import the exchange rates for.

3.  In the **Exchange rate provider** field, select the exchange rate provider. To import the exchange rates from the CBRF website, select **Central Bank of the Russian Federation**.

4.  In the **Import as of** field, select the date or date range to import the exchange rates for. The following options are available:
    
      - **Today's date** – Import the exchange rates for the current date.
    
      - **Date range** – Select the start date and end date of a date range. This option lets you import historical exchange rates.

5.  Select the **Create necessary currency pairs** check box to create exchange rates between two currencies or currency pairs for the International Organization for Standardization (ISO) currency codes.

6.  Select the **Override existing exchange rates** check box to override exchange rates that are already available for the current date or the specified date range.

7.  Click **OK** to import the exchange rates from the CBRF website.
    

    > [!NOTE]
    > <P>If a currency is not set, the exchange rates are not imported.</P>



## See also

[Currency exchange rates (form)](https://technet.microsoft.com/library/hh209477\(v=ax.60\))

  


