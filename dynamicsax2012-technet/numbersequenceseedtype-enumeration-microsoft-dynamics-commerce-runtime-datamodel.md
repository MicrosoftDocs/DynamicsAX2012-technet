---
title: NumberSequenceSeedType Enumeration (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NumberSequenceSeedType Enumeration
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.numbersequenceseedtype(v=AX.60)
ms:contentKeyID: 62205547
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.None
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.ReceiptCustomerQuote
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.BatchId
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.ReceiptCustomerSalesOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.TransactionId
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.ReceiptSalesOrder
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.ReceiptPayment
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.ReceiptDefault
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.ReceiptReturn
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.ReceiptSale
- Microsoft.Dynamics.Commerce.Runtime.DataModel.NumberSequenceSeedType.ReceiptSalesInvoice
dev_langs:
- CSharp
- C++
- VB
---

# NumberSequenceSeedType Enumeration


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Number sequence counter type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Enumeration NumberSequenceSeedType
'Usage
Dim instance As NumberSequenceSeedType
```

``` csharp
[DataContractAttribute]
public enum NumberSequenceSeedType
```

``` c++
[DataContractAttribute]
public enum class NumberSequenceSeedType
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
<td>None</td>
<td>Unknown type.</td>
</tr>
<tr class="even">
<td></td>
<td>ReceiptDefault</td>
<td>Default number sequence for receipt identifier.</td>
</tr>
<tr class="odd">
<td></td>
<td>ReceiptSale</td>
<td>Receipt identifier for sales transaction.</td>
</tr>
<tr class="even">
<td></td>
<td>ReceiptReturn</td>
<td>Receipt identifier for return transaction.</td>
</tr>
<tr class="odd">
<td></td>
<td>ReceiptSalesOrder</td>
<td>Receipt identifier for sales order.</td>
</tr>
<tr class="even">
<td></td>
<td>ReceiptSalesInvoice</td>
<td>Receipt identifier for sales invoice.</td>
</tr>
<tr class="odd">
<td></td>
<td>ReceiptPayment</td>
<td>Receipt identifier for payment.</td>
</tr>
<tr class="even">
<td></td>
<td>BatchId</td>
<td>Batch identifier.</td>
</tr>
<tr class="odd">
<td></td>
<td>TransactionId</td>
<td>Transaction identifier.</td>
</tr>
<tr class="even">
<td></td>
<td>ReceiptCustomerSalesOrder</td>
<td>Receipt identifier for customer sales order.</td>
</tr>
<tr class="odd">
<td></td>
<td>ReceiptCustomerQuote</td>
<td>Receipt identifier for customer quote.</td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

