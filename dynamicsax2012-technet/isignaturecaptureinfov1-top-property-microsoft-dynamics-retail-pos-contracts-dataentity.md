---
title: ISignatureCaptureInfoV1.Top Property  (Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity)
TOCTitle: Top Property
ms:assetid: P:Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISignatureCaptureInfoV1.Top
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.retail.pos.contracts.dataentity.isignaturecaptureinfov1.top(v=AX.60)
ms:contentKeyID: 49842427
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity.ISignatureCaptureInfoV1.Top
dev_langs:
- CSharp
- C++
- VB
---

# Top Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the maximum vertical coordinate of the signature point.

**Namespace:**  [Microsoft.Dynamics.Retail.Pos.Contracts.DataEntity](microsoft-dynamics-retail-pos-contracts-dataentity-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Retail.Pos.Contracts (in Microsoft.Dynamics.Retail.Pos.Contracts.dll)

## Syntax

``` vb
'Declaration
Property Top As Integer
    Get
    Set
'Usage
Dim instance As ISignatureCaptureInfoV1
Dim value As Integer

value = instance.Top

instance.Top = value
```

``` csharp
int Top { get; set; }
```

``` c++
property int Top {
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

