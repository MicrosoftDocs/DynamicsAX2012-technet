---
title: RichMediaLocations.Items Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Items Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations.Items
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.richmedialocations.items(v=AX.60)
ms:contentKeyID: 62213411
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocations.Items
dev_langs:
- CSharp
- C++
- VB
---

# Items Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Items As RichMediaLocationsRichMediaLocation()
    Get
    Set
'Usage
Dim instance As RichMediaLocations
Dim value As RichMediaLocationsRichMediaLocation()

value = instance.Items

instance.Items = value
```

``` csharp
[DataMemberAttribute]
public RichMediaLocationsRichMediaLocation[] Items { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property array<RichMediaLocationsRichMediaLocation^>^ Items {
    array<RichMediaLocationsRichMediaLocation^>^ get ();
    void set (array<RichMediaLocationsRichMediaLocation^>^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.RichMediaLocationsRichMediaLocation](richmedialocationsrichmedialocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)\[\]  
Returns [RichMediaLocationsRichMediaLocation](richmedialocationsrichmedialocation-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[RichMediaLocations Class](richmedialocations-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

