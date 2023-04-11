---
title: OrgUnit.OrgUnitName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnitName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.OrgUnitName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.orgunitname(v=AX.60)
ms:contentKeyID: 62209311
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.OrgUnitName
dev_langs:
- CSharp
- C++
- VB
---

# OrgUnitName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the organization unit name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STORENAME")> _
<DataMemberAttribute> _
Public Property OrgUnitName As String
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As String

value = instance.OrgUnitName

instance.OrgUnitName = value
```

``` csharp
[ColumnAttribute("STORENAME")]
[DataMemberAttribute]
public string OrgUnitName { get; set; }
```

``` c++
[ColumnAttribute(L"STORENAME")]
[DataMemberAttribute]
public:
property String^ OrgUnitName {
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

