---
title: (RUS) Set up the tax agent transactions
TOCTitle: (RUS) Set up the tax agent transactions
ms:assetid: 9eb51a58-bfd5-4f16-8972-e9fe3d3b4c46
ms:mtpsurl: https://technet.microsoft.com/library/JJ678541(v=AX.60)
ms:contentKeyID: 49387770
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up the tax agent transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up the parameters for tax agent transactions in the general ledger module before you can create the tax agent transactions.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



## Set up the VAT operation code for the tax declaration

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **VAT operation codes**.

2.  In the **VAT operation code** field, enter the operation code for the VAT declaration.

3.  In the **Description** field, enter a description of the transaction code.

4.  Press CTRL+S or close the form.

## Set up the sales tax code for tax agent transactions

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Press CTRL+N to create a new tax code.

3.  In the **Sales tax code** field, enter a code for sales tax.

4.  In the **Settlement period** field, select the time period for which the tax is calculated and paid to the tax authority.

5.  In the **Ledger posting group** field, select the ledger posting group for the sales tax code.

6.  In the **Type of tax** field, select **Standard VAT**.

7.  In the **VAT charge** field, select the source of VAT accrual from the following options:
    
      - **From vendor funds** − VAT payment is made from the vendor's income.
    
      - **From own funds** − VAT payment is made from the tax agent's funds.

8.  Click **Values** to open the **Values** form.

9.  In the **Value** field, enter the VAT percentage.

10. Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa553257(v=ax.60)">Sales tax codes (form)</A>.</P>



11. Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax groups**.

12. Press CTRL+N to create a sales tax group, and enter the necessary information.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa498345(v=ax.60)">Sales tax groups (form)</A>.</P>



13. On the **Setup** tab, in the **Sales tax code** field, select the sales tax code created in steps 1 through 10.
    

    > [!NOTE]
    > <P>If you select the sales tax code for the <STRONG>From own funds</STRONG> option, the <STRONG>Exempt</STRONG> check box is selected by default on the <STRONG>Setup</STRONG> tab.</P>



14. Press CTRL+S or close the form.

15. Click **General ledger** \> **Setup** \> **Sales tax** \> **Item sales tax groups**.

16. Press CTRL+N to create an item sales tax group, and enter the necessary information.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa615960(v=ax.60)">Item sales tax groups (form)</A>.</P>



17. On the **Setup** tab, in the **Sales tax code** field, select the sales tax code created in steps 1 through 10.

18. Press CTRL+S or close the form.

## Set up a vendor tax authority

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax authorities**.

2.  Press CTRL+N to create a tax authority, and enter the required details.

3.  In the **Vendor account** field, select the vendor who operates as the tax authority.

4.  Press CTRL+S or close the form.
    

    > [!NOTE]
    > <P>For more information, see <A href="set-up-a-sales-tax-authority-as-a-vendor.md">Set up a sales tax authority as a vendor</A>.</P>



## See also

[(RUS) Sales tax codes (modified form)](https://technet.microsoft.com/library/jj923552\(v=ax.60\))

[(RUS) VAT operation codes (form)](https://technet.microsoft.com/library/jj839695\(v=ax.60\))

[(RUS) Create a payment proposal for a tax agent invoice](rus-create-a-payment-proposal-for-a-tax-agent-invoice.md)

[(RUS) Create and print factures for VAT deductions](rus-create-and-print-factures-for-vat-deductions.md)

[(RUS) Create vendor tax agent transactions](rus-create-vendor-tax-agent-transactions.md)

  


