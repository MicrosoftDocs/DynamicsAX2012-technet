---
title: SearchArea.Latitude Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Latitude Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.Latitude
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.searcharea.latitude(v=AX.60)
ms:contentKeyID: 49846061
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SearchArea.Latitude
dev_langs:
- CSharp
- C++
- VB
---

# Latitude Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the latitude.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Latitude As Decimal
    Get
    Set
'Usage
Dim instance As SearchArea
Dim value As Decimal

value = instance.Latitude

instance.Latitude = value
```

``` csharp
[DataMemberAttribute]
public decimal Latitude { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Decimal Latitude {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Latitude values must be between -90 and 90 degrees.  

## See Also

#### Reference

[SearchArea Class](searcharea-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

