---
title: (MEX) Generate a monthly report of electronic invoices
TOCTitle: (MEX) Generate a monthly report of electronic invoices
ms:assetid: a7351dab-53de-4240-a42a-fcfcb5347acd
ms:mtpsurl: https://technet.microsoft.com/library/Hh242685(v=AX.60)
ms:contentKeyID: 36058875
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Mexico
---

# (MEX) Generate a monthly report of electronic invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the EInvoice monthly report to generate a report of all the electronic and paper invoices that are issued during a month. You can use the Sistema de comprobantes fiscales digitales CFD Plus (SICOFI) application website to submit the monthly report to the Servicio de Administración Tributaria (SAT) in .txt format. The report is due on or before the fifth day of the following month.

The monthly report includes the following details:

  - The Registro Federal de Contribuyentes (RFC) number assigned to the customer for whom the electronic invoice was generated

  - The series, number, and authorization code of the electronic invoice

  - The date and time that the electronic invoice was generated

  - The total VAT amount and total amount of the electronic invoice

  - The status and type of the electronic invoice

  - The name, number, and date of the customs document that was generated for the imported items that are included in the electronic invoice

The monthly report file name consists of the XML schema number that is used to generate electronic invoices, the RFC number assigned to the company, and the month and year for which the report is generated. For example, if the XML schema number is 1, the RFC number for the company is XXXX010101000, and the report is generated for October, 2010, the monthly report file name is 1XXXX010101000102010.txt.

1.  Click **Accounts receivable** \> **Periodic** \> **CFD - Electronic invoices** \> **EInvoice monthly report**.

2.  In the **Month/Year** field, select the month and year for which the report must be generated.

3.  Select the **EInvoice** check box to include only the electronic invoices issued during the month in the report.

4.  In the **File path** field, specify a path to store the report.

5.  Click **OK** to generate the monthly report of electronic invoices.

## See also

[(MEX) About electronic invoices](mex-about-electronic-invoices.md)

[(MEX) Einvoice monthly report (EInvoiceReport\_MX)](mex-einvoice-monthly-report-einvoicereport-mx.md)

  


