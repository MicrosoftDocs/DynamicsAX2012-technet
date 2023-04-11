---
title: (RUS) Set up import of exchange rates
TOCTitle: (RUS) Set up import of exchange rates
ms:assetid: d0c546d6-db2e-4e84-9816-b5dc7936f93e
ms:mtpsurl: https://technet.microsoft.com/library/JJ711642(v=AX.60)
ms:contentKeyID: 49387966
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up import of exchange rates 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To import currency exchange rates from the Central Bank of the Russian Federation (CBRF) website, you must set up an exchange rate provider to forward the exchange rates from the website. You must also configure currency factors that are used as coefficients to multiply the imported exchange rates. Use the following procedures to configure CBRF as the exchange rate provider, and to set the factor for exchange rates for a currency code.

## Configure an exchange rate provider

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Configure exchange rate providers**. For more information, see [Configure exchange rate providers (form)](https://technet.microsoft.com/library/jj852132\(v=ax.60\))

2.  Click **Add** to open the **Select exchange rate providers** form.

3.  In the **Select exchange rate providers** form, in the **Name** field, select **Central Bank of the Russian Federation** as the exchange rate provider, and then click **OK**. The exchange rate provider is added with the default configuration settings to the **Configure exchange rate providers** form.

4.  In the **Name** field, modify the exchange provider name, if required.

5.  In the **Value** field, modify the key information that is required by the provider.

6.  Click **Reset values** to return to the default configuration settings, if required.

## Set up the currency exchange rate factor

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currencies**. For more information, see [Currencies (form)](https://technet.microsoft.com/library/aa582902\(v=ax.60\)).

2.  In the **Currency** field, select the International Organization for Standardization (ISO) currency code for which you want to set the exchange rate factor, and then click **Factor** to open the **Exchange rate factor** form.
    

    > [!NOTE]
    > <P>In the <STRONG>Default factor</STRONG> field, the default factor is displayed for the currency exchange rate. This factor is used for all exchange rate types for the currency.</P>



3.  In the **Factor** field, modify the factor for a specific exchange rate type, if required.

## See also

[(RUS) Import exchange rates from the CBRF website](rus-import-exchange-rates-from-the-cbrf-website.md)

[Exchange rate types (form)](https://technet.microsoft.com/library/hh242857\(v=ax.60\))

  


