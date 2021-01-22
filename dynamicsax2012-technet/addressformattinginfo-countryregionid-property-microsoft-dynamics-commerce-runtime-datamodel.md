---
title: AddressFormattingInfo.CountryRegionId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CountryRegionId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.CountryRegionId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.addressformattinginfo.countryregionid(v=AX.60)
ms:contentKeyID: 62209956
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.AddressFormattingInfo.CountryRegionId
dev_langs:
- CSharp
- C++
- VB
---

# CountryRegionId Property

Gets or sets the country/region identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COUNTRYREGIONID")> _
<IgnoreDataMemberAttribute> _
Public Property CountryRegionId As String
    Get
    Set
'Usage
Dim instance As AddressFormattingInfo
Dim value As String

value = instance.CountryRegionId

instance.CountryRegionId = value
```

``` csharp
[ColumnAttribute("COUNTRYREGIONID")]
[IgnoreDataMemberAttribute]
public string CountryRegionId { get; set; }
```

``` c++
[ColumnAttribute(L"COUNTRYREGIONID")]
[IgnoreDataMemberAttribute]
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

[AddressFormattingInfo Class](addressformattinginfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

