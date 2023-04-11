---
title: TillLayoutExtensions.PopulateZones Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PopulateZones Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayoutExtensions.PopulateZones(Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout,System.Collections.Generic.IEnumerable{Microsoft.Dynamics.Commerce.Runtime.DataModel.ZoneReference})
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.tilllayoutextensions.populatezones(v=AX.60)
ms:contentKeyID: 65319028
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayoutExtensions.PopulateZones
dev_langs:
- CSharp
- C++
- VB
---

# PopulateZones Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Populates till layout entity by layout zones of supported types.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ExtensionAttribute> _
Public Shared Sub PopulateZones ( _
    tillLayout As TillLayout, _
    zones As IEnumerable(Of ZoneReference) _
)
'Usage
Dim tillLayout As TillLayout
Dim zones As IEnumerable(Of ZoneReference)

tillLayout.PopulateZones(zones)
```

``` csharp
public static void PopulateZones(
    this TillLayout tillLayout,
    IEnumerable<ZoneReference> zones
)
```

``` c++
[ExtensionAttribute]
public:
static void PopulateZones(
    TillLayout^ tillLayout, 
    IEnumerable<ZoneReference^>^ zones
)
```

#### Parameters

  - tillLayout  
    Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.TillLayout](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

<!-- end list -->

  - zones  
    Type: [System.Collections.Generic.IEnumerable](https://technet.microsoft.com/library/9eekhta0\(v=ax.60\))\<[ZoneReference](zonereference-class-microsoft-dynamics-commerce-runtime-datamodel.md)\>  

#### Usage Note

In Visual Basic and C\#, you can call this method as an instance method on any object of type [TillLayout](tilllayout-class-microsoft-dynamics-commerce-runtime-datamodel.md). When you use instance method syntax to call this method, omit the first parameter. For more information, see b8020aae-374d-46a9-bcb7-8cc2390b93b6 or 175ce3ff-9bbf-4e64-8421-faeb81a0bb51.

## See Also

#### Reference

[TillLayoutExtensions Class](tilllayoutextensions-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

