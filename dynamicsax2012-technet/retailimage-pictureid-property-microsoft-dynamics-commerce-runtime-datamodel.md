---
title: RetailImage.PictureId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PictureId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailImage.PictureId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.retailimage.pictureid(v=AX.60)
ms:contentKeyID: 62214746
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailImage.PictureId
dev_langs:
- CSharp
- C++
- VB
---

# PictureId Property

Gets or sets the picture id.

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
Dim instance As RetailImage
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

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[RetailImage Class](retailimage-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

