---
title: IUtilityV3.GetNumberOfDecimals Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: GetNumberOfDecimals Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV3.GetNumberOfDecimals(System.Decimal)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv3.getnumberofdecimals(v=AX.60)
ms:contentKeyID: 51677232
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV3.GetNumberOfDecimals
dev_langs:
- CSharp
- C++
- VB
---

# GetNumberOfDecimals Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the number of decimals of the given currency unit.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function GetNumberOfDecimals ( _
    minimumCurrencyUnit As Decimal _
) As Integer
'Usage
Dim instance As IUtilityV3
Dim minimumCurrencyUnit As Decimal
Dim returnValue As Integer

returnValue = instance.GetNumberOfDecimals(minimumCurrencyUnit)
```

``` csharp
int GetNumberOfDecimals(
    decimal minimumCurrencyUnit
)
```

``` c++
int GetNumberOfDecimals(
    Decimal minimumCurrencyUnit
)
```

#### Parameters

  - minimumCurrencyUnit  
    Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The number of decimals.  

## See Also

#### Reference

[IUtilityV3 Interface](iutilityv3-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

