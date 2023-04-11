---
title: ARGBColor.A Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: A Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ARGBColor.A
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.argbcolor.a(v=AX.60)
ms:contentKeyID: 62212224
author: tfehr
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ARGBColor.A
dev_langs:
- CSharp
- C++
- VB
---

# A Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the color alpha value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property A As Byte
    Get
    Set
'Usage
Dim instance As ARGBColor
Dim value As Byte

value = instance.A

instance.A = value
```

``` csharp
[DataMemberAttribute]
public byte A { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property unsigned char A {
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

