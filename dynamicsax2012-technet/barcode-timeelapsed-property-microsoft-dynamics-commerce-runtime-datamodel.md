---
title: Barcode.TimeElapsed Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeElapsed Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.TimeElapsed
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.barcode.timeelapsed(v=AX.60)
ms:contentKeyID: 62213724
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Barcode.TimeElapsed
dev_langs:
- CSharp
- C++
- VB
---

# TimeElapsed Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property TimeElapsed As TimeSpan
    Get
    Set
'Usage
Dim instance As Barcode
Dim value As TimeSpan

value = instance.TimeElapsed

instance.TimeElapsed = value
```

``` csharp
[IgnoreDataMemberAttribute]
public TimeSpan TimeElapsed { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property TimeSpan TimeElapsed {
    TimeSpan get ();
    void set (TimeSpan value);
}
```

#### Property Value

Type: [System.TimeSpan](https://technet.microsoft.com/library/269ew577\(v=ax.60\))  

## See Also

#### Reference

[Barcode Class](barcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

