---
title: IItemV1.Height Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Height Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.Height
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.iitemv1.height(v=AX.60)
ms:contentKeyID: 49853693
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IItemV1.Height
dev_langs:
- CSharp
- C++
- VB
---

# Height Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the height.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Height As Decimal
    Get
    Set
'Usage
Dim instance As IItemV1
Dim value As Decimal

value = instance.Height

instance.Height = value
```

``` csharp
decimal Height { get; set; }
```

``` c++
property Decimal Height {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
The height.  

## See Also

#### Reference

[IItemV1 Interface](iitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

