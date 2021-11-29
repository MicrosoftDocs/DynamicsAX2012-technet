---
title: ITenderV1.FunctionType Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: FunctionType Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.FunctionType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderv1.functiontype(v=AX.60)
ms:contentKeyID: 49823539
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderV1.FunctionType
dev_langs:
- CSharp
- C++
- VB
---

# FunctionType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

The tender function type (cash, card, account, tender remove / float)

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property FunctionType As Decimal
    Get
    Set
'Usage
Dim instance As ITenderV1
Dim value As Decimal

value = instance.FunctionType

instance.FunctionType = value
```

``` csharp
decimal FunctionType { get; set; }
```

``` c++
property Decimal FunctionType {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ITenderV1 Interface](itenderv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

