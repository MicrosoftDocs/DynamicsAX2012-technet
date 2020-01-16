---
title: PriceGroup.GroupId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GroupId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceGroup.GroupId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.pricegroup.groupid(v=AX.60)
ms:contentKeyID: 49827724
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceGroup.GroupId
dev_langs:
- CSharp
- C++
- VB
---

# GroupId Property

Gets the group identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("GROUPID")> _
<DataMemberAttribute> _
Public Property GroupId As String
    Get
    Set
'Usage
Dim instance As PriceGroup
Dim value As String

value = instance.GroupId

instance.GroupId = value
```

``` csharp
[ColumnAttribute("GROUPID")]
[DataMemberAttribute]
public string GroupId { get; set; }
```

``` c++
[ColumnAttribute(L"GROUPID")]
[DataMemberAttribute]
public:
property String^ GroupId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PriceGroup Class](pricegroup-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

