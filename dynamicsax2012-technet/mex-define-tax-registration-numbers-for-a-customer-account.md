---
title: (MEX) Define tax registration numbers for a customer account
TOCTitle: (MEX) Define tax registration numbers for a customer account
ms:assetid: 842a449d-d6ff-4488-a489-3f67ed683540
ms:mtpsurl: https://technet.microsoft.com/library/Hh209318(v=AX.60)
ms:contentKeyID: 36058384
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Mexico
- tax registration number
- customer accounts
audience: Application User
ms.search.region: Mexico
---

# (MEX) Define tax registration numbers for a customer account 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In accordance with Mexican legislation, companies must report all customer transactions in the Declaración Informativa de Operaciones con Terceros (DIOT), a tax declaration that is submitted to the Servicios de Administración Tributaria (SAT). The following tax registration IDs must be included in the DIOT: the Registro Federal del Contribuyentes (RFC) number, Clave Única de Registro de Población (CURP) number, and state inscription number. The RFC number and state inscription number are assigned to both individuals and corporations, but CURP numbers are assigned only to individuals. The format of the tax registration number depends on the entity type, as shown in the table.

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
<td><p>12 characters in length. The first three characters represent the business name. The next six characters represent the date of the registration (YYMMDD). The last three characters are assigned by the government at random.</p></td>
</tr>
<tr class="even">
<td><p>RFC</p></td>
<td><p>Individuals</p></td>
<td><p>13 characters in length. The first four characters represent the name of the person. The next six characters represent the person’s date of birth (YYMMDD). The last three characters are assigned randomly.</p></td>
</tr>
<tr class="odd">
<td><p>CURP</p></td>
<td><p>Individuals</p></td>
<td><p>18 characters in length. The first four characters represent the name of the person, the next six characters represent the person’s date of birth (YYMMDD), the next character represents the gender of the individual (M: female or H: male), the next two characters represent the state where the person resides, and the last five characters are assigned randomly.</p></td>
</tr>
</tbody>
</table>


Use the **Customers** form to specify the CURP and RFC for a customer. When you create a sales order, the CURP and RFC numbers of the customer are printed in the following documents and reports:

  - All documents submitted to the customer.

  - Declaración Informativa de Operaciones con Terceros (DIOT).

  - **Confirm report** – Generated when you confirm and print a sales order.

  - **Packing slip report** – Generated when you confirm the packing slip.

  - **Invoice report** – Generated when you post an invoice.

## Assign a tax registration number to a customer

Use this procedure to assign a tax registration number to a customer.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Click **Customer** or double-click a customer account.

3.  Under the **Tax registration** field group in the **Company type** field, select the type of customer. **01: Legal Entity**, **02: legal person**, or **03: foreign company**.

4.  In the **RFC number** and **CURP number** fields, enter the RFC and CURP numbers.

5.  In the **State inscription** field, enter the state inscription number.

6.  Close the form to save your changes.

## See also

[Customers (form)](https://technet.microsoft.com/library/aa590606\(v=ax.60\))

[(MEX) Define tax registration numbers for a company and a vendor account](mex-define-tax-registration-numbers-for-a-company-and-a-vendor-account.md)

[(MEX) Create and post invoices for a non-managed vendor](mex-create-and-post-invoices-for-a-non-managed-vendor.md)

  


