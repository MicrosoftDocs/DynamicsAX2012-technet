---
title: Credit invoicing configuration key (CustVendCreditInvoicing)
TOCTitle: Credit invoicing configuration key (CustVendCreditInvoicing)
ms:assetid: 18cf83e3-2063-4b4c-9487-10adf5c612c1
ms:mtpsurl: https://technet.microsoft.com/library/Aa572421(v=AX.60)
ms:contentKeyID: 36997741
author: Khairunj
ms.author: daxcpft
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Data_Dictionary.Configuration_Keys.CustVendCreditInvoicing
---

# Credit invoicing configuration key (CustVendCreditInvoicing) 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The **Credit invoicing** configuration key is deprecated in Microsoft Dynamics AX 2012. The functionality that it controlled in previous releases is automatically available to legal entities whose primary address is in Spain or Sweden.

The credit invoicing feature creates a relation between a credit note and the original invoice that you want to correct. This feature also lets you enter the reason for the correction. After this information is stored, information that is related to the original invoice is printed on the credit note.

The following functionality is included with this feature:

  - The **Apply the credit invoicing layout into sales and project invoice reports** check box is displayed in the **Accounts receivable parameters** form.

  - The **Apply the credit invoicing layout to vendor invoice reports** check box is displayed in the **Accounts payable parameters** form.

  - The **View the customer transactions related to credit invoicing** button is displayed in the **Customer transactions** form.

  - The **View the vendor transactions related to credit invoicing** button is displayed in the **Vendor transactions** form.

  - The credit invoicing information is displayed on the relevant reports.

You can enable or disable this key in the **License configuration** form.

## Forms affected by the feature

The following forms are affected when the feature is enabled.

## Accounts payable forms

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Accounts payable parameters</strong></p></td>
<td><p><a href="https://technet.microsoft.com/library/aa596348(v=ax.60)">Accounts payable parameters (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Vendor transactions</strong></p></td>
<td><p><a href="https://technet.microsoft.com/library/aa572427(v=ax.60)">Vendor transactions (form)</a></p></td>
</tr>
</tbody>
</table>


## Accounts receivable forms

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Form</p></th>
<th><p>For more information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Accounts receivable parameters</strong></p></td>
<td><p><a href="https://technet.microsoft.com/library/aa576993(v=ax.60)">Accounts receivable parameters (form)</a></p></td>
</tr>
<tr class="even">
<td><p><strong>Customer transactions</strong></p></td>
<td><p><a href="https://technet.microsoft.com/library/aa634902(v=ax.60)">Customer transactions (form)</a></p></td>
</tr>
</tbody>
</table>


## Additional information about this configuration key

The following table provides information about how this configuration key relates to other configuration keys and license codes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Detail</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>License code</p></td>
<td><p><strong>Users</strong></p></td>
</tr>
<tr class="even">
<td><p>Parent key</p></td>
<td><p><strong>Multiple countries/regions</strong></p></td>
</tr>
<tr class="odd">
<td><p>Child keys</p></td>
<td><p>None</p></td>
</tr>
</tbody>
</table>


For more information about how license codes and configuration keys work together, see [About license codes and configuration keys](https://technet.microsoft.com/library/aa548653\(v=ax.60\)).

  


