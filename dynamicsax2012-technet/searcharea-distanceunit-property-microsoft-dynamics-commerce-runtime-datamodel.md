---
title: SearchArea.DistanceUnit Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DistanceUnit Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.DistanceUnit
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.searcharea.distanceunit(v=AX.60)
ms:contentKeyID: 49852666
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.DistanceUnit
dev_langs:
- CSharp
- C++
- VB
---

# DistanceUnit Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the distance unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Property DistanceUnit As DistanceUnit
    Get
    Set
'Usage
Dim instance As SearchArea
Dim value As DistanceUnit

value = instance.DistanceUnit

instance.DistanceUnit = value
```

``` csharp
[IgnoreDataMemberAttribute]
public DistanceUnit DistanceUnit { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
property DistanceUnit DistanceUnit {
    DistanceUnit get ();
    void set (DistanceUnit value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.DistanceUnit](distanceunit-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
The distance unit.  

## See Also

#### Reference

[SearchArea Class](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

