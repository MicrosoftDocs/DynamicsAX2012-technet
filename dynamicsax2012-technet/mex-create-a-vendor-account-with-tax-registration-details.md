---
title: (MEX) Create a vendor account with tax registration details
TOCTitle: (MEX) Create a vendor account with tax registration details
ms:assetid: a327f1d6-c1bb-442f-b02a-c376ce949a4b
ms:mtpsurl: https://technet.microsoft.com/library/Hh209460(v=AX.60)
ms:contentKeyID: 36058805
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Mexico
- vendor account
- tax registration
audience: Application User
ms.search.region: Mexico
---

# (MEX) Create a vendor account with tax registration details 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In accordance with Mexican legislation, companies must report all vendor transactions in the Declaración Informativa de Operaciones con Terceros (DIOT), a tax declaration that is submitted to the Servicios de Administración Tributaria (SAT). The tax registration IDs must be included in the DIOT: the Registro Federal del Contribuyentes (RFC) number, Clave Única de Registro de Población (CURP) number, and state inscription number. The RFC number and state inscription number are assigned to both individuals and corporations, but CURP numbers are assigned only to individuals.

Use the **Vendors** form to enter the RFC, CURP, state inscription number, and other vendor details for the DIOT. You can also assign a default operation type for all vendor invoice transactions that you will create for the selected vendor.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Click **Vendor** to create a new vendor.

3.  Click the **Invoice and delivery** FastTab, and in the **Company type** field, select **01: Legal Entity** or **02: legal person**.
    
    The **RFC number**, **CURP number**, and **State inscription** fields are only available if you select the type of company.

4.  In the **RFC number** field, enter the 12-character RFC number of the vendor. The first three characters represent the company name, the next six characters represent the date of company registration (YYMMDD), and the last three characters are assigned randomly by the government.

5.  In the **CURP number** field, enter the 18-character CURP number of the vendor. The first four characters represent the individual’s name, the next six characters represent the date of birth (YYMMDD), the next character represents the gender (M: female or H: male), and the next two characters represent the state where the person resides. The last five characters are assigned randomly by the tax authority.

6.  In the **State inscription** field, enter the state inscription number of the vendor.

7.  In the **Type of vendor** field, select **04: domestic vendor**.

8.  In the **Type of operation** field, select the operation type as **03: professional services**, **06: rent/lease**, or **85: Others**.
    
    The option you select becomes the default selection when you create purchase transactions for the vendor.

9.  Close the form to save your changes.

## See also

[Vendors (form)](https://technet.microsoft.com/library/aa592162\(v=ax.60\))

  


