---
title: (ITA) Set up information for the "Italian black list" report
TOCTitle: (ITA) Set up information for the "Italian black list" report
ms:assetid: 889bc090-e652-4bf7-8108-d8d604953641
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209341(v=AX.60)
ms:contentKeyID: 36058452
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# (ITA) Set up information for the \"Italian black list\" report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Legal entities must report all taxable sales and purchase transactions with other companies in countries that offer privileged tax structures. These countries are referred to as “black listed” countries by the Italian government. These countries present a high risk from a tax standpoint. Legal entities in Italy must report these transactions on a monthly or quarterly basis to the government.

You must complete the following setup procedures before you generate the “Italian black list” report and export it as an ASCII file:

  - Set up a country or region as "black listed"

  - Set up the legal nature of a legal entity

  - Set up the country/region of residence for a foreign customer

  - Set up the country/region of residence for a foreign vendor

  - Set up the VAT type for a sales tax code

## Set up a country or region as "black listed"

Use the **Foreign trade parameters** form to identify a country as “black listed” and the **Address setup** form to specify the county code for a “black listed” country.

1.  Click **Organization administration** \> **Setup** \> **Foreign trade** \> **Foreign trade parameters**.

2.  Click the **Country/region properties** link.

3.  Select or create a country/region.

4.  In the **IT three-digit code** field, set the numeric country code as mentioned in the report instructions from the Italian government. For example, the IT three-digit code for Switzerland is 071.

5.  Select the **Black listed country/region** check box.

6.  Close the form.

7.  Click **Organization administration** \> **Setup** \> **Addresses** \> **Address setup**.

8.  Click the **County** link, and then in the **Italian county code** field, enter the two-letter county code.

9.  Close the form.

## Set up the legal nature of a legal entity

Use the **Legal entities** form to specify the legal nature of a legal entity. The legal nature is the legal structure that is registered with the government, such as **Limited share partnerships**, **Limited liability companies (SRL)**, or **Public limited companies (SPA)**.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Select or create a legal entity.

3.  Click the **Statutory reporting** FastTab.

4.  In the **Fiscal code** field, enter the fiscal code of the legal entity.

5.  In the **Legal nature** field, select the legal structure of the legal entity.

6.  Close the form.

## Set up the country/region of residence for a foreign customer

Use the **Customers** form to set up the country/region of residence for a customer in a foreign country/region. Only the invoice transactions with legal entities in countries that have privileged tax structures (“black listed” countries) are included in the “Italian black list” report.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Double-click a customer account.

3.  In the **Customers** form, in the **Account** field, specify the customer account number.
    

    > [!NOTE]
    > <P>If the customer is also a vendor and the vendor account number is specified in the <STRONG>Customers</STRONG> form, the sales and purchase transactions are summarized as one record in the “Italian black list” report.</P>



4.  Click the **Sales demographics** FastTab.

5.  In the **Primary contact** field, select the primary contact for the customer.

6.  In the **Birth date** field, select the date of birth of the primary contact.

7.  In the **Birth place** field, enter the place of birth of the primary contact.

8.  In the **Birth county** field, select the county of birth of the primary contact.

9.  In the **Residence foreign country/region** field, select the country/region where the customer is based for tax purposes.

10. Close the form.

## Set up the country/region of residence for a foreign vendor

Use the **Vendors** form to set up the country/region of residence for a vendor in a foreign country/region.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Double-click a vendor account.

3.  In the **Vendors** form, in the **Vendor account** field, specify the vendor account number.
    

    > [!NOTE]
    > <P>If the vendor is also a customer and the customer account number is specified in the <STRONG>Vendors</STRONG> form, the sales and purchase transactions are summarized as one record in the “Italian black list” report.</P>



4.  Click the **Purchasing demographics** FastTab.

5.  In the **Primary contact** field, select the primary contact for the vendor.

6.  In the **Birth date** field, select the date of birth of the primary contact.

7.  In the **Birth place** field, enter the place of birth of the primary contact.

8.  In the **Birth county** field, select the county of birth of the primary contact.

9.  In the **Residence foreign country/region** field, select the country/region where the vendor is based for tax purposes.

10. Close the form.

## Set up the VAT type for a sales tax code

Use the **Sales tax codes** form to set up the type of tax to be calculated for the “Italian black list” report, such as **Standard**, **Zero**, **Exempt**, or **Not subject to VAT**. The VAT type that is specified determines the category where the net and VAT amounts for the invoices are printed on the report and where they are located in the file.


> [!NOTE]
> <P>If the total net or VAT amount that is invoiced in a period is negative for a specific VAT type, it appears as credit for the previous period (or previous year, if the period starts in January).</P>



1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Sales tax codes**.

2.  Select or create a sales tax code.

3.  Click the **Calculation** FastTab.

4.  In the **VAT type** field, select the VAT type that is used to categorize the transactions in the “Italian black list” report:
    
      - **Standard** – The transaction includes a standard VAT amount.
    
      - **Zero** – The transaction does not include a VAT amount.
    
      - **Exempt** – The transaction is exempted from VAT.
    
      - **Not subject to VAT** – The transaction is not subject to VAT.
    

    > [!NOTE]
    > <P>Similarly, you can set up the VAT type for other sales tax codes by selecting the sales tax code on the <STRONG>General</STRONG> FastTab.</P>



5.  Close the form.

## See also

[(ITA) Generate the "Italian black list" report for taxable transactions](ita-generate-the-italian-black-list-report-for-taxable-transactions.md)

[Foreign trade parameters (form)](https://technet.microsoft.com/en-us/library/aa620385\(v=ax.60\))

[Customers (form)](https://technet.microsoft.com/en-us/library/aa590606\(v=ax.60\))

[Sales tax codes (form)](https://technet.microsoft.com/en-us/library/aa553257\(v=ax.60\))

[Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\))

[Legal entities (form)](https://technet.microsoft.com/en-us/library/hh242860\(v=ax.60\))

[Address setup (form)](https://technet.microsoft.com/en-us/library/hh209301\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

