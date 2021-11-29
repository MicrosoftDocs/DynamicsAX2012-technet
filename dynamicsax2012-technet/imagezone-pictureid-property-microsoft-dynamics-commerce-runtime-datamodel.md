---
title: ImageZone.PictureId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PictureId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ImageZone.PictureId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.imagezone.pictureid(v=AX.60)
ms:contentKeyID: 62214475
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ImageZone.PictureId
dev_langs:
- CSharp
- C++
- VB
---

# PictureId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value of picture identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PICTUREID")> _
Public Property PictureId As Integer
    Get
    Set
'Usage
Dim instance As ImageZone
Dim value As Integer

value = instance.PictureId

instance.PictureId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PICTUREID")]
public int PictureId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PICTUREID")]
public:
property int PictureId {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[ImageZone Class](imagezone-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

