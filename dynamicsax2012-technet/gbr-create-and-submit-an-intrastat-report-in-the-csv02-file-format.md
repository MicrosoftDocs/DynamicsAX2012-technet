---
title: (GBR) Create and submit an Intrastat report in the CSV02 file format
TOCTitle: (GBR) Create and submit an Intrastat report in the CSV02 file format
ms:assetid: a58c635f-f019-4114-8f64-484da74e2ab2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242682(v=AX.60)
ms:contentKeyID: 36058865
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Intrastat
- Create and submit Intrastat reports in the CSV02 file format
- Great Britain
---

# (GBR) Create and submit an Intrastat report in the CSV02 file format [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can now create and submit your Intrastat reports in the new CSV02 file format, which is an updated version of the CSV format. The Intrastat declaration is used to report the movement of goods between European Union (EU) member states. British companies can use the **Intrastat** form to generate an Intrastat declaration in CSV format for submittal to Her Majesty’s Revenue and Customs (HMRC) authority. In CSV02, all string characters are in uppercase. The values of all amounts are rounded up to the nearest whole number. For more information, see [About Intrastat](about-intrastat.md).

Before you generate an Intrastat report, you must first transfer transactions from product receipts, packing slips and invoices to the **Intrastat** form. You can report input transactions for arrivals and output transactions for dispatches in the Intrastat report.

1.  Click **Organization administration** \> **Periodic** \> **Foreign trade** \> **Intrastat**.

2.  Click **Transfer UK** to open the **Dialog** form.

3.  Select one or all of the following check boxes to transfer the transactions to the **Intrastat** form:
    
      - **Free text invoice** – Transfer the free text invoice transactions.
    
      - **Customer invoice** – Transfer the customer invoice transactions.
    
      - **Customer packing slips** – Transfer the customer packing slip transactions.
    
      - **Vendor invoice** – Transfer the vendor invoice transactions.
    
      - **Vendor product receipts** – Transfer the vendor product receipt transactions.
    
      - **Project invoice** – Transfer the project invoice transactions.

4.  Click **OK** to transfer transactions from the selected transaction types.

5.  Click **Output** \> **Diskette UK** to open the **Create Intrastat diskette in British layout** form.

6.  Under the **Input transactions** field group, in the **File name** field, specify the file name and path of the report file for input transactions.

7.  Under the **Output transactions** field group, in the **File name** field, specify the file name and path of the report file for output transactions.

8.  In the **Month** and **Years** fields, select the month and year for the Intrastat declaration.

9.  Click **OK** to generate the Intrastat declaration for input and output transactions to the specified paths in the CSV02 format.

10. Close the form to save your changes.

## See also

[Intrastat (form)](https://technet.microsoft.com/en-us/library/aa619055\(v=ax.60\))

[(GBR) Make diskette for Intrastat in British layout (class form)](https://technet.microsoft.com/en-us/library/aa575118\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

