---
title: (MEX) Define tax registration numbers for a company and a vendor account
TOCTitle: (MEX) Define tax registration numbers for a company and a vendor account
ms:assetid: 6b0da322-8f95-4a70-9ab9-82c820074c05
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242611(v=AX.60)
ms:contentKeyID: 36057986
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Mexico
- customer
- tax registration number
audience: Application User
ms.search.region: Mexico
---

# (MEX) Define tax registration numbers for a company and a vendor account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In accordance with Mexican legislation, companies in Mexico must report all customer and vendor transactions in the Declaración Informativa de Operaciones con Terceros (DIOT), a tax declaration that is submitted to the Servicios de Administración Tributaria (SAT). The following tax registration IDs are included in the DIOT: the Registro Federal del Contribuyentes (RFC) number, Clave Única de Registro de Población (CURP) number, and state inscription number.

The RFC number and state inscription number are assigned to both individuals and corporations, but CURP numbers are assigned only to individuals. The formats of the tax registration numbers are shown in the table below.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tax registration ID</p></th>
<th><p>Entity type</p></th>
<th><p>Format</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>RFC</p></td>
<td><p>Corporations</p></td>
<td><p>12 characters in length. The first three characters represent the business name, the next six characters represent the company’s registration date (YYMMDD), and the last three characters are assigned randomly by the tax authority.</p></td>
</tr>
<tr class="even">
<td><p>RFC</p></td>
<td><p>Individuals</p></td>
<td><p>13 characters in length. The first four characters represent the person’s name, the next six characters represent the date of birth (YYMMDD), and the last three characters are assigned randomly by the tax authority.</p></td>
</tr>
<tr class="odd">
<td><p>CURP</p></td>
<td><p>Individuals</p></td>
<td><p>18 characters in length. The first four characters represent the person’s name, the next six characters represent the individual’s date of birth (YYMMDD), the next character represents the gender (M: Female or H: Male), and the next two characters represent the state where the person resides. The last five characters are assigned randomly by the tax authority.</p></td>
</tr>
</tbody>
</table>


The CURP and RFC numbers are printed in sales and purchase documents as well as the tax declaration report.

## Set up tax registration ID for a company

Use the **Legal entities** form to enter the RFC, CURP, and state inscription numbers for a company.

1.  Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**.

2.  Click the **Tax registration** FastTab, in the **Company type** field, select the type of company as **01: Legal Entity**, **02: legal person**, or **03: foreign company**.

3.  In the **RFC number** field, enter the RFC number for the selected company type.

4.  In the **CURP number** field, enter the CURP number.

5.  In the **State inscription** field, enter the state inscription number.

6.  Click the **Statutory reporting** FastTab, under the **Mexico** field group in the **Legal representative** field, enter the name of the person in the company who serves as the legal representative for tax issues.

7.  In the **RFC number** field and **CURP number** fields, enter the RFC and CURP numbers for the legal representative.

8.  Close the form to save your changes.

## Define tax registration for vendor accounts

Use the **Vendors** form to enter the RFC and CURP numbers for a domestic or a foreign vendor. When you create and post a purchase order, the RFC and CURP numbers specified for the vendor are printed in the purchase order documents and reports.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Click **Vendor** or double-click a vendor account.

3.  Click the **Invoice and delivery** FastTab, and under the **Tax registration** field group, in the **Company type** field, select the type of company as **01: Legal Entity**, **02: legal person**, or **03: foreign company**.

4.  In the **RFC number** field, enter the RFC number.

5.  In the **CURP number** field, enter the CURP number.

6.  In the **State inscription** field, enter the State inscription number.

7.  Under the **Diot Information** field group, in the **Type of vendor** field, select the type of vendor as **04: domestic vendor**, **05: foreign vendor**, or **15: domestic/global vendor**.
    
    The domestic value is used to differentiate vendors as domestic or foreign depending on the amounts declared in the DIOT. If the total amount of payments to be declared is greater than the maximum value allowed, the value is domestic. The global value is used to identify the vendors depending on the total amount declared in the DIOT. If the total amount of payments to be declared is less than or equal to the maximum value allowed, the value is global.

8.  In the **Type of operation**, select the type of operation as **03: professional services**, **06: rent/lease**, or **85: Others**.

9.  In the **Tax registration ID** field, enter the tax registration number for a foreign vendor. The tax registration number contains 40 characters. You can view the country code and nationality of the vendor in the **Country/region code** and **Nationality** fields. For more information, see [(MEX) Create a vendor account with tax registration details](mex-create-a-vendor-account-with-tax-registration-details.md).

10. Close the form to save your changes.

## See also

[Vendors (form)](https://technet.microsoft.com/en-us/library/aa592162\(v=ax.60\))

[Legal entities (form)](https://technet.microsoft.com/en-us/library/hh242860\(v=ax.60\))

  


