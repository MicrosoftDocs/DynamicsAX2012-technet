---
title: OrgUnit.OrgUnitFullAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnitFullAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.OrgUnitFullAddress
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.orgunitfulladdress(v=AX.60)
ms:contentKeyID: 62208878
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.OrgUnitFullAddress
dev_langs:
- CSharp
- C++
- VB
---

# OrgUnitFullAddress Property

Gets or sets the full organization unit address in text.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STOREADDRESS")> _
Public Property OrgUnitFullAddress As String
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As String

value = instance.OrgUnitFullAddress

instance.OrgUnitFullAddress = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STOREADDRESS")]
public string OrgUnitFullAddress { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STOREADDRESS")]
public:
property String^ OrgUnitFullAddress {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

