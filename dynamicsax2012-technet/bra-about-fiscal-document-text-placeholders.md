---
title: (BRA) About fiscal document text placeholders
TOCTitle: (BRA) About fiscal document text placeholders
ms:assetid: 4506c98e-15a0-4a29-8d18-f571ccad4520
ms:mtpsurl: https://technet.microsoft.com/library/JJ710483(v=AX.60)
ms:contentKeyID: 49384376
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- placeholders
- BRA
- Brazil
- fiscal document
- fiscal document placeholders
- fiscal document text
- BR - 00020
audience: Application User
ms.search.region: Brazil
---

# (BRA) About fiscal document text placeholders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Fiscal document text placeholders are predefined tags that represent specific values. You can include the placeholders in the **Text** field in the **Fiscal document source texts** form when you create a fiscal document source text. You can also include placeholders in the **Note** field in the **Fiscal document texts** form when you attach a fiscal document text to a sales order, purchase order, or free text invoice. When you post a sales order, purchase order, or free text invoice that has a fiscal document text that includes placeholders, the placeholders are replaced by the values in the predefined tags.

## Tags that support fiscal document texts for referenced processes

The following table contains the predefined tags that support fiscal document texts for referenced processes, and their values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Predefined tag</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%RefProcess_TaxAuthorityName</p></td>
<td><p>The name of the tax authority.</p></td>
</tr>
<tr class="even">
<td><p>%RefProcess_TaxAuthorityAgency</p></td>
<td><p>The agency of the tax authority.</p></td>
</tr>
<tr class="odd">
<td><p>%RefProcess_RefProcessNumber</p></td>
<td><p>The number of the referenced process.</p></td>
</tr>
</tbody>
</table>


## Tag that supports fiscal document texts for SUFRAMA

The following table contains the predefined tag that supports fiscal document texts for Superintendência da Zona Franca de Manaus (SUFRAMA), and its value.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Predefined tag</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%Suframa_CustNumber</p></td>
<td><p>The SUFRAMA customer number.</p></td>
</tr>
</tbody>
</table>


## Tags that support fiscal document texts for taxes

The following table contains the predefined tags that support fiscal document texts for taxes, and their values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Predefined tag</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%ICMS</p></td>
<td><p>The Imposto Sobre Circulação de Mercadorias e Serviços (ICMS) tax amount.</p></td>
</tr>
<tr class="even">
<td><p>%PIS</p></td>
<td><p>The Programa de Integração Social (PIS) contribution amount.</p></td>
</tr>
<tr class="odd">
<td><p>%COFINS</p></td>
<td><p>The Contribuição para o financiamente da securidade social (COFINS) contribution amount.</p></td>
</tr>
</tbody>
</table>


## Tags that support fiscal document texts for fiscal references

The following table contains the predefined tags that support fiscal document texts for fiscal references, and their values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Predefined tag</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%FiscalRef_InvNoRef</p></td>
<td><p>The number of the reference invoice.</p></td>
</tr>
<tr class="even">
<td><p>%FiscalRef_InvSeriesRef</p></td>
<td><p>The series of the reference invoice.</p></td>
</tr>
<tr class="odd">
<td><p>%FiscalRef_InvDateRef</p></td>
<td><p>The date of the reference invoice.</p></td>
</tr>
<tr class="even">
<td><p>%FiscalRef_InvAccNameRef</p></td>
<td><p>The account name of the reference invoice.</p></td>
</tr>
<tr class="odd">
<td><p>%FiscalRef_InvAccAddressRef</p></td>
<td><p>The address of the reference invoice.</p></td>
</tr>
<tr class="even">
<td><p>%FiscalRef_InvAccIENumberRef</p></td>
<td><p>The Inscrição Estadual (IE), or state registration number, of the reference invoice account.</p></td>
</tr>
<tr class="odd">
<td><p>%FiscalRef_InvAccCNPJCPFNumRef</p></td>
<td><p>The Cadastro Nacional da Pessoa Jurídica (CNPJ), or taxpayer registration number, of the reference invoice account.</p></td>
</tr>
</tbody>
</table>


## Tags that support fiscal document texts that involve vendor information

The following table contains the predefined tags for vendor information, and their values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Predefined tag</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%Vendor_Name</p></td>
<td><p>The name of the vendor.</p></td>
</tr>
<tr class="even">
<td><p>%Vendor_CNPJ_CPF</p></td>
<td><p>The Cadastro Nacional da Pessoa Jurídica (CNPJ)/Cadastro de Pessoas Físicas (CPF), or taxpayer registration number, of the vendor.</p></td>
</tr>
<tr class="odd">
<td><p>%Vendor_IE</p></td>
<td><p>The IE of the vendor.</p></td>
</tr>
<tr class="even">
<td><p>%Vendor_Address</p></td>
<td><p>The address of the vendor.</p></td>
</tr>
</tbody>
</table>


## Tags that support fiscal document texts that involve customer information

The following table contains the predefined tags for customer information, and their values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Predefined tag</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%Customer_Name</p></td>
<td><p>The name of the customer.</p></td>
</tr>
<tr class="even">
<td><p>%Customer_CNPJ_CPF</p></td>
<td><p>The CNPJ/CPF of the customer.</p></td>
</tr>
<tr class="odd">
<td><p>%Vendor_IE</p></td>
<td><p>The IE of the customer.</p></td>
</tr>
<tr class="even">
<td><p>%Vendor_Address</p></td>
<td><p>The address of the customer.</p></td>
</tr>
</tbody>
</table>


## Tags that support fiscal document texts for withholding taxes

The following table contains the predefined tags for withholding taxes, and their values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Predefined tag</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%TaxWithhold_Code</p></td>
<td><p>The withholding tax code.</p></td>
</tr>
<tr class="even">
<td><p>%TaxWithhold_Value</p></td>
<td><p>The rate of withholding tax.</p></td>
</tr>
<tr class="odd">
<td><p>%TaxWithhold_Amount</p></td>
<td><p>The amount of withholding tax.</p></td>
</tr>
</tbody>
</table>


## Tags that support fiscal document texts for imports

The following table contains the predefined tags for imports, and their values.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Predefined tag</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>%DI_Number</p></td>
<td><p>The identifier of the import declaration document.</p></td>
</tr>
<tr class="even">
<td><p>%DI_Date</p></td>
<td><p>The date that the import declaration document was issued.</p></td>
</tr>
<tr class="odd">
<td><p>%ImportTax</p></td>
<td><p>The import tax amount.</p></td>
</tr>
<tr class="even">
<td><p>%Freight</p></td>
<td><p>The freight amount for the import.</p></td>
</tr>
<tr class="odd">
<td><p>%Insurance</p></td>
<td><p>The insurance amount for the import.</p></td>
</tr>
<tr class="even">
<td><p>%Siscomex</p></td>
<td><p>The charge amount for Sistema Integrado de Comércio Exterior (Siscomex).</p></td>
</tr>
<tr class="odd">
<td><p>%ExchRate</p></td>
<td><p>The exchange rate that is used in the import.</p></td>
</tr>
</tbody>
</table>


## See also

[(BRA) Set up a fiscal document source text](bra-set-up-a-fiscal-document-source-text.md)

[(BRA) Fiscal document source texts (form)](https://technet.microsoft.com/library/jj663934\(v=ax.60\))

[(BRA) Attach fiscal document texts to a free text invoice](bra-attach-fiscal-document-texts-to-a-free-text-invoice.md)

[(BRA) Attach fiscal document texts to a fiscal document](bra-attach-fiscal-document-texts-to-a-fiscal-document.md)

  


