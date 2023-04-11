---
title: ISignatureCaptureInfoV1.Bottom Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Bottom Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISignatureCaptureInfoV1.Bottom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isignaturecaptureinfov1.bottom(v=AX.60)
ms:contentKeyID: 49852008
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISignatureCaptureInfoV1.Bottom
dev_langs:
- CSharp
- C++
- VB
---

# Bottom Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the minimum vertical coordinate of the signature point.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Bottom As Integer
    Get
    Set
'Usage
Dim instance As ISignatureCaptureInfoV1
Dim value As Integer

value = instance.Bottom

instance.Bottom = value
```

``` csharp
int Bottom { get; set; }
```

``` c++
property int Bottom {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ISignatureCaptureInfoV1 Interface](isignaturecaptureinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

