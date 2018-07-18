---
title: (RUS) Set up sales tax groups for customer advance payment
TOCTitle: (RUS) Set up sales tax groups for customer advance payment
ms:assetid: c3260d29-419a-46e5-a657-69d0d893a145
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711578(v=AX.60)
ms:contentKeyID: 49387902
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up sales tax groups for customer advance payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Sales tax groups** form to set up sales tax groups (TG) for customers and vendors when you register advances. The taxes included in the sales tax group pertain to the customer or vendor, rather than to an item.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

2.  Press CTRL+N to create a new line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/en-us/library/aa498345(v=ax.60)">Sales tax groups (form)</A>.</P>



3.  In the **Sales tax group** field, enter a sales tax group code.

4.  In the **Description** field, enter a name that describes the sales tax group.

5.  In the **Sales tax group setup** field, select **Sales tax codes**.
    

    > [!NOTE]
    > <P><STRONG>Sales tax jurisdiction</STRONG> is selected only if the company conducts business in the United States of America.</P>



6.  In the **Rounding by** field, select the adjustment criteria for the sales tax code from the following options:
    
      - **Sales tax codes** – The tax amount is determined for every line. It is then added up for every tax code.
    
      - **Sales tax code combinations** – Tax amounts are arranged in groups for all lines with the same tax codes, and then the tax amounts are adjusted.

7.  Click the **Setup** tab, and then press CTRL+N to create a new line and specify all the tax codes to be included in the new sales tax group.
    

    > [!NOTE]
    > <P>The same tax code can be included in several sales tax groups.</P>



8.  Press CTRL+S or close the form.

## See also

[(RUS) Set up sales tax codes for customer advance payment](rus-set-up-sales-tax-codes-for-customer-advance-payment.md)

[(RUS) Set up item sales tax groups for customer advance payment](rus-set-up-item-sales-tax-groups-for-customer-advance-payment.md)

  


