---
title: ITenderLineItemV2.SignatureData Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: SignatureData Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV2.SignatureData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.itenderlineitemv2.signaturedata(v=AX.60)
ms:contentKeyID: 49830249
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ITenderLineItemV2.SignatureData
dev_langs:
- CSharp
- C++
- VB
---

# SignatureData Property

Signature capture data.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property SignatureData As ICollection(Of Point)
    Get
'Usage
Dim instance As ITenderLineItemV2
Dim value As ICollection(Of Point)

value = instance.SignatureData
```

``` csharp
ICollection<Point> SignatureData { get; }
```

``` c++
property ICollection<Point>^ SignatureData {
    ICollection<Point>^ get ();
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[Point](https://technet.microsoft.com/library/bk9hwzbw\(v=ax.60\))\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[ITenderLineItemV2 Interface](itenderlineitemv2-interface-microsoft-dynamics-retail-pos-contracts-dataentity.md)

[Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity Namespace](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)

