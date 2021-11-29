---
title: ILineItemV1.Voided Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Voided Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineItemV1.Voided
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.ilineitemv1.voided(v=AX.60)
ms:contentKeyID: 49842460
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ILineItemV1.Voided
dev_langs:
- CSharp
- C++
- VB
---

# Voided Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Is set to true if line has been voided

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Voided As Boolean
    Get
    Set
'Usage
Dim instance As ILineItemV1
Dim value As Boolean

value = instance.Voided

instance.Voided = value
```

``` csharp
bool Voided { get; set; }
```

``` c++
property bool Voided {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[ILineItemV1 Interface](ilineitemv1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

