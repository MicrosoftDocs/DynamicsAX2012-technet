---
title: OrgUnitLocation.PostalAddressId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PostalAddressId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.PostalAddressId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.postaladdressid(v=AX.60)
ms:contentKeyID: 62208847
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.PostalAddressId
dev_langs:
- CSharp
- C++
- VB
---

# PostalAddressId Property

Gets or sets the postal address identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("POSTALADDRESSRECID")> _
Public Property PostalAddressId As Long
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As Long

value = instance.PostalAddressId

instance.PostalAddressId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("POSTALADDRESSRECID")]
public long PostalAddressId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"POSTALADDRESSRECID")]
public:
property long long PostalAddressId {
    long long get ();
    void set (long long value);
}
```

#### Property Value

Type: [System.Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\))  
Returns [Int64](https://technet.microsoft.com/library/6yy583ek\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

