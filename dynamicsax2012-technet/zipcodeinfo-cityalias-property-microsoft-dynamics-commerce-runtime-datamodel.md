---
title: ZipCodeInfo.CityAlias Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CityAlias Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo.CityAlias
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.zipcodeinfo.cityalias(v=AX.60)
ms:contentKeyID: 49852672
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo.CityAlias
dev_langs:
- CSharp
- C++
- VB
---

# CityAlias Property

Gets or sets the city alias.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CITYALIAS")> _
<DataMemberAttribute> _
Public Property CityAlias As String
    Get
    Set
'Usage
Dim instance As ZipCodeInfo
Dim value As String

value = instance.CityAlias

instance.CityAlias = value
```

``` csharp
[ColumnAttribute("CITYALIAS")]
[DataMemberAttribute]
public string CityAlias { get; set; }
```

``` c++
[ColumnAttribute(L"CITYALIAS")]
[DataMemberAttribute]
public:
property String^ CityAlias {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ZipCodeInfo Class](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

