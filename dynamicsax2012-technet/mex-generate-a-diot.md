---
title: (MEX) Generate a DIOT
TOCTitle: (MEX) Generate a DIOT
ms:assetid: d067b7cf-435b-456f-8f34-3a2b18bbbfbf
ms:mtpsurl: https://technet.microsoft.com/library/Hh242917(v=AX.60)
ms:contentKeyID: 36059487
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Mexico
- generate
- DIOT
- SSRS_Reports.Reports.DIOTDeclaration_MX
audience: Application User
ms.search.region: Mexico
---

# (MEX) Generate a DIOT 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Generate DIOT declaration** form to generate a Declaración Informativa de Operaciones con Terceros (DIOT).

1.  Click **General ledger** \> **Reports** \> **Mexican tax reports** \> **Generate DIOT declaration**.

2.  On the **General** tab, in the **From date** and **To date** fields, select the starting date and ending date of the reporting period.

3.  In the **DIOT report type** field, select one of the following options to indicate the type for the DIOT:
    
    **1: consolidated** – Summarizes the vendor transactions that are created for a specific Registro Federal de Contribuyentes (RFC) number or registration ID.
    
    **2: detailed** – Generates a detailed report that contains information about all vendor transactions. Each line in the report represents a transaction.

4.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Include transactions** field, select one of the following options to indicate the type of vendor invoice transactions to include in the report:
    
      - **Open** – Include transactions that have not been settled. In other words, transactions that have a current balance that is not equal to zero.
    
      - **Closed** – Include transactions that have been settled. In other words, transactions that have a current balance that is equal to zero.
    
      - **All** – Include all transactions.

5.  In the **File name** field, specify the path and file name for the DIOT.

6.  Select the **Generate file** check box to generate the DIOT as a text file.

7.  In the **Percentage of global vendor operations** field, enter the percentage of total transactions that are considered global vendor transactions.

8.  In the **Upper limit** field, enter the maximum transaction amount for a global vendor.

9.  Click **OK** to generate the DIOT.

## See also

[(MEX) Generate the DIOT declaration report (DIOTDeclaration\_MX)](mex-generate-the-diot-declaration-report-diotdeclaration-mx.md)

  


