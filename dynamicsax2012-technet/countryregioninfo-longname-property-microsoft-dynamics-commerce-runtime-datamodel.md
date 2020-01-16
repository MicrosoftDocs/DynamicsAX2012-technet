---
title: CountryRegionInfo.LongName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LongName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.LongName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.countryregioninfo.longname(v=AX.60)
ms:contentKeyID: 49822617
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CountryRegionInfo.LongName
dev_langs:
- CSharp
- C++
- VB
---

# LongName Property

Gets or sets the long name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("LONGNAME")> _
<DataMemberAttribute> _
Public Property LongName As String
    Get
    Set
'Usage
Dim instance As CountryRegionInfo
Dim value As String

value = instance.LongName

instance.LongName = value
```

``` csharp
[ColumnAttribute("LONGNAME")]
[DataMemberAttribute]
public string LongName { get; set; }
```

``` c++
[ColumnAttribute(L"LONGNAME")]
[DataMemberAttribute]
public:
property String^ LongName {
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

