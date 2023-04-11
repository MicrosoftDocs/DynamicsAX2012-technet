---
title: ICustomerSystemV3.ResetCustomerTaxGroup Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ResetCustomerTaxGroup Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV3.ResetCustomerTaxGroup(Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.icustomersystemv3.resetcustomertaxgroup(v=AX.60)
ms:contentKeyID: 62205585
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.ICustomerSystemV3.ResetCustomerTaxGroup
dev_langs:
- CSharp
- C++
- VB
---

# ResetCustomerTaxGroup Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Reset all taxable items pertaining to the transaction.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Sub ResetCustomerTaxGroup ( _
    retailTransaction As IRetailTransaction _
)
'Usage
Dim instance As ICustomerSystemV3
Dim retailTransaction As IRetailTransaction

instance.ResetCustomerTaxGroup(retailTransaction)
```

``` csharp
void ResetCustomerTaxGroup(
    IRetailTransaction retailTransaction
)
```

``` c++
void ResetCustomerTaxGroup(
    IRetailTransaction^ retailTransaction
)
```

#### Parameters

  - retailTransaction  
    Type: [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IRetailTransaction](iretailtransaction-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)  

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
<td><a href="https://technet.microsoft.com/library/27426hcy(v=ax.60)">ArgumentNullException</a></td>
<td><p>Thrown when RetailTransaction is NULL</p></td>
</tr>
</tbody>
</table>


## See Also

#### Reference

[ICustomerSystemV3 Interface](icustomersystemv3-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

