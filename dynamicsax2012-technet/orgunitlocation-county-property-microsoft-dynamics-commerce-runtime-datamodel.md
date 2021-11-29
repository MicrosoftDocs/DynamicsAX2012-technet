---
title: OrgUnitLocation.County Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: County Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.County
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.county(v=AX.60)
ms:contentKeyID: 62208296
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.County
dev_langs:
- CSharp
- C++
- VB
---

# County Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the location county.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("COUNTY")> _
Public Property County As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.County

instance.County = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("COUNTY")]
public string County { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"COUNTY")]
public:
property String^ County {
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

