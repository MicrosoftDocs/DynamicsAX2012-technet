---
title: SearchArea.Longitude Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Longitude Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.Longitude
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.searcharea.longitude(v=AX.60)
ms:contentKeyID: 49842746
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.Longitude
dev_langs:
- CSharp
- C++
- VB
---

# Longitude Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the longitude.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Longitude As Decimal
    Get
    Set
'Usage
Dim instance As SearchArea
Dim value As Decimal

value = instance.Longitude

instance.Longitude = value
```

``` csharp
[DataMemberAttribute]
public decimal Longitude { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Longitude {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Longitude values must be between -15069 and 15069 degrees.  

## See Also

#### Reference

[SearchArea Class](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

