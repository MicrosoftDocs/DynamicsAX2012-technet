---
title: CountryRegionInfo.TimeZone Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TimeZone Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.TimeZone
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.countryregioninfo.timezone(v=AX.60)
ms:contentKeyID: 49824836
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.TimeZone
dev_langs:
- CSharp
- C++
- VB
---

# TimeZone Property

Gets or sets the time zone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TIMEZONE")> _
<DataMemberAttribute> _
Public Property TimeZone As Integer
    Get
    Set
'Usage
Dim instance As CountryRegionInfo
Dim value As Integer

value = instance.TimeZone

instance.TimeZone = value
```

``` csharp
[ColumnAttribute("TIMEZONE")]
[DataMemberAttribute]
public int TimeZone { get; set; }
```

``` c++
[ColumnAttribute(L"TIMEZONE")]
[DataMemberAttribute]
public:
property int TimeZone {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CountryRegionInfo Class](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

