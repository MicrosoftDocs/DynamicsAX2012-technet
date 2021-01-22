---
title: Address.DistrictName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DistrictName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.DistrictName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.districtname(v=AX.60)
ms:contentKeyID: 49842426
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.DistrictName
dev_langs:
- CSharp
- C++
- VB
---

# DistrictName Property

Gets or sets the DistrictName.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DISTRICTNAME")> _
<DataMemberAttribute> _
Public Property DistrictName As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.DistrictName

instance.DistrictName = value
```

``` csharp
[ColumnAttribute("DISTRICTNAME")]
[DataMemberAttribute]
public string DistrictName { get; set; }
```

``` c++
[ColumnAttribute(L"DISTRICTNAME")]
[DataMemberAttribute]
public:
property String^ DistrictName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

