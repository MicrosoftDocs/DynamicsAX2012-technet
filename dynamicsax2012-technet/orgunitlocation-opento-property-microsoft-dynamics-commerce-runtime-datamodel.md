---
title: OrgUnitLocation.OpenTo Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OpenTo Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.OpenTo
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.opento(v=AX.60)
ms:contentKeyID: 62204752
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.OpenTo
dev_langs:
- CSharp
- C++
- VB
---

# OpenTo Property

Gets or sets the open to value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("OPENTO")> _
<DataMemberAttribute> _
Public Property OpenTo As Integer
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As Integer

value = instance.OpenTo

instance.OpenTo = value
```

``` csharp
[ColumnAttribute("OPENTO")]
[DataMemberAttribute]
public int OpenTo { get; set; }
```

``` c++
[ColumnAttribute(L"OPENTO")]
[DataMemberAttribute]
public:
property int OpenTo {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

