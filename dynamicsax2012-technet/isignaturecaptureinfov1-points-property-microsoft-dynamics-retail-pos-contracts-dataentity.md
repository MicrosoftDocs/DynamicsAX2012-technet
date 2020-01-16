---
title: ISignatureCaptureInfoV1.Points Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Points Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISignatureCaptureInfoV1.Points
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isignaturecaptureinfov1.points(v=AX.60)
ms:contentKeyID: 49842725
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISignatureCaptureInfoV1.Points
dev_langs:
- CSharp
- C++
- VB
---

# Points Property

Gets the collection of signature points.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Points As ReadOnlyCollection(Of Point)
    Get
    Set
'Usage
Dim instance As ISignatureCaptureInfoV1
Dim value As ReadOnlyCollection(Of Point)

value = instance.Points

instance.Points = value
```

``` csharp
ReadOnlyCollection<Point> Points { get; set; }
```

``` c++
property ReadOnlyCollection<Point>^ Points {
    ReadOnlyCollection<Point>^ get ();
    void set (ReadOnlyCollection<Point>^ value);
}
```

#### Property Value

Type: [System.Collections.ObjectModel.ReadOnlyCollection](https://technet.microsoft.com/library/ms132474\(v=ax.60\))\<[Point](https://technet.microsoft.com/library/bk9hwzbw\(v=ax.60\))\>  
Returns [ReadOnlyCollection\<T\>](https://technet.microsoft.com/library/ms132474\(v=ax.60\)).  

## See Also

#### Reference

[ISignatureCaptureInfoV1 Interface](isignaturecaptureinfov1-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

