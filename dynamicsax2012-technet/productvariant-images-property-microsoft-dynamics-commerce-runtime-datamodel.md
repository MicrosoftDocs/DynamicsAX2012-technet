---
title: ProductVariant.Images Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Images Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Images
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productvariant.images(v=AX.60)
ms:contentKeyID: 62212258
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductVariant.Images
dev_langs:
- CSharp
- C++
- VB
---

# Images Property

Gets or sets the image.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Images As IEnumerable(Of RichMediaLocations)
    Get
    Set
'Usage
Dim instance As ProductVariant
Dim value As IEnumerable(Of RichMediaLocations)

value = instance.Images

instance.Images = value
```

``` csharp
[DataMemberAttribute]
public IEnumerable<RichMediaLocations> Images { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property IEnumerable<RichMediaLocations^>^ Images {
    IEnumerable<RichMediaLocations^>^ get ();
    void set (IEnumerable<RichMediaLocations^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/en-us/library/9eekhta0\(v=ax.60\))\<[RichMediaLocations](richmedialocations-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
The image.  

## See Also

#### Reference

[ProductVariant Class](productvariant-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

