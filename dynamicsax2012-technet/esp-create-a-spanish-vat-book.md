---
title: (ESP) Create a Spanish VAT book
TOCTitle: (ESP) Create a Spanish VAT book
ms:assetid: 7adc593e-c0da-4444-9cd9-dab6319fd162
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213022(v=AX.60)
ms:contentKeyID: 36058250
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Spain
---

# (ESP) Create a Spanish VAT book 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Spanish companies must submit VAT declarations to the Spanish tax authorities. VAT transactions must be listed in periodic reports and be included in the appropriate VAT book, such as VAT receivable, VAT payable, and capital allowance.

Use the **Spanish VAT books** form to create VAT book types and assign sales tax codes to the VAT books.

One of the periodic VAT reports, the 340 report, must be submitted monthly to the tax authorities. This report contains details of sales and purchases and the associated taxes for a specified period. It is generated as an ASCII file.

After you generate the ASCII file, log on to the **Agencia Tributaria** website and upload the ASCII file. Once uploaded, the ASCII file is validated, and you will be notified of any errors in the file. Use the procedures to set up a sales tax code for the VAT book and generate a 340 report.

## Set up a Spanish VAT book

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Spain** \> **Spanish VAT books**.

2.  Click **New** to enter a VAT book code and description.

3.  On the **General** FastTab, in the **Book type** field, select the VAT book type from the following options:
    
      - **Sales tax receivable**
    
      - **Sales tax payable**
    
      - **All the books**

4.  Select a number sequence code.

5.  Click the **Setup** FastTab, and then select a sales tax code to specify which VAT book that the VAT transactions are in. You also can select an equivalence charge code, which is a Spanish sales tax code.

## Generate the 340 report

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **Spain** \> **Spanish VAT books**..

2.  Click **Spanish VAT reports** to open the **Spanish VAT reports** form.

3.  Click **Create new** to open the **Spanish VAT list** form.

4.  In the **VAT book** field, select the VAT book for the 340 report.

5.  In the **Settlement period** and **From date** fields, select the settlement period and the start date for the 340 report.

6.  Click **OK** .

7.  In the **Spanish VAT reports** form, click **Output** \> **Export to ASCII file** to open the **Export to ASCII file** form.

8.  In the **File name** field, enter or browse to the path where the 340 report file is to be exported.

9.  Click **OK** to generate the 340 report as an ASCII file.

10. Close the form to save your changes.

## See also

[(ESP) Spanish VAT books (form)](https://technet.microsoft.com/en-us/library/aa549899\(v=ax.60\))

  


