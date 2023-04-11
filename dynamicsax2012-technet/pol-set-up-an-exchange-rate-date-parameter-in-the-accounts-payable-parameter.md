---
title: (POL) Set up an exchange rate date parameter in the Accounts payable parameter
TOCTitle: (POL) Set up an exchange rate date parameter in the Accounts payable parameter
ms:assetid: 644e0303-4733-44d5-929e-e240fe2d6360
ms:mtpsurl: https://technet.microsoft.com/library/JJ678224(v=AX.60)
ms:contentKeyID: 49386946
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up an exchange rate date parameter in the Accounts payable parameter 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In accordance with Polish tax law, you must calculate an exchange rate based on the document date, posting date, or date of VAT register to post invoices that are issued in a foreign currency.

You can use the **Accounts payable parameters** form to define the date parameters for vendors with currency exchange rate transactions.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  On the **General** tab, in the **Exchange rate date** field, select the exchange rate date to calculate the exchange rate from the following options:
    
      - **Posting date** - Calculate the exchange rate based on the posting date.
    
      - **Date of VAT register** - Calculate the exchange rate based on the date of VAT register.
    
      - **Document date** - Calculate the exchange rate based on the document date.
    
      - **Document date (for EU trade only)** - Calculate the exchange rate based on the document date when trading with European Union countries.
        

        > [!NOTE]
        > <P>If you select <STRONG>Document date (for EU trade only)</STRONG>, the document date will be used to calculate the exchange rate only if the sales tax group for EU trade is selected in the <STRONG>Sales order</STRONG> form, <STRONG>Free text invoice</STRONG> form, <STRONG>Purchase order</STRONG> form, <STRONG>Invoice pool excl. posting</STRONG> form, <STRONG>Invoice register journal lines</STRONG> form, and <STRONG>Invoice journal lines</STRONG> form.</P>



3.  Press CTRL+S or close the form.

## See also

[(POL) Set up a sales tax group for EU trade](pol-set-up-a-sales-tax-group-for-eu-trade.md)

[(POL) Set up an exchange rate date parameter in the Accounts receivable parameter](pol-set-up-an-exchange-rate-date-parameter-in-the-accounts-receivable-parameter.md)

  


