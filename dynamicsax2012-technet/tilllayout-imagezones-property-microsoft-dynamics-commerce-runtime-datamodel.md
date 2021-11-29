---
title: TillLayout.ImageZones Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ImageZones Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ImageZones
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayout.imagezones(v=AX.60)
ms:contentKeyID: 62208434
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout.ImageZones
dev_langs:
- CSharp
- C++
- VB
---

# ImageZones Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the collection of image zones.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ImageZones As ICollection(Of ImageZone)
    Get
    Set
'Usage
Dim instance As TillLayout
Dim value As ICollection(Of ImageZone)

value = instance.ImageZones

instance.ImageZones = value
```

``` csharp
[DataMemberAttribute]
public ICollection<ImageZone> ImageZones { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property ICollection<ImageZone^>^ ImageZones {
    ICollection<ImageZone^>^ get ();
    void set (ICollection<ImageZone^>^ value);
}
```

#### Property Value

Type: [System.Collections.Generic.ICollection](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\))\<[ImageZone](imagezone-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  
Returns [ICollection\<T\>](https://technet.microsoft.com/library/92t2ye13\(v=ax.60\)).  

## See Also

#### Reference

[TillLayout Class](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

