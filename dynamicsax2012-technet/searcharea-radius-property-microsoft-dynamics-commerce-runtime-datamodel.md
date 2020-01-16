---
title: SearchArea.Radius Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Radius Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.Radius
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.searcharea.radius(v=AX.60)
ms:contentKeyID: 49845761
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.Radius
dev_langs:
- CSharp
- C++
- VB
---

# Radius Property

Gets or sets the radius.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Radius As Double
    Get
    Set
'Usage
Dim instance As SearchArea
Dim value As Double

value = instance.Radius

instance.Radius = value
```

``` csharp
[DataMemberAttribute]
public double Radius { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property double Radius {
    double get ();
    void set (double value);
}
```

#### Property Value

Type: [System.Double](https://technet.microsoft.com/library/643eft0t\(v=ax.60\))  
A non-negative radius.  

## See Also

#### Reference

[SearchArea Class](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

