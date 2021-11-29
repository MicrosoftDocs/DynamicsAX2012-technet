---
title: IUtilityV1.ToDecimal Method  (Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic)
TOCTitle: ToDecimal Method
ms:assetid: M:Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.ToDecimal(System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.businesslogic.iutilityv1.todecimal(v=AX.60)
ms:contentKeyID: 47129355
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic.IUtilityV1.ToDecimal
dev_langs:
- CSharp
- C++
- VB
---

# ToDecimal Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Converts value to a decimal.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Function ToDecimal ( _
    value As Object _
) As Decimal
'Usage
Dim instance As IUtilityV1
Dim value As Object
Dim returnValue As Decimal

returnValue = instance.ToDecimal(value)
```

``` csharp
decimal ToDecimal(
    Object value
)
```

``` c++
Decimal ToDecimal(
    Object^ value
)
```

#### Parameters

  - value  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The decimal value or 0 if conversion fails.  

## See Also

#### Reference

[IUtilityV1 Interface](iutilityv1-interface-microsoft-dynamics-retail-pos-contracts-businesslogic.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.BusinessLogic Namespace](microsoft-dynamics-retail-pos-contracts-businesslogic-namespace.md)

