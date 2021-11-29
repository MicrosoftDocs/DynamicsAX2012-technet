---
title: SearchArea.DistanceUnitValue Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DistanceUnitValue Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.DistanceUnitValue
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.searcharea.distanceunitvalue(v=AX.60)
ms:contentKeyID: 62212763
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.DistanceUnitValue
dev_langs:
- CSharp
- C++
- VB
---

# DistanceUnitValue Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the distance unit. Used for OData.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property DistanceUnitValue As Integer
    Get
    Set
'Usage
Dim instance As SearchArea
Dim value As Integer

value = instance.DistanceUnitValue

instance.DistanceUnitValue = value
```

``` csharp
[DataMemberAttribute]
public int DistanceUnitValue { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int DistanceUnitValue {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The distance unit.  

## See Also

#### Reference

[SearchArea Class](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

