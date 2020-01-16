---
title: ZipCodeInfo.District Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: District Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo.District
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.zipcodeinfo.district(v=AX.60)
ms:contentKeyID: 49851755
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ZipCodeInfo.District
dev_langs:
- CSharp
- C++
- VB
---

# District Property

Gets or sets the name of the district.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISTRICTNAME")> _
<DataMemberAttribute> _
Public Property District As String
    Get
    Set
'Usage
Dim instance As ZipCodeInfo
Dim value As String

value = instance.District

instance.District = value
```

``` csharp
[ColumnAttribute("DISTRICTNAME")]
[DataMemberAttribute]
public string District { get; set; }
```

``` c++
[ColumnAttribute(L"DISTRICTNAME")]
[DataMemberAttribute]
public:
property String^ District {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[ZipCodeInfo Class](zipcodeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

