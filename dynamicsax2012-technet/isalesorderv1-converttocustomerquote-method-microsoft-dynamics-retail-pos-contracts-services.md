---
title: ISalesOrderV1.ConvertToCustomerQuote Method  (Microsoft.Dynamics.Retail.Pos.Contracts.Services)
TOCTitle: ConvertToCustomerQuote Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.ConvertToCustomerQuote(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.services.isalesorderv1.converttocustomerquote(v=AX.60)
ms:contentKeyID: 47344208
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.Services.ISalesOrderV1.ConvertToCustomerQuote
dev_langs:
- CSharp
- C++
- VB
---

# ConvertToCustomerQuote Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts the given transaction into a customer quote.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.Services](microsoft-dynamics-retail-pos-contracts-services-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ConvertToCustomerQuote ( _
    retailTransaction As IRetailTransaction _
) As ICustomerOrderTransaction
'Usage
Dim instance As ISalesOrderV1
Dim retailTransaction As IRetailTransaction
Dim returnValue As ICustomerOrderTransaction

returnValue = instance.ConvertToCustomerQuote(retailTransaction)
```

``` csharp
ICustomerOrderTransaction ConvertToCustomerQuote(
    IRetailTransaction retailTransaction
)
```

``` c++
ICustomerOrderTransaction^ ConvertToCustomerQuote(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

#### Return Value

Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ICustomerOrderTransaction](icustomerordertransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  
The customer order transaction.  

## Exceptions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Exception</th>
<th>Condition</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="https://technet.microsoft.com/library/2asft85a(v=ax.60)">InvalidOperationException</a></td>
<td><p>Thrown if conversion is not supported from the given transaction.</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ISalesOrderV1 Interface](isalesorderv1-interface-microsoft-dynamics-retail-pos-contracts-services.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.Services Namespace](microsoft-dynamics-retail-pos-contracts-services-namespace.md)

