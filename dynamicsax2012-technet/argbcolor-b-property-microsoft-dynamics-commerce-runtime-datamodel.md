---
title: ARGBColor.B Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: B Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ARGBColor.B
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.argbcolor.b(v=AX.60)
ms:contentKeyID: 62204392
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ARGBColor.B
dev_langs:
- CSharp
- C++
- VB
---

# B Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the color blue component value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property B As Byte
    Get
    Set
'Usage
Dim instance As ARGBColor
Dim value As Byte

value = instance.B

instance.B = value
```

``` csharp
[DataMemberAttribute]
public byte B { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property unsigned char B {
    unsigned char get ();
    void set (unsigned char value);
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))  
Returns [Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\)).  

## See Also

#### Reference

[ARGBColor Class](argbcolor-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

