---
title: (BEL) Generate journal, sales tax, and purchase sales tax transaction reports
TOCTitle: (BEL) Generate journal, sales tax, and purchase sales tax transaction reports
ms:assetid: a15dca78-9159-4ec7-baba-84049d9bfc9d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209454(v=AX.60)
ms:contentKeyID: 36058783
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Belgium
- sales tax
- purchase tax tranasctions
---

# (BEL) Generate journal, sales tax, and purchase sales tax transaction reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must complete the following tasks before you generate journal, sales tax, and purchase sales tax transaction reports:

  - Set up posting journals for sales, purchases, and journals. For more information, see [(BEL) Posting journals (form)](https://technet.microsoft.com/en-us/library/aa592268\(v=ax.60\)).

  - Set up sales tax codes. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

  - Set up item sales tax groups (reporting type= service). For more information, see [Set up default item sales tax groups for an item](set-up-default-item-sales-tax-groups-for-an-item.md).

  - Set up sales tax jurisdictions. For more information, see [Set up sales tax jurisdictions](set-up-sales-tax-jurisdictions.md).

  - Set up sales tax authorities. For more information, see [Set up sales tax authorities](set-up-sales-tax-authorities.md).

  - Set up sales tax settlement periods. For more information, see [Set up a sales tax settlement period](set-up-a-sales-tax-settlement-period.md).

  - Set up sales tax reporting codes. For more information, see [Sales tax reporting codes (form)](https://technet.microsoft.com/en-us/library/aa588316\(v=ax.60\)).

## Generate General ledger journal reports

Belgian companies can generate the following reports that list all the postings to the General ledger account for each journal:

  - **Financial journals** – This report lists the financial journal information for Belgium.

  - **Other journals** – This report lists the other journal information for Belgium.

  - **Overview journals** – This report lists the summary posting journal information for Belgium.

  - **Sales journals** – This report lists the sales journal information for Belgium.

  - **Purchase journals** – This report lists the purchase journal information for Belgium.

<!-- end list -->

1.  Click **General ledger** \> **Reports** \> **Journals** \> **Financial journals**.
    
    –or–
    
    Click **General ledger** \> **Reports** \> **Journals** \> **Other journals**.
    
    –or–
    
    Click **General ledger** \> **Reports** \> **Journals** \> **Overview journals**.
    
    –or–
    
    Click **General ledger** \> **Reports** \> **Journals** \> **Sales journals**.
    
    –or–
    
    Click **General ledger** \> **Reports** \> **Journals** \> **Purchase journals**.

2.  In the **Journal** field, select the name of the journal.

3.  In the **From date** and **To date** fields, select the starting date and ending date for the reporting period.

4.  Click **OK** to generate the report.

## Generate sales tax and purchase sales tax transaction reports

In accordance with VAT 2010 regulation, the sales tax and purchase sales tax transaction reports must include information about service-related transactions in tax boxes 44 and 88. Services that are provided to customers are reported in box 44 of the VAT statement, and services that are received from vendors are reported in box 88 of the VAT statement.

1.  Click **General ledger** \> **Reports** \> **Reconciliation** \> **Customer** \> **Sales tax transactions re sales**.

2.  In the **Settlement period** field, select the sales tax settlement period.

3.  In the **From date** field, select the starting date for the report.

4.  Click **OK** to generate the sales tax transactions report.

5.  Click **General ledger** \> **Reports** \> **Reconciliation** \> **Vendor** \> **Purchase sales tax transactions**.

6.  In the **Settlement period** field, select the sales tax settlement period.

7.  In the **From date** field, select the starting date for the report.

8.  Click **OK** to generate the purchase sales tax transactions report.

## See also

[(BEL) Posting journals (form)](https://technet.microsoft.com/en-us/library/aa592268\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

