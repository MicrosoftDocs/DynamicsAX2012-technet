---
title: (MEX) Generate an ISR provisional payment report
TOCTitle: (MEX) Generate an ISR provisional payment report
ms:assetid: e208da75-64af-47cd-8082-414b69dfc62c
ms:mtpsurl: https://technet.microsoft.com/library/Hh227426(v=AX.60)
ms:contentKeyID: 36059716
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- ISR
- Mexico
- report
- provisional payment
audience: Application User
ms.search.region: Mexico
---

# (MEX) Generate an ISR provisional payment report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Mexican government requires that individuals, corporations, and foreign companies operating in Mexico submit an Impuesto sobre la renta (ISR), or federal corporate income tax report. The report displays detailed calculations of provisional income tax payments, and is based on the following factors:

  - ISR concept categories linked to one or more ledger accounts

  - ISR annual rate table

  - ISR utility ratio

## Set up a concept category and assign a ledger account

Use the **ISR report setup** form to set up ISR report concept categories and link them to a ledger account.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **ISR report setup**.

2.  Press CTRL+N to create a new ISR report concept category.

3.  In the **Concept category** field, select one of the following ISR concept categories to assign to one or more ledger accounts:
    
      - **Revenue** – The income tax is calculated based on the revenue collected during the period.
    
      - **Inventory** – The income tax is calculated based on the status of inventory during the review period.
    
      - **PTU Paid in fiscal year** – The income tax is calculated based on the Participación a los Trabajadores de las Utilidades (PTU) tax paid during the fiscal year.
    
      - **Investment deductions** – The income tax is calculated based on investment deductions for the reporting period.
    
      - **Pending depreciation tax losses** – The income tax is calculated based on pending depreciation tax losses for the reporting period.
    
      - **ISR withheld from bank** – The income tax is calculated based on the ISR withheld from the bank.
    
      - **Tax for cash deposit operations** – The income tax is calculated based on the tax for cash deposit operations.
    
      - **ISR paid for dividends of previous fiscal year** – The income tax is calculated based on the ISR paid on dividends from previous fiscal years.
    
      - **ISR payments** – The income tax is calculated based on ISR payments made for the fiscal year.
    
      - **Balance to compensate for cash** – The income tax is calculated based on the account balance to compensate for cash during the reporting period.
    
      - **Employee allowance paid** – The income tax is calculated based on employee allowances paid during the fiscal year.

4.  In the **Concept category description** field, enter a description of the ISR report concept category.

5.  Click the right pane, and then press CTRL+N to create a new line to link the ISR report concept category to a main account.

6.  In the **Main account** field, select the main account to be linked with the ISR report concept category. The main account name is updated in the **Account name** field.

7.  In the **D/C indicator** field, select the account type indicator:
    
      - **Both** – The main account is both a debit and credit account.
    
      - **Debit** – The main account is a debit account.
    
      - **Credit** – The main account is a credit account.

8.  Click **Link main accounts** to view all available main accounts. You can indicate which main account to link to the concept category.

9.  Click **Link all** to link all the main accounts to the ISR concept category.

10. Close the forms to save your changes.

## Define the ISR annual rate

Use the **ISR rate table** form to set up annual rates to generate the ISR reports.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **ISR report setup**.

2.  Select an ISR report concept category, and then click **ISR rate table** to open the **ISR rate table** form.

3.  Press CTRL+N to create a new ISR annual rate.

4.  In the **Year** field, enter the fiscal year for which the ISR rate is to be applied.

5.  In the **Minimum amount** and **Maximum amount** fields, enter the lower limit and upper limit for the ISR calculation.

6.  In the **Month** field, enter the month of the fiscal year for which the ISR rate is to be applied.

7.  In the **Fixed amount** field, enter the fixed amount for the ISR rate.

8.  In the **Rate%** field, enter the ISR rate percentage.

9.  Close the forms to save your changes.

## Generate the ISR report

Use the **ISR reports** form to generate the ISR provisional payment report.

1.  Click **General ledger** \> **Reports** \> **External** \> **ISR reports**.

2.  In the **Month** field, enter the month for the ISR report.

3.  In the **Year** field, enter the year for the ISR report.

4.  In the **Utility ratio** field, enter the utility ratio amount for the ISR calculation.

5.  In the **Type of report** field, select the type of ISR report:
    
      - **Details** – Generates a detailed report with ledger transactions for each ISR report concept and main account.
    
      - **Summary** – Generates the ISR report with a summary of ISR provisional payments.

6.  Click **OK** to generate the ISR report.

## See also

[(MEX) Define tax registration numbers for a company and a vendor account](mex-define-tax-registration-numbers-for-a-company-and-a-vendor-account.md)

  


