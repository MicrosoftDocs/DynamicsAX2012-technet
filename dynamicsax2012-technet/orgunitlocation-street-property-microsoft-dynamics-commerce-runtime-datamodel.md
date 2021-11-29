---
title: OrgUnitLocation.Street Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Street Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Street
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.street(v=AX.60)
ms:contentKeyID: 62208124
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Street
dev_langs:
- CSharp
- C++
- VB
---

# Street Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the location street.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STREET")> _
Public Property Street As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.Street

instance.Street = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STREET")]
public string Street { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STREET")]
public:
property String^ Street {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

