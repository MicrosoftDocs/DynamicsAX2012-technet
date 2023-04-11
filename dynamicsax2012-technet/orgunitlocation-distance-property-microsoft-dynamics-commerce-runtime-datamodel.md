---
title: OrgUnitLocation.Distance Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Distance Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Distance
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.distance(v=AX.60)
ms:contentKeyID: 62214192
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Distance
dev_langs:
- CSharp
- C++
- VB
---

# Distance Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the distance to the location.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISTANCE")> _
<DataMemberAttribute> _
Public Property Distance As Double
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As Double

value = instance.Distance

instance.Distance = value
```

``` csharp
[ColumnAttribute("DISTANCE")]
[DataMemberAttribute]
public double Distance { get; set; }
```

``` c++
[ColumnAttribute(L"DISTANCE")]
[DataMemberAttribute]
public:
property double Distance {
    double get ();
    void set (double value);
}
```

#### Property Value

Type: [System.Double](https://technet.microsoft.com/library/643eft0t\(v=ax.60\))  
Returns [Double](https://technet.microsoft.com/library/643eft0t\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

