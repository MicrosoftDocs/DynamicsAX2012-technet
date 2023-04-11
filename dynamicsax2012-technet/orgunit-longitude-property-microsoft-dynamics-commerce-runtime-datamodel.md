---
title: OrgUnit.Longitude Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Longitude Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.Longitude
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.longitude(v=AX.60)
ms:contentKeyID: 65322262
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.Longitude
dev_langs:
- CSharp
- C++
- VB
---

# Longitude Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LONGITUDE")> _
<DataMemberAttribute> _
Public Property Longitude As Decimal
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As Decimal

value = instance.Longitude

instance.Longitude = value
```

``` csharp
[ColumnAttribute("LONGITUDE")]
[DataMemberAttribute]
public decimal Longitude { get; set; }
```

``` c++
[ColumnAttribute(L"LONGITUDE")]
[DataMemberAttribute]
public:
property Decimal Longitude {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

