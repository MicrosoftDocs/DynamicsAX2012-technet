---
title: CityInfo.CountyId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CountyId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CityInfo.CountyId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cityinfo.countyid(v=AX.60)
ms:contentKeyID: 49821282
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CityInfo.CountyId
dev_langs:
- CSharp
- C++
- VB
---

# CountyId Property

Gets or sets the county identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COUNTYID")> _
Public Property CountyId As String
    Get
    Set
'Usage
Dim instance As CityInfo
Dim value As String

value = instance.CountyId

instance.CountyId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COUNTYID")]
public string CountyId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COUNTYID")]
public:
property String^ CountyId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CityInfo Class](cityinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

