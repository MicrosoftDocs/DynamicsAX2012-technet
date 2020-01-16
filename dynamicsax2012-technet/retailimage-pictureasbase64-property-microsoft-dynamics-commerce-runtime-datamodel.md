---
title: RetailImage.PictureAsBase64 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PictureAsBase64 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailImage.PictureAsBase64
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.retailimage.pictureasbase64(v=AX.60)
ms:contentKeyID: 62212471
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RetailImage.PictureAsBase64
dev_langs:
- CSharp
- C++
- VB
---

# PictureAsBase64 Property

Gets or sets the button picture as base64 string.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property PictureAsBase64 As String
    Get
    Set
'Usage
Dim instance As RetailImage
Dim value As String

value = instance.PictureAsBase64

instance.PictureAsBase64 = value
```

``` csharp
[DataMemberAttribute]
public string PictureAsBase64 { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ PictureAsBase64 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[RetailImage Class](retailimage-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

