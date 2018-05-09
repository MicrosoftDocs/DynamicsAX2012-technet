---
title: OrgUnitLocation.Longitude Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Longitude Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Longitude
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.longitude(v=AX.60)
ms:contentKeyID: 62209364
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Longitude
dev_langs:
- CSharp
- C++
- VB
---

# Longitude Property

Gets or sets the location longitude.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LONGITUDE")> _
Public Property Longitude As Decimal
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As Decimal

value = instance.Longitude

instance.Longitude = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LONGITUDE")]
public decimal Longitude { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LONGITUDE")]
public:
property Decimal Longitude {
    Decimal get ();
    void set (Decimal value);
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/en-us/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

