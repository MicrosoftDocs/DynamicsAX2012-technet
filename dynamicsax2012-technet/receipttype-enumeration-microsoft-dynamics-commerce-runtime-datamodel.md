---
title: ReceiptType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ReceiptType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.receipttype(v=AX.60)
ms:contentKeyID: 62212536
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.GiftCertificate
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CustomerAccountReceiptForShop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.FloatEntry
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CreditMemo
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CustomerAccountReceiptForCustomerReturn
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CardReceiptForCustomerReturn
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CardReceiptForShopReturn
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CustomerAccountReceiptForShopReturn
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CustomerAccountDeposit
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.BankDrop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CardReceiptForShop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CustomerAccountReceiptForCustomer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.CardReceiptForCustomer
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.TenderDeclaration
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.StartingAmount
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.ReturnLabel
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.RemoveTender
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.SalesOrderReceipt
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.XReport
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.PickupReceipt
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.SalesReceipt
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.QuotationReceipt
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.ZReport
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.SafeDrop
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.PackingSlip
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReceiptType.Unknown
dev_langs:
- CSharp
- C++
- VB
---

# ReceiptType Enumeration

The different receipt types.

The source of these values is the FORMLAYOUTID in the RETAILFORMLAYOUT table in Ax.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Enumeration ReceiptType
'Usage
Dim instance As ReceiptType
```

``` csharp
public enum ReceiptType
```

``` c++
public enum class ReceiptType
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
<td>Unknown receipt type.</td>
</tr>
<tr class="even">
<td></td>
<td>SalesReceipt</td>
<td>The standard receipt.</td>
</tr>
<tr class="odd">
<td></td>
<td>CardReceiptForShop</td>
<td>Credit card receipt for the store.</td>
</tr>
<tr class="even">
<td></td>
<td>CardReceiptForCustomer</td>
<td>Credit card receipt for the customer.</td>
</tr>
<tr class="odd">
<td></td>
<td>CardReceiptForShopReturn</td>
<td>Credit card receipt for the store for return.</td>
</tr>
<tr class="even">
<td></td>
<td>CardReceiptForCustomerReturn</td>
<td>Credit card receipt for the customer for return.</td>
</tr>
<tr class="odd">
<td></td>
<td>CustomerAccountReceiptForShop</td>
<td>Customer account receipt for shop.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerAccountReceiptForCustomer</td>
<td>Customer account receipt for customer.</td>
</tr>
<tr class="odd">
<td></td>
<td>CustomerAccountReceiptForShopReturn</td>
<td>Customer account receipt for shop for return.</td>
</tr>
<tr class="even">
<td></td>
<td>CustomerAccountReceiptForCustomerReturn</td>
<td>Customer account receipt for customer for return.</td>
</tr>
<tr class="odd">
<td></td>
<td>CustomerAccountDeposit</td>
<td>Customer account deposit.</td>
</tr>
<tr class="even">
<td></td>
<td>CreditMemo</td>
<td>Credit memo receipt.</td>
</tr>
<tr class="odd">
<td></td>
<td>SalesOrderReceipt</td>
<td>Sales order receipt.</td>
</tr>
<tr class="even">
<td></td>
<td>GiftCertificate</td>
<td>Gift certificate.</td>
</tr>
<tr class="odd">
<td></td>
<td>QuotationReceipt</td>
<td>Quotation receipt if the customer order type is quotation.</td>
</tr>
<tr class="even">
<td></td>
<td>PackingSlip</td>
<td>Packing slip.</td>
</tr>
<tr class="odd">
<td></td>
<td>PickupReceipt</td>
<td>Pick up receipt for customer orders.</td>
</tr>
<tr class="even">
<td></td>
<td>XReport</td>
<td>Print X report..</td>
</tr>
<tr class="odd">
<td></td>
<td>ZReport</td>
<td>Print Z report.</td>
</tr>
<tr class="even">
<td></td>
<td>SafeDrop</td>
<td>Receipt for a safe drop.</td>
</tr>
<tr class="odd">
<td></td>
<td>BankDrop</td>
<td>Receipt for a bank drop.</td>
</tr>
<tr class="even">
<td></td>
<td>TenderDeclaration</td>
<td>Receipt for a tender declaration.</td>
</tr>
<tr class="odd">
<td></td>
<td>RemoveTender</td>
<td>Receipt for a remove tender.</td>
</tr>
<tr class="even">
<td></td>
<td>FloatEntry</td>
<td>Receipt for a float entry.</td>
</tr>
<tr class="odd">
<td></td>
<td>StartingAmount</td>
<td>Receipt for declarating starting amount.</td>
</tr>
<tr class="even">
<td></td>
<td>ReturnLabel</td>
<td>Return label.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

