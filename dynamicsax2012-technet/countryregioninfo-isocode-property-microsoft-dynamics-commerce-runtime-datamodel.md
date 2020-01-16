---
title: CountryRegionInfo.ISOCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ISOCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.ISOCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.countryregioninfo.isocode(v=AX.60)
ms:contentKeyID: 49851446
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.ISOCode
dev_langs:
- CSharp
- C++
- VB
---

# ISOCode Property

Gets or sets the ISO code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISOCODE")> _
Public Property ISOCode As String
    Get
    Set
'Usage
Dim instance As CountryRegionInfo
Dim value As String

value = instance.ISOCode

instance.ISOCode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISOCODE")]
public string ISOCode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISOCODE")]
public:
property String^ ISOCode {
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

