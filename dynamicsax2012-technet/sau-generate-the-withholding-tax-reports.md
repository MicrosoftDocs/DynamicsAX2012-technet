---
title: (SAU) Generate the withholding tax reports
TOCTitle: (SAU) Generate the withholding tax reports
ms:assetid: 8d742be6-b29b-492f-ba6c-c604e21d35cb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209357(v=AX.60)
ms:contentKeyID: 36058502
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Saudi Arabia
---

# (SAU) Generate the withholding tax reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In accordance with Department of Zakat and Income Tax (DZIT) regulations, you must generate the following withholding tax reports that contain details of the withholding tax transactions:

  - **Saudi Arabia monthly withholding tax report** – You must generate this report every month, and then submit it to the DZIT within the first ten days of the following month.

  - **Saudi Arabia annual withholding tax report** – You must generate this report annually, and then submit it to the DZIT within 120 days after the end of the fiscal year.

In addition to these reports, you can also generate a withholding tax slip for each payment made to a vendor from which you have withheld or deducted tax.

## Generate the Saudi Arabia monthly withholding tax report

1.  Click **General ledger** \> **Reports** \> **External** \> **Withholding tax** \> **Saudi Arabia monthly withholding tax report**.

2.  In the **Settlement period** field, select the settlement period for which the tax report is generated.

3.  In the **Month** field, select the month that you want to generate the withholding tax report for. The fiscal year of the specified settlement period is displayed in the **Year** and **Fiscal year** fields.

4.  In the **Delay fine** field, enter the delay fine that is imposed on the taxpayer for late filing and payment.

5.  In the **Evasion fine** field, enter the evasion fees as calculated by the company. This fine is imposed if it becomes clear that the taxpayer has deliberately concealed facts that may increase their tax liability.

6.  Click **OK** to generate the report.

## Generate the Saudi Arabia annual withholding tax report

1.  Click **General ledger** \> **Reports** \> **External** \> **Withholding tax** \> **Saudi Arabia annual withholding tax report**.

2.  In the **Fiscal year** field, select the fiscal year that you want to generate the withholding tax report for.

3.  Click **OK** to generate the report.

## Generate the withholding tax slip

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new journal, and then click **Lines** to open the **Journal voucher** form. For more information, see [Journal voucher - Vendor payment journal (form)](https://technet.microsoft.com/en-us/library/aa599011\(v=ax.60\)).

3.  Enter the required payment details, and then click **Print** \> **Withholding tax slip** to generate the withholding tax slip for the vendor payment.

4.  Close the forms.

## See also

[(SAU) Saudi Arabia annual withholding tax report (TaxWithholdYearlyReport\_SA)](sau-saudi-arabia-annual-withholding-tax-report-taxwithholdyearlyreport-sa.md)

[(SAU) Saudi Arabia monthly withholding tax report (TaxWithholdMonthlyReport\_SA)](sau-saudi-arabia-monthly-withholding-tax-report-taxwithholdmonthlyreport-sa.md)

  


