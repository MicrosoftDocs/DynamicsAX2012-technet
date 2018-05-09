---
title: FormType Enumeration (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: FormType Enumeration
ms:assetid: T:Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.retail.pos.contracts.services.formtype(v=AX.60)
ms:contentKeyID: 47343836
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.BankDrop
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CreditMemo
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.PackingSlip
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CardReceiptForCustReturn
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.TenderDeclaration
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.QuotationReceipt
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.EFTMessage
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.GiftCertificate
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CustAcntReceiptForCustReturn
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.RemoveTender
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CreditMemoBalance
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.PickupReceipt
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.SalesOrderReceipt
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.SafeDrop
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.SalesInvoiceReceipt
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CustomerAccountDeposit
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.Invoice
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.Receipt
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CustAcntReceiptForShop
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CustAcntReceiptForShopReturn
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.FloatEntry
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CardReceiptForShop
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CardReceiptForCust
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.Unknown
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CardReceiptForShopReturn
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.CustAcntReceiptForCust
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.SalesOrderSummary
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.GiftReceipt
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType.ReturnLabel
dev_langs:
- CSharp
- C++
- VB
---

# FormType Enumeration

The Microsoft.Dynamics.Retail.Pos.Contracts.Services.FormType interface indicates the form type

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Public Enumeration FormType
'Usage
Dim instance As FormType
```

``` csharp
public enum FormType
```

``` c++
public enum class FormType
```

## Members

<table>
<thead>
<tr class="header">
<th></th>
<th>Member name</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td>Unknown</td>
<td>0</td>
</tr>
<tr class="even">
<td></td>
<td>Receipt</td>
<td>1</td>
</tr>
<tr class="odd">
<td></td>
<td>CardReceiptForShop</td>
<td>2</td>
</tr>
<tr class="even">
<td></td>
<td>CardReceiptForCust</td>
<td>3</td>
</tr>
<tr class="odd">
<td></td>
<td>CardReceiptForShopReturn</td>
<td>4</td>
</tr>
<tr class="even">
<td></td>
<td>CardReceiptForCustReturn</td>
<td>5</td>
</tr>
<tr class="odd">
<td></td>
<td>EFTMessage</td>
<td>6</td>
</tr>
<tr class="even">
<td></td>
<td>CustAcntReceiptForShop</td>
<td>7</td>
</tr>
<tr class="odd">
<td></td>
<td>CustAcntReceiptForCust</td>
<td>8</td>
</tr>
<tr class="even">
<td></td>
<td>CustAcntReceiptForShopReturn</td>
<td>9</td>
</tr>
<tr class="odd">
<td></td>
<td>CustAcntReceiptForCustReturn</td>
<td>10</td>
</tr>
<tr class="even">
<td></td>
<td>TenderDeclaration</td>
<td>11</td>
</tr>
<tr class="odd">
<td></td>
<td>Invoice</td>
<td>12</td>
</tr>
<tr class="even">
<td></td>
<td>RemoveTender</td>
<td>13</td>
</tr>
<tr class="odd">
<td></td>
<td>CustomerAccountDeposit</td>
<td>14</td>
</tr>
<tr class="even">
<td></td>
<td>CreditMemo</td>
<td>15</td>
</tr>
<tr class="odd">
<td></td>
<td>CreditMemoBalance</td>
<td>16</td>
</tr>
<tr class="even">
<td></td>
<td>FloatEntry</td>
<td>17</td>
</tr>
<tr class="odd">
<td></td>
<td>SalesOrderReceipt</td>
<td>18</td>
</tr>
<tr class="even">
<td></td>
<td>SalesInvoiceReceipt</td>
<td>19</td>
</tr>
<tr class="odd">
<td></td>
<td>GiftCertificate</td>
<td>20</td>
</tr>
<tr class="even">
<td></td>
<td>QuotationReceipt</td>
<td>21</td>
</tr>
<tr class="odd">
<td></td>
<td>PackingSlip</td>
<td>22</td>
</tr>
<tr class="even">
<td></td>
<td>PickupReceipt</td>
<td>23</td>
</tr>
<tr class="odd">
<td></td>
<td>BankDrop</td>
<td>30 This layout not in AX, actual ID is unknown</td>
</tr>
<tr class="even">
<td></td>
<td>SafeDrop</td>
<td>31 This layout not in AX, actual ID is unknown</td>
</tr>
<tr class="odd">
<td></td>
<td>SalesOrderSummary</td>
<td>32 Sales order summary</td>
</tr>
<tr class="even">
<td></td>
<td>GiftReceipt</td>
<td>33 Gift Receipt</td>
</tr>
<tr class="odd">
<td></td>
<td>ReturnLabel</td>
<td>34 Return label</td>
</tr>
</tbody>
</table>


## Remarks

These values must align with the RetailFormLayout table in AX. See the RetailConnSeedDataGenerator and setPOSIsFormLayout classes.

## See Also

#### Reference

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

