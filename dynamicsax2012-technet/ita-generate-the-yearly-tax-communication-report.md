---
title: (ITA) Generate the Yearly tax communication report
TOCTitle: (ITA) Generate the Yearly tax communication report
ms:assetid: fc8f7904-27cd-4e96-957b-d57963e2dc11
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433549(v=AX.60)
ms:contentKeyID: 36941369
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Italy
- Generate the Yearly Tax Communication report
- Yearly Tax Communication report
audience: Application User
ms.search.region: Italy
---

# (ITA) Generate the Yearly tax communication report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

According to Italian tax legislation, companies must submit sales and purchase information in an electronic format to the Italian tax authorities in the month of February each year. In Microsoft Dynamics AX, you can generate and export the Yearly tax communication report to an ASCII file, and then upload it to the tax authority website.

## Set up information to generate the Yearly tax communication report

You must complete the following setup procedures to generate and export the Yearly tax communication report:

  - Set up the company fiscal code and tax registration number.

  - Set up an Italian sales tax book.

  - Set up VAT codes for the Yearly tax communication report.

## Set up the company fiscal code and tax registration number

Use the **Legal entities** form to set up the fiscal code and tax registration number for a legal entity. For more information, see [Legal entities (form)](https://technet.microsoft.com/en-us/library/hh242860\(v=ax.60\)).

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click the **Tax registration** FastTab.

3.  In the **Tax registration number** field, enter the tax registration number of the company.

4.  Click the **Statutory reporting** FastTab.

5.  In the **Fiscal code** field, enter the fiscal code of the company.

6.  In the **Legal nature** field, select the legal structure of the company, such as **Limited share partnerships**, **Limited liability companies (SRL)**, or **Public limited companies (SPA)**.

7.  Close the form.

## Set up an Italian sales tax book

Use the **Italian sales tax books** form to set up information to include sales and purchase transactions in the Yearly tax communication report. For more information, see [(ITA) Italian sales tax books (form)](https://technet.microsoft.com/en-us/library/aa620738\(v=ax.60\)). You must also set up number sequences for the sales tax books. After you assign the number sequences, they remain linked to the sales tax purpose for which they were set up. When you post the transactions, the voucher numbers are ordered sequentially by the posting date, and the sales tax transactions that have the same number sequence code are posted in sequence.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Italian sales tax books**.

2.  Create an Italian sales tax book. For more information, see [(ITA) Italian sales tax books (form)](https://technet.microsoft.com/en-us/library/aa620738\(v=ax.60\)).

3.  In the **ATECOFIN Code** field, enter the tax code for sales tax reporting.

4.  Select the **Print summary and payment** check box to print the value-added tax (VAT) summary and VAT payment in the report.

5.  Close the form.

## Set up VAT codes for the Yearly tax communication report

Use the **Yearly tax communication setup** form to set up VAT codes for the capital goods that are sold and purchased. For more information, see [(ITA) Yearly tax communication (form)](https://technet.microsoft.com/en-us/library/hh242665\(v=ax.60\)).

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **External** \> **Yearly tax communication setup**.

2.  In the **Capital goods sold** and **Capital goods purchased** fields, select the appropriate VAT codes.

3.  Close the form.

## Generate and export the Yearly tax communication report

Use the **Yearly tax communication** form to generate the Yearly tax communication report and export the information to an ASCII file that is sent to the tax authorities. For more information, see [(ITA) Yearly tax communication (form)](https://technet.microsoft.com/en-us/library/hh242665\(v=ax.60\)). The report and ASCII file include details of the amounts of purchases and sales of capital goods. The fiscal code and tax registration number specified in the **Legal entities** form are also included in the report and ASCII file.

1.  Click **General ledger** \> **Reports** \> **External** \> **Yearly tax communication**.

2.  Click **Create new** to create a yearly tax communication record.

3.  Select the yearly tax communication record, and then click **Open**. In the **Yearly tax communication** form, the **Module** field group is updated with details of the tax communication, such as the tax communication ID, ATECOFIN code, and the year for which tax is being declared. The **Company name** and **Company tax registration number** fields are updated with the company details from the **Legal entities** form.

4.  In the **Fiscal code** field, enter the fiscal code of the company.

5.  Click the **Tax data** tab.

6.  In the **Capital goods sold** field, enter the amount of capital goods sold for the year.

7.  In the **Capital goods purchased** field, enter the amount of capital goods purchased for the year.

8.  Close the form.

9.  In the **Yearly tax communication** form, click **Print** to print the Yearly tax communication report.
    
    –or–
    
    Click **Export to**.

10. In the **Create export file** form, in the **File name** field, specify the file name and path to export the ASCII file.

11. Click **OK** to save the ASCII file in the specified path.

12. Close the forms.

## See also

[(ITA) Yearly tax communication details (form)](https://technet.microsoft.com/en-us/library/hh433551\(v=ax.60\))

  


