---
title: (AUT) Generate an Austrian sales tax report
TOCTitle: (AUT) Generate an Austrian sales tax report
ms:assetid: 73337299-b912-4fbb-b579-64aa943985bb
ms:mtpsurl: https://technet.microsoft.com/library/Hh209225(v=AX.60)
ms:contentKeyID: 36058139
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Austria
- sales tax
audience: Application User
ms.search.region: Austria
---

# (AUT) Generate an Austrian sales tax report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can generate the Austrian annual sales tax report as a .pdf file for all sales tax reporting codes that are specified in the Austrian reporting layout. You can also generate a monthly sales tax statement as an .xml file, which can be uploaded to the online Austrian Ministry of Finance portal.

## Generate an annual sales tax report

1.  Click **General ledger** \> **Reports** \> **External** \> **Annual sales tax (Austria)**.

2.  In the **From date** and **To date** fields, select or enter the starting and ending dates for the fiscal year.

3.  In the **Settlement period** field, select a code to identify the sales tax settlement period.

4.  In the **PDF file** field, enter the path of the annual VAT statement .pdf file. When the file is generated, it will contain the sales tax data. You must download the .pdf file from the website of the Austrian Ministry of Finance, and store it on your computer before you can generate the annual sales tax report.

5.  Click **OK** to generate the .pdf file as an .fdf file, which is a text file that is used with the pdf file format.

## Generate a monthly sales tax statement

1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.

2.  In the **Settlement period** field, select the applicable reporting period. If the settlement period and the Austrian report layout are linked to your sales tax authority, you will be asked to specify the path where the monthly VAT statement .pdf and the XML file are to be created.

3.  In the **From date** field, specify the first day of the sales tax settlement period for which sales tax is to be calculated. This corresponds to the date in the **From date** field on the **Sales tax settlement periods** form.

4.  In the **Transaction date** field, specify the date when the sales tax report is calculated. The default value is the current date. The ending date of the settlement period shown in the **From date** field corresponds to the **To date** field in the **Sales tax settlement periods** form. The sales tax payment is calculated for all transactions that were posted within the settlement period.

5.  In the **Sales tax payment version** field, select the type of transactions to include in the sales tax payment calculation.
    
      - **Original** – Sales tax transactions of the first posted settlement calculation for the period.
    
      - **Corrections** – Sales tax transactions that were not included in the first posted settlement calculation for the period. The report includes all subsequent payments that were posted for the settlement period.
    
      - **Latest corrections** – Sales tax transactions included in the most recent settlement calculation made for the period. If you select the **Update** check box and this option, the settlement calculation of the current job is the most recent settlement calculation.
    
      - **Total list** – All sales tax transactions to be settled in the current period.
        

        > [!NOTE]
        > <P>This field is not available if you select the <STRONG>Include corrections</STRONG> check box on the <STRONG>Sales tax</STRONG> tab of the <STRONG>General ledger parameters</STRONG> form.</P>



6.  Select the **Update** check box to post the sales tax payment calculations for the settlement period.

7.  Click **OK** and specify the path to generate the monthly sales tax statement as an .xml file.

## See also

[(AUT) Austrian annual sales tax report (TaxReportYearly\_AT)](aut-austrian-annual-sales-tax-report-taxreportyearly-at.md)

[(AUT) Create sales tax reporting codes](aut-create-sales-tax-reporting-codes.md)

  


