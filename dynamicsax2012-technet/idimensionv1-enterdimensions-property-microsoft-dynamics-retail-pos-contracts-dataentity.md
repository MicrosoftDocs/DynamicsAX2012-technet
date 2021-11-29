---
title: IDimensionV1.EnterDimensions Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: EnterDimensions Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDimensionV1.EnterDimensions
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.idimensionv1.enterdimensions(v=AX.60)
ms:contentKeyID: 49839135
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.IDimensionV1.EnterDimensions
dev_langs:
- CSharp
- C++
- VB
---

# EnterDimensions Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Is set true if color,size,style,config info found, else false

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property EnterDimensions As Boolean
    Get
    Set
'Usage
Dim instance As IDimensionV1
Dim value As Boolean

value = instance.EnterDimensions

instance.EnterDimensions = value
```

``` csharp
bool EnterDimensions { get; set; }
```

``` c++
property bool EnterDimensions {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[IDimensionV1 Interface](idimensionv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

