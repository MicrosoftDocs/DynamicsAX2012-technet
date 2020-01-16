---
title: (RUS) Set up sales tax codes for customer advance payment
TOCTitle: (RUS) Set up sales tax codes for customer advance payment
ms:assetid: 4cc66b56-774e-45e3-80fc-658fd28925ab
ms:mtpsurl: https://technet.microsoft.com/library/JJ665362(v=AX.60)
ms:contentKeyID: 49387450
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up sales tax codes for customer advance payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Each sales tax code is characterized by the following criteria:

  - Tax type

  - Basis for adding tax

  - Tax rate or amount

  - Period of validity

  - Account posting rules

You can set the posting rules by specifying a ledger posting group for the sales tax code. Within the Posting groups directory, the ledger accounts are set up to create tax accounting transactions for a specified tax code.

The sales tax codes are grouped into sales tax groups (TG) and item sales tax groups (ITG). When you execute a purchase or sales voucher, you must specify the appropriate TG or ITG. The taxes (sales tax codes) that are included in both TG and ITG are calculated. When you post the voucher, the relevant accounting transactions are created.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  On the **Overview** tab, press CTRL+N to create a new line, and enter the required details.
    

    > [!NOTE]
    > <P>For more information, <A href="https://technet.microsoft.com/library/aa553257(v=ax.60)">Sales tax codes (form)</A> and <A href="create-various-kinds-of-sales-tax-codes.md">Create various kinds of sales tax codes</A>.</P>



3.  In the **Type of tax** field, select the tax type for the tax calculation from the following options:
    
      - **Other**
    
      - **Standard VAT**
    
      - **Excise**
    
      - **Reduced VAT**
    
      - **VAT 0%**
    
      - **Assessed tax**
    
      - **Transport tax**
    
      - **Land tax**
        

        > [!NOTE]
        > <P>When you process VAT receivables, or create sales or purchase books and their supplemental pages, the invoice lines are selected in accordance with the tax type.</P>



4.  In the **Currency** field, select the currency in which the sales tax is to be calculated.

5.  Click the **Calculation** tab.

6.  In the **Marginal base** field, select the type of amount for the sales tax code calculation from the following options:
    
      - **Net amount per line** – Tax is calculated from the value of every line.
    
      - **Net amount per unit** – Tax is calculated from the value of the units of goods without taking into account other taxes.
    
      - **Net amount of invoice balance** – Tax is calculated from the gross invoice amount.
    
      - **Gross amount per lin**e – Tax is calculated from the gross value per line.
    
      - **Gross amount per unit** – Tax is calculated from the gross value per unit.
    
      - **Invoice total incl. other sales tax amounts** – Tax is calculated from the account total, including other taxes.

7.  In the **Calculation method** field, select the method of calculation for the selected sales tax code from the following options:
    
      - **Whole amount** – One sales tax rate or amount applies to the calculation base (taxable amount).
    
      - **Interval** – Various sales tax rates or amounts apply to different parts of the calculation base (taxable amount).

8.  In the **Round-off** field, enter the number of decimal places for the sales tax calculation for the selected sales tax code.

9.  In the **Rounding form** field, specify how the calculated taxes are rounded off. The options include **Normal**, **Downward**, and **Rounding-up**.

10. Click **Values** to specify a sales tax code value or a percentage for the sales tax calculation.
    

    > [!NOTE]
    > <P>You can specify different sales tax values for different amount intervals and periods. If the period is not specified, the tax rate is valid without any time restriction.</P>



11. Press CTRL+S or close the form.

## See also

[(RUS) Set up sales tax groups for customer advance payment](rus-set-up-sales-tax-groups-for-customer-advance-payment.md)

  


