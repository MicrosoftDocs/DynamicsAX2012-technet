---
title: CountryRegionInfo.CountryRegionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CountryRegionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.CountryRegionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.countryregioninfo.countryregionid(v=AX.60)
ms:contentKeyID: 49849441
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.CountryRegionId
dev_langs:
- CSharp
- C++
- VB
---

# CountryRegionId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the country/region identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COUNTRYREGIONID")> _
<KeyAttribute> _
<DataMemberAttribute> _
Public Property CountryRegionId As String
    Get
    Set
'Usage
Dim instance As CountryRegionInfo
Dim value As String

value = instance.CountryRegionId

instance.CountryRegionId = value
```

``` csharp
[ColumnAttribute("COUNTRYREGIONID")]
[KeyAttribute]
[DataMemberAttribute]
public string CountryRegionId { get; set; }
```

``` c++
[ColumnAttribute(L"COUNTRYREGIONID")]
[KeyAttribute]
[DataMemberAttribute]
public:
property String^ CountryRegionId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CountryRegionInfo Class](countryregioninfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

