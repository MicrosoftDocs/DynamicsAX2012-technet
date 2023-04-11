---
title: ButtonGridButton.Picture Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Picture Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.Picture
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.buttongridbutton.picture(v=AX.60)
ms:contentKeyID: 65317622
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ButtonGridButton.Picture
dev_langs:
- CSharp
- C++
- VB
---

# Picture Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("PICTURE")> _
Public Property Picture As Byte()
    Get
    Set
'Usage
Dim instance As ButtonGridButton
Dim value As Byte()

value = instance.Picture

instance.Picture = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("PICTURE")]
public byte[] Picture { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"PICTURE")]
public:
property array<unsigned char>^ Picture {
    array<unsigned char>^ get ();
    void set (array<unsigned char>^ value);
}
```

#### Property Value

Type: [System.Byte](https://technet.microsoft.com/library/yyb1w04y\(v=ax.60\))\[\]  

## See Also

#### Reference

[ButtonGridButton Class](buttongridbutton-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

